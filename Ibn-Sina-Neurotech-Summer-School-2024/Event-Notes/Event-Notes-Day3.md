
# 📝 Event Notes – Day 3

## **Day 3 – Tuesday, 10 September 2024**

**EEG Signal Processing Techniques and Feature Extraction**

---

### **Session 3: EEG Signal Processing Techniques and Feature Extraction — Dr. Abdelkader Nasreddine**

**Key Takeaways:**

* **Computational Intelligence for EEG-based BCI:**

  * Pre-processed EEG signals → feature extraction → classifier → BCI output.
  * Feature extraction is critical: poor features → inaccurate classification.
* **Feature Types:**

  * **Temporal (Time) Features:** Based on signal amplitude over time, e.g., P300.
  * **Spectral (Frequency) Features:** Band-power analysis, e.g., SSVEP; isolate via band-pass filter.
  * **Time-Frequency Features:** Combines time and frequency; e.g., wavelet analysis for motor imagery (MI).
* **Feature Classification in BCI:**

  * Converts extracted features into device control commands (continuous or discrete).
  * **Linear Models:** Linear Discriminant Analysis (LDA) – efficient, low computational cost, suitable for online BCI.
  * **Non-linear Models:** Artificial Neural Networks (ANNs) – can capture complex, non-linear relationships; learns patterns without predefined features.
* **Sensor-level vs Source-level EEG Analysis:**

  * **Sensor-level (Scalp electrodes):** Direct, efficient, captures overall patterns; limited by volume conduction.
  * **Source-level:** Localizes brain activity sources; precise but computationally intensive and noise-sensitive.
* **Post-processing & Data Epoching:**

  * Continuous EEG → segmented into epochs [electrodes × time × trials].
  * **Time-locked vs Phase-locked:** Signal changes at same time or phase across trials.
  * **Evoked vs Induced Activity:** Evoked → stimulus-driven, phase-locked; Induced → top-down processes, not necessarily phase-locked.
* **ERP (Event-Related Potentials):**

  * Time-locked response to stimuli; average across trials to enhance SNR.
  * Characterized by amplitude, latency, polarity, and scalp distribution (e.g., P300).
* **ERO (Event-Related Oscillations):**

  * Frequency-specific changes (theta, alpha, beta, gamma); often analyzed via time-frequency techniques.
* **Motor & Mental Imagery:**

  * Motor imagery → changes in sensorimotor frequency bands.
  * Mental imagery → visualizations or abstract concepts → induced oscillatory changes.


### **Tutorial 3: EEG Temporal and Spectral Analysis — Dr. Mohamed Zaky**

**Key Takeaways:**

* **ERP Analysis Workflow:**

  * Epoch extraction → baseline correction → channel visualization → manual/automatic artifact rejection.
  * Tools: EEGLAB GUI (Plot > Channel data, Plot > Channel ERPs, ERP scalp maps).
  * Components: peak amplitude, mean amplitude, peak latency, topographic mapping.

* **Group-level Analysis:**

  * Multi-level approach: first level → individual subjects; second level → groups.
  * Data organized using **BIDS** (Brain Imaging Data Structure).
  * Preprocessing: clean raw data, ASR, ICA, re-reference, channel interpolation.
  * Study design setup → precompute measures → visualize ERPs per channel or across all channels.

* **SSVEP Feature Analysis:**

  * Frequency domain analysis (Fourier Transform) to extract power at stimulus frequencies.
  * Classification via LDA, SVM, or deep learning.
  * ICA can separate SSVEP from other brain activity.

* **SSVEP Datasets Used for Practice:**

  * **Dataset 1:** 12-target visual stimuli, 8 occipital channels (BioSemi ActiveTwo), 256 Hz sampling.
  * **Dataset 2:** BETA database, 64 channels, 250 Hz sampling, 40 characters flickering 5.8–8 Hz.
  * **Dataset 3:** MAMEM SSVEP dataset, 14 wireless channels (Emotiv Epoc), 128 Hz sampling, 5 simultaneous flicker frequencies.

---


# **Workshop 3 – Hands-on EEG Data Recording & Analysis (SSVEP Task)**

**Speakers:** Dr. Mohamed Zaky, Eng. Mai Gamal
**Focus:** Practical EEG recording, preprocessing, ERP & SSVEP analysis

---

## **Day 1–2 Recap: EEG Recording & Preprocessing**

* **EEG Setup:** g.tec Unicorn Hybrid Black, 8 dry electrodes, wireless via Bluetooth
* **Electrode Placement:** 10–20 system, impedance checked, proper scalp contact
* **Data Acquisition:** Record SSVEP responses while focusing on visual stimuli
* **EEGLAB/MATLAB Preprocessing Steps:**

  1. Load raw EEG + event markers
  2. Filtering: high-pass (~0.5 Hz), notch (50 Hz)
  3. Re-reference
  4. Artifact removal: ASR + ICA

---

## **Day 3 – Practical EEG Analysis**

### **1. Epoch Extraction & Baseline Correction** *(Day three starting workshops)*

* Tools > Extract epochs → select events **“square” & “RT”**
* Tools > Remove epoch baseline → detect relative changes vs baseline

### **2. Visualization – Subject Level**

* Plot > Channel data (scroll) → inspect each channel
* Reject bad epochs → manually or using ERPLAB
* Plot > Channel ERPs > With scalp maps → averaged ERPs + scalp distribution
* Plot > Channel ERPs > In scalp/rect array → visualize single channel trace
* Plot > ERP map series > In 2-D → scalp maps at specified latencies

### **3. Group-level ERP Analysis**

* Import BIDS dataset → File > BIDS tools > Import BIDS folder to STUDY
* Edit data → remove non-EEG channels + re-reference
* Denoise → Tools > Clean Rawdata + ASR → interpolate → re-reference
* ICA → Tools > Decompose data → classify (ICLABEL) → remove artifacts
* Epoching & baseline correction → Tools > Extract epochs → Remove epoch baseline
* Study design → Study > Select/Edit study design(s) → New (Independent variable)
* Precompute channel measures → Study > Precompute channel measures
* Visualization → Study > Plot channel measures (per channel or all channels)

### **4. SSVEP Feature Extraction & Analysis**

* **Feature Extraction:** Fourier Transform → power or correlation at stimulus frequencies
* **Classification:** Choose classifier (LDA / SVM) → discriminate stimulus frequencies
* **Model Training & Evaluation:** Train classifier → evaluate on test set
* **Advanced Techniques:** ICA → separate SSVEP components; Deep Learning → feature extraction & classification

---

**Outcome:** Hands-on experience in EEG recording, preprocessing, epoch extraction, baseline correction, ERP/SSVEP analysis, group-level statistical visualization, and feature extraction for BCI applications

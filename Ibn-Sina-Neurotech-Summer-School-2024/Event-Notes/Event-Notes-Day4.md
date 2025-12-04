# 📝 Event Notes– Day 4

## **Day 4 – Wednesday, 11 September 2024**

**Machine Learning for EEG in BCIs and Healthcare**

---

### **Session 4: Machine Learning in BCIs and Healthcare — Dr. Mohamed Abdelhack**

**Key Takeaways:**

* EEG → preprocessed → feature extraction → classifier → BCI output.

* Applications of ML in BCIs:

  * SSVEP-based spellers
  * Motor imagery BCIs
  * Neurological disorder detection

* **Importance:** Careful preprocessing and feature selection are critical for accurate classification.

* Emphasis on understanding **SSVEP response characteristics** and how ML can interpret them for BCIs.

---

### **Tutorial 4: Post-processing Analysis of EEG with Machine Learning — Dr. Nour El-Madany**

**Step-by-Step Workflow:**

#### **1. Sampling & Filtering**

* Converts continuous EEG signals to discrete-time by sampling at defined intervals.
* Band-pass filtering (6–80 Hz) removes unwanted frequency components.
* Goal: reduce noise and retain relevant neural oscillations.

#### **2. Epoch Segmentation**

* EEG divided into **short epochs** (time windows) per trial.
* Allows computation of features for each epoch.

#### **3. Feature Extraction**

* **Power Spectrum Density (PSD):** energy at different frequencies (key for SSVEP).
* **Time-domain features:** amplitude, latency of ERP components.
* **Frequency-domain features:** band-power, dominant frequencies.

#### **4. Machine Learning Classification**

* ML models classify EEG epochs using extracted features.
* Example: **Canonical Correlation Analysis (CCA)** compares EEG with reference stimuli to identify the attended frequency.
* Other possible models: LDA, SVM, deep learning.
* Purpose: predict user intent or detect brain states.

#### **5. Evaluation**

* Compare predicted labels with **ground truth**.
* Metrics: classification accuracy, confusion matrices.

---

### **Workshop 4: Post-processing Analysis — Dr. Mohamed Zaky & Eng. Mai Gamal**

**Focus:** Analysis of **pre-recorded SSVEP dataset**, post-processing and ML classification.

#### **1. Dataset Setup**

* 12 SSVEP stimulus classes
* 8 EEG channels
* 15 trials per stimulus

#### **2. Preprocessing**

* Band-pass filtering (6–80 Hz)
* Artifact removal (ICA or ASR)
* Epoch segmentation (4-second windows)

#### **3. Frequency-Domain Analysis**

* Compute magnitude spectrum per epoch using **FFT**
* Inspect key channels (e.g., Oz) for stimulus frequency peaks
* Identify clear vs noisy SSVEP responses

#### **4. Feature Extraction & Classification**

* **CCA Workflow:**

  1. Generate sine/cosine templates for each stimulus frequency and harmonics
  2. Compute correlation between EEG epochs and templates
  3. Assign stimulus label with highest correlation

* Complete ML pipeline:

  1. Load EEG epochs
  2. Apply preprocessing & filtering
  3. Generate reference templates
  4. Apply CCA classification
  5. Evaluate accuracy per subject

#### **5. Results**

* Accuracy varied across subjects:

  * Low (~26–30%)
  * High (~91%)
* **Average accuracy:** 60%
* Highlights **inter-subject variability** and the importance of preprocessing.

#### **6. Key Takeaways**

* Focused on **post-processing EEG data** and ML-based classification for SSVEP BCIs.
* Hands-on experience covered the full pipeline:
  **Filtering → Epoching → Feature Extraction → CCA Classification → Evaluation**
* Emphasis on practical application using **real pre-recorded datasets**.

---

**Outcome:** By the end of the day, participants gained practical skills in **SSVEP data analysis, feature extraction, ML classification**, and evaluation of EEG-based BCIs, 

# 📝 Event Notes – Day 2

## **Day 2 – Monday, 9 September 2024**

**Principles of Electrophysiology and EEG-Based BCIs**

---

### **Session 2: Principles of Electrophysiology and EEG-Based BCIs — Dr. Mahmoud Hassan**

**Key Takeaways:**

* **Global Brain Projects:**

  * Human Brain Project (HBP): [link](https://www.humanbrainproject.eu/en/)
  * The Brain Initiative
* **Neuroimaging Techniques Overview:**

  * Structural MRI, Functional MRI (fMRI)
  * Trade-offs: time resolution, spatial resolution, price, portability, usability
  * EEG: non-invasive, inexpensive, easy to use, excellent temporal resolution
* **History of EEG:**

  * First EEG in animals: Richard Caton (1874–1877)
  * Pioneers: Caton, Adolf Beck, Fleischl von Marxow, Danilevsky, Neminski, Hans Berger
  * First human EEG: Hans Berger (1924–1929), measured brain activity using silver wires under scalp
* **Physiological Origins of EEG:**

  1. Neurons communicate via action potentials
  2. Postsynaptic potentials (EPSP/IPSP) are main contributors to EEG
  3. Pyramidal neurons in cortex: radial orientation, synchronized firing, long-duration potentials
  4. Synchronization of neuronal activity is required for detectable EEG signals
* **EEG Signal Sources:**

  * Gray matter: neuron cell bodies
  * White matter: myelinated axons
* **Biophysical Properties:**

  * EEG amplitudes: 1–100 µV
  * Signal types: action potential, local field potential, EEG
* **EEG Processing & Analysis:**

  * Electrode types: gel, sponge, dry
  * Electrode layout: 10–20 system, high-density EEG up to 256 channels
  * Experimental paradigms: resting state, task-based
* **Preprocessing & Artefacts:**

  * Physiological artefacts: EOG (eye), EMG (muscle), ECG (heartbeat), respiration, tongue movement
  * Extra-physiological artefacts: power-line noise (50/60 Hz), electromagnetic interference, lead movements, high impedance
  * Filters: high-pass (~0.3 Hz), notch (50 Hz)
  * ICA and ASR for denoising
* **EEG Features & Analysis:**

  * Time domain, frequency domain
  * Source connectivity from HD-EEG
* **BCI Pipeline Example (P300 Speller):**

  * Acquisition → Preprocessing → Feature extraction → Channel selection → Classification → Application
* **Key Challenges:**

  * Signal quality, real-time processing, ethical/privacy concerns, non-stationarity, user variability, training time
* **Applications of EEG:**

  * Normal brain function, information processing, resting vs task
  * Brain disorder research, diagnosis refinement, treatment monitoring, brain stimulation
  * Classification, regression, clustering, normative modeling

---

### **Tutorial 2: Introduction to EEG Signal Processing — Dr. Mohamed Zaky**

**Key Takeaways:**

* **EEG Preprocessing Goals:** Enhance SNR by removing noise/artifacts (sweat, movement, ECG, EMG, power-line)
* **Manual vs Automatic Cleaning:** Manual inspection reliable but time-consuming; automatic algorithms (ICA, ASR) needed for large datasets
* **Open-Source Software:**

  * **EEGLAB** (MATLAB): GUI-based, extensive features, active community, MATLAB license required
  * **FieldTrip** (MATLAB): Flexible, strong time-frequency & source localization
  * **MNE** (Python): Integrated with Python ecosystem, advanced features, requires programming
* **EEG Pipeline Steps:**

  1. Import raw EEG data, channel locations, and event markers
  2. Temporal filtering (high-pass, notch)
  3. Re-referencing and optional down-sampling
  4. Interpolate bad channels
  5. Reject large artefacts (manual or ASR)
  6. Run ICA, identify and remove noisy components (eye blinks, muscle)
  7. Inspect & visualize data at each step
* **Common EEG Artefacts:**

  * Eye blinks/movements (frontal & lateral channels, delta-theta)
  * Muscle activity (20–300 Hz)
  * Pulse & body movements
  * Sweating (slow voltage drifts)
  * Loose electrode contact
  * Line noise (50/60 Hz)
* **Automated ICA Classification Tools:**

  * MARA, IC_MARC, ICLabel
* **EEGLAB Practical Workflow:**

  * Add to MATLAB path, open GUI, import dataset
  * Import channel locations & event markers
  * Re-reference and filter
  * Identify and reject bad channels & artefacts
  * Run ICA → manually or automatically label bad ICs → remove bad ICs
  * Validate results visually after each step

---

### **Workshop 2: Hands-on EEG Data Recording (SSVEP task) — Dr. Mohamed Zaky, Eng. Mai Gamal**

**Key Takeaways (Practical Focus):**

* **EEG Recording Setup:** Used the same device as Day 1 (g.tec Unicorn Hybrid Black) with 8 dry electrodes, wireless EEG recording via Bluetooth.
* **Electrode Preparation & Placement:** Applied the 10–20 system, ensured good scalp contact, and checked impedance for each electrode to guarantee signal quality.
* **Data Acquisition:** Recorded SSVEP responses during flickering stimuli on the screen, monitored participant attention and engagement.
* **EEG Preprocessing Practical Steps (EEGLAB/MATLAB):**

  1. **Import Data:** Loaded raw EEG data, electrode locations, and event markers into EEGLAB.
  2. **Filtering:** Applied high-pass filter (~0.5 Hz) and notch filter (50 Hz) to remove noise and power-line interference.
  3. **Re-referencing & Down-sampling:** Adjusted reference to reject common-mode signals and down-sampled for computational efficiency.
  4. **Bad Channel Handling:** Visually inspected channels, removed or interpolated bad electrodes using neighboring channels.
  5. **Artifact Removal:** Applied **ASR** (Artifact Subspace Reconstruction) for large non-stationary artifacts, followed by **ICA** to identify and remove eye blinks, muscle activity, and other common artifacts.
  6. **Visualization:** Checked the quality at each step using channel plots and spectral maps to confirm preprocessing effectiveness.
* **Outcome:** Participants practically applied a full EEG pipeline—from data recording, preprocessing, to artifact removal—using EEGLAB, gaining hands-on experience in real-world EEG signal handling.

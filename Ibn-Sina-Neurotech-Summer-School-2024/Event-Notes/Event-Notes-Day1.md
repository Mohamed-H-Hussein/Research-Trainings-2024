# 📝 Event Notes – Day 1

## **Day 1 – Sunday, 8 September 2024**

**Introduction to Neurotechnology and Brain-Computer Interfaces (BCIs)**

---

### **Session 1: Introduction to Neurotechnology and BCIs — Dr. Seif Eldawlalty**

**Key Takeaways:**

* **Neurotechnology Overview:** Engineering tech to monitor or modulate the nervous system. Interfaces can be invasive (single/multiple sites) or non-invasive (EEG, fMRI).
* **Neuron Basics:** Brain has ~100B neurons; each with ~7000 synapses. Neural signals are binary (action potential or none) with EPSP/IPSP influencing postsynaptic neuron firing.
* **Recorded Signals & Applications:**

  * BCIs for communication and control
  * Neurodegenerative disease monitoring (e.g., ALS)
  * Visual prostheses
* **BCI Types & Examples:**

  * **P300-based:** Detects rare stimuli, used in spellers, wheelchairs, robotic arms
  * **SSVEP-based:** Detects brain response to flickering stimuli; applications in spellers, AR integration
  * **Motor Imagery (MI):** Uses C3/C4 electrodes for imagined movements, controlling robotic arms or wheelchairs
* **Generative AI Integration:** GANs can reduce calibration time for P300- and MI-based BCIs
* **Industrial Applications:** Nissan (brain-to-vehicle), Facebook CTRL Labs, Samsung TV control, Neuralink
* **Challenges:** Early diagnosis of ALS, EEG accessibility for African hair types, user engagement, visual fatigue

---

### **Tutorial 1: EEG Data Collection and Experimental Design — Dr. Mohamed Zaky**

**Key Takeaways:**

* **BCI System Components:** Signal acquisition → preprocessing → feature extraction → classification → application → biofeedback
* **EEG Basics:**

  * Non-invasive; high temporal resolution, low spatial precision
  * Signals amplified and filtered before visualization
  * 10–20 system for electrode placement; supports 32–512 electrodes
* **Signal Acquisition & Electrode Types:**

  * Dry and wet electrodes, gel or pre-gelled, caps for hygiene and practicality
  * Correct electrode-scalp contact is crucial for accurate signals
* **BCI Approaches:**

  * Active vs Natural Intent, Operant Conditioning vs Pattern Recognition
  * Synchronous vs Asynchronous, Offline vs Online, Non-invasive vs Invasive
* **BCI Paradigms:**

  * **Selective attention:** P300, SSVEP
  * **Spontaneous signal:** SMR, MI, SCP, mental tasks
* **EEG-based Signals:**

  * P300: Positive deflection ~300ms after stimulus
  * SSVEP: Brain response at stimulus flicker frequency
  * MI: ERD/ERS patterns during imagined/real movement
* **Experiment Design Notes:**

  * Controlled baseline vs task conditions
  * Behavioral task engagement is key
  * Pre-tests and pilot tests are essential
* **BCI Illiteracy:** Causes include individual brain differences, system limitations, insufficient training, and psychological factors

---

### **Workshop 1: Hands-on EEG Data Recording (SSVEP task) — Dr. Mohamed Zaky, Eng. Mai Gamal**

**Key Takeaways:**

* **Hardware Used:** g.tec Unicorn Hybrid Black, 8 dry electrodes (Fz, C3, Cz, C4, Pz, PO7, Oz, PO8), wireless EEG recording via Bluetooth
* **Signal Processing:** Amplification, filtering, digitalization, extraction of SSVEP components
* **SSVEP Paradigm:**

  * Flickering stimuli at multiple frequencies on FHD screen (240 Hz refresh)
  * Gray-scale flicker, green background, blue cue color
* **Software:** Customizable scripts for band-pass filtering and SSVEP extraction, GitHub repo for reference
* **BCI Approaches Supported:** P300, MI, SSVEP, code-based VEP
* **Practical Tips:**

  * Electrode placement and impedance checking critical
  * Monitor participant attention and fatigue
  * Ensure correct reference and ground electrode fixation

---

**Summary of Notes for Day 1:**

1. **Understand neurotechnology foundations** (neurons, signals, interfaces, applications).
2. **Know EEG-based BCI paradigms** (P300, SSVEP, MI) and how they relate to selective attention or spontaneous signals.
3. **Familiarize with hardware/software** (Unicorn Hybrid Black, OpenBCI, electrode types, signal acquisition).
4. **Experiment design skills:** Pre-tests, pilot tests, trial/run/epoch/event definitions, participant criteria.
5. **Practical lab skills:** Electrode placement, EEG signal acquisition, handling SSVEP tasks, monitoring attention/fatigue.
6. **Applications awareness:** Clinical (ALS, vision restoration), industrial (robotic arm, wheelchair, automotive), AI integration for calibration.


# 💻 Research Trainings 2024 Repository
 
This repository **contains my personal notes, analysis reports, project materials, and summaries**from three research major training events in 2024. It highlights **hands-on experience in multi-omics bioinformatics for neuro-oncology, neurotechnology, and biodiversity genomics**, developed alongside my M.Sc. in Biochemistry and Molecular Biology.

---

## 🎓 Trainings Included

| Training/Event                            | Institution / Organizer                                            | Dates               | Folder Link                                       |
| ----------------------------------------- | ------------------------------------------------------------------ | ------------------- | ------------------------------------------------- |
| **BioHack I Hackathon 2024**              | German International University (GIU), Cairo, Egypt                | June 2024     | [Folder](./BioHack-I-Hackathon-2024)              |
| **Ibn Sina Neurotech Summer School 2024** | The American University in Cairo, School of Sciences & Engineering | September 2024 | [Folder](./Ibn-Sina-Neurotech-Summer-School-2024) |
| **African BioGenome Project 2024**        | Mohammed V University & Nile University, North Africa              | November 2024 | [Folder](./African-Biogenome-Training-2024)       |

---

## 🗂️ Repository Structure

```

Research-Trainings-2024/
│
├── README.md                                 # Main repository README: overview of all trainings, projects, and skills gained
│
├── BioHack-I-Hackathon-2024/                  
│   ├── README.md                             # Overview of the hackathon, challenges, objectives, and key skills acquired
│   ├── Event-Notes.md                        # Detailed session notes, highlights from lectures, mentorship, and workshops
│   └── Challenge/                            # Contains files related to the main hackathon challenge
│       ├── Challenge12_Analysis_Report.md   # Multi-omics integration analysis report (RNA-seq, ChIP-seq, networks, biomarkers)
│       └── Challenge12_Project.pdf          # Final presentation summarizing methods, results, and conclusions
│
├── Ibn-Sina-Neurotech-Summer-School-2024/   
│   ├── README.md                             # Overview of the summer school, project description, and skills gained
│   ├── Event-Notes/                          # Day-wise detailed session notes
│   │     ├── README.md                       # Summary of all event notes
│   │     ├── Event-Notes-Day1.md             # Day 1: Introduction to neurotechnology, EEG basics, SSVEP, P300
│   │     ├── Event-Notes-Day2.md             # Day 2: EEG preprocessing, ICA, artifact removal
│   │     ├── Event-Notes-Day3.md             # Day 3: Feature extraction, ERP & SSVEP analysis
│   │     ├── Event-Notes-Day4.md             # Day 4: Machine learning (CCA, SVM) on EEG data
│   │     └── Event-Notes-Day5.md             # Day 5: Ethics, future directions, project presentations
│   └── Project/                              # EEG analysis project folder with reproducible workflow
│         ├── SSVEP-CCA-Analysis-Report.md   # Main EEG project report: preprocessing, CCA analysis, results
│         ├── presentation/                   # Folder containing project presentation slides
│         │     └── SSVEP-CCA-Project-Presentation.pdf
│         ├── scripts/                        # Analysis scripts and notebooks
│         │     └── SSVEP_CCA_Analysis_Project_Notebook.ipynb
│         ├── results/                        # Final analysis results in tabular form
│         │     └── cca_ssvep_results.xls
│         ├── figures/                        # Visualizations supporting analysis and results
│         │     ├── accuracy_boxplot.png                 # Accuracy comparison across subjects
│         │     ├── accuracy_per_subject.png             # Accuracy per individual subject
│         │     ├── confusion_matrix_last_subject.png    # Confusion matrix for last subject
│         │     ├── max_cca_corr_hist_last_subject.png   # Histogram of max CCA correlation values
│         │     ├── sample_eeg_signal.png                # Example EEG signal from dataset
│         │     └── true_vs_predicted_labels.png         # Plot comparing true vs predicted labels
│         └── data/                          # EEG data for all subjects (MATLAB .mat files)
│               ├── s1.mat
│               ├── s2.mat
│               ├── s3.mat
│               ├── s4.mat
│               ├── s5.mat
│               ├── s6.mat
│               ├── s7.mat
│               ├── s8.mat
│               ├── s9.mat
│               └── s10.mat
│
└── African-BioGenome-Training-2024/         
    ├── README.md                             # Overview of the workshop, key insights, and skills acquired
    └── Event-Notes/                          # Detailed session notes from both online and onsite sessions
          ├── MohammedV-University-Workshop-EventNotes.md  # Notes from online sessions at Mohammed V University, Rabat, Morocco
          └── Nile-University-Workshop-EventNotes.md       # Notes from onsite sessions at Nile University, Giza, Egypt


```

---

## 📂 Folder Descriptions

### **BioHack-I-Hackathon-2024**

Contains **notes, multi-omics analysis reports, and project presentation** from the BioHack I Hackathon.

* **README.md** — Overview of the hackathon, challenge topic, objectives, and skills acquired.
* **Event-Notes.md** — Detailed session notes, including key lectures, workshops, mentorship sessions, and hackathon activities.
* **Challenge/** — Contains the multi-omics challenge work:

  * `Challenge12_Analysis_Report.md` — Complete analysis report integrating RNA-seq and ChIP-seq datasets.
  * `Challenge12_Project.pdf` — Presentation summarizing methodology, results, and conclusions.

---

### **Ibn-Sina-Neurotech-Summer-School-2024**

Contains **notes, project materials, and EEG analysis reports** from the summer school.

* **README.md** — Overview of the summer school, hands-on project, and skills acquired.
* **Event-Notes/** — Notes from each day:

  * `Event-Notes-Day1.md` to `Event-Notes-Day5.md` — Day-wise summaries covering lectures, workshops, and tutorials.
* **Project/** — EEG-based BCI project:

  * `SSVEP-CCA-Analysis-Report.md` — Main project report with analysis of EEG data.
  * `presentation/` — PDF slides summarizing the project.
  * `scripts/` — Jupyter Notebook containing preprocessing, feature extraction, and analysis code.
  * `results/` — Excel files or other outputs generated from the project.
  * `figures/` — Plots and visualizations supporting the analysis.
  * `data/` — Raw EEG datasets for all subjects in `.mat` format.

---

### **African-BioGenome-Training-2024**

Contains **personal notes and summaries** from the African BioGenome Project North Africa Workshop.

* **README.md** — Overview of the workshop, hybrid format, key concepts, and relevance to research.
* **Event-Notes/** — Detailed session notes:

  * `MohammedV-University-Workshop-EventNotes.md` — Notes from online sessions at Mohammed V University, Rabat.
  * `Nile-University-Workshop-EventNotes.md` — Notes from onsite sessions at Nile University, Cairo.

This folder documents **hands-on genomics training, bioinformatics workflows, biodiversity applications, and computational tools**, with clear educational and research relevance.

---

## 🧠 Why These Trainings?

These trainings were selected to:

* Gain hands-on experience in **multi-omics analysis, EEG-based neurotechnology, and genomics**
* Apply computational methods to **biological and biomedical datasets**
* Integrate theoretical knowledge with **practical project workflows**
* Enhance skills in **data analysis, visualization, and scientific reporting**
* Build a strong foundation for **future Neuro-Oncology/Bioinformatics projects**

---

## 🎯 Relevance to My Field

As an **M.Sc. candidate in Biochemistry & Molecular Biology**, specializing in **Molecular Cancer Biology and Bioinformatics**, these trainings provided experience in:

* Multi-omics data integration and analysis
* EEG signal processing and machine learning for BCI applications
* Genomic workflows in biodiversity and bioinformatics pipelines
* Scientific documentation, reproducible workflows, and collaborative research
* Skills transferable to **cancer biomarker discovery, neuro-oncology research, and computational biology**

---

## 🛠️ Key Skills Developed

* **Bioinformatics & Multi-Omics:** RNA-seq, ChIP-seq, peak annotation, functional enrichment, GRN construction
* **Neurotechnology & EEG Analysis:** Signal preprocessing, feature extraction, machine learning (CCA), visualization
* **Genomics & Biodiversity:** Sequencing workflows, OTU analysis, taxonomic classification, bioinformatics pipelines
* **Programming & Data Analysis:** R programming, Python/Jupyter, MATLAB for EEG data, reproducible workflows
* **Scientific Reporting & Presentation:** Clear documentation, structured project reports, project presentations
* **Collaboration & Mentorship:** Working in teams, applying feedback, and communicating scientific findings

---

## ✍️ Author & Contribution

**Mohamed H. Hussein — MSc Candidate, Biochemistry & Molecular Biology, Ain Shams University**

* Actively participated in all three research trainings, attending lectures, workshops, and practical sessions.
* Independently compiled detailed **event notes, project reports, and analysis workflows**.
* Executed **multi-omics analyses, EEG-based project workflows, and bioinformatics pipelines**.
* Organized all materials into **well-structured GitHub folders** to ensure clarity and reproducibility.

---

## 📝 Citation & Usage

This repository contains **summaries, notes, and projects** and is part of the **Research Trainings 2024** documentation.

**Citation:**
Hussein, Mohamed H. (2025). *Research Training 2024* [ Summary, Notes,and Project]. GitHub repository: [https://github.com/Mohamed-H-Hussein/Research-Trainings-2024](https://github.com/Mohamed-H-Hussein/Research-Trainings-2024)

**Usage:**
Materials are for **educational and non-commercial use**, with proper citation. Training-provided materials remain under the copyright of original organizers.


---

## 📜 License

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This repository is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).
Full license: [https://creativecommons.org/licenses/by-nc/4.0/legalcode](https://creativecommons.org/licenses/by-nc/4.0/legalcode)

---

© 2025 Mohamed H. Hussein

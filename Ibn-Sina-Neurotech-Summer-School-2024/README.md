# 💻 Ibn Sina Neurotech Summer School: Decoding Your Mind with BCI Technology

This folder contains **personal notes, summaries, and project materials** from the **Ibn Sina Neurotech Summer School 2024**, focusing on **EEG-based Brain-Computer Interfaces (BCIs)**, signal processing, and machine learning applications in healthcare and neuroscience. The training involved hands-on sessions, tutorials, workshops and a mini-project carried out to gain practical experience in **neurotechnology research**.

---

## 🏫 Event Information

* **Institution:** The American University in Cairo, School of Sciences and Engineering
* **Dates:** 8–12 September 2024
* **Support:** International Brain Research Organization (IBRO)
* **Organizers:** Arabs in Neuroscience
* **Event Format:** On-site Summer School
* **Event Link:**[Ibn Sina Neurotech Summer School](https://arabsinneuro.org/school/isn/summer-2024/)
* **Main Speakers:**

| Speaker                         | Affiliation                                                        |
| ------------------------------- | ------------------------------------------------------------------ |
| Prof. Dr. Seif Eldawlalty       | The American University in Cairo, Egypt                            |
| Dr. Mohamed Zaky                | Arab Academy for Science, Technology and Maritime Transport, Egypt |
| Eng. Mai Gamal                  | German University in Cairo, Egypt                                  |
| Prof. Dr. Mahmoud Hassan        | Reykjavik University, Iceland                                      |
| Prof. Dr. Abdelkader Nasreddine | United Arab Emirates University, UAE                               |
| Dr. Mohamed Abdelhack           | The Centre for Addiction and Mental Health (CAMH), Canada          |
| Dr. Nour El-Madany              | The American University in Cairo, Egypt                            |
| Dr. Slobodan Tanackovic         | g.tec medical engineering GmbH, Austria                            |

---

## 📘 Overview

The **Ibn Sina Neurotech Summer School** introduced participants to **neurotechnology, EEG-based BCIs, signal processing techniques, and machine learning applications in healthcare**. The program combined theoretical sessions with **hands-on workshops**, providing participants with:

* Hands-on EEG recording and **BCI experimental design**
* **Signal processing** and **feature extraction**
* **Machine learning** applications for EEG classification
* Exposure to **ethical considerations** and neurotechnology innovation
* Participation in **mini-projects** with practical datasets

> Detailed session notes are available in the [Event-Notes folder](./Event-Notes).

---

## 📂 Folder Structure

```
Ibn-Sina-Neurotech-Summer-School-2024/
│
├── README.md                          # Overview of the event and project
├── Event-Notes/                       
│     ├── README.md                     # Summary of event notes
│     ├── Event-Notes-Day1.md           # Notes from Day 1
│     ├── Event-Notes-Day2.md           # Notes from Day 2
│     ├── Event-Notes-Day3.md           # Notes from Day 3
│     ├── Event-Notes-Day4.md           # Notes from Day 4
│     └── Event-Notes-Day5.md           # Notes from Day 5
└── Project/
      ├── SSVEP-CCA-Analysis-Report.md       # Main report
      ├── presentation/
      │     └── SSVEP-CCA-Project-Presentation.pdf   # Final slides summarizing project
      ├── scripts/
      │     └── SSVEP_CCA_Analysis_Project_Notebook.ipynb  # Jupyter Notebook with analysis code
      ├── results/
      │     └── cca_ssvep_results.xls       # Excel sheet with final results
      ├── figures/
      │     ├── .gitkeep
      │     ├── accuracy_boxplot.png         # Accuracy comparison across subjects
      │     ├── accuracy_per_subject.png    # Accuracy per individual subject
      │     ├── confusion_matrix_last_subject.png  # Confusion matrix for last subject
      │     ├── max_cca_corr_hist_last_subject.png # Histogram of max CCA correlation
      │     ├── sample_eeg_signal.png       # Example EEG signal from dataset
      │     └── true_vs_predicted_labels.png # True vs predicted labels plot
      └── data/
            ├── s1.mat                      # EEG data for Subject 1 — MATLAB .mat file
            ├── s2.mat                      # EEG data for Subject 2 — MATLAB .mat file
            ├── s3.mat                      # EEG data for Subject 3 — MATLAB .mat file
            ├── s4.mat                      # EEG data for Subject 4 — MATLAB .mat file
            ├── s5.mat                      # EEG data for Subject 5 — MATLAB .mat file
            ├── s6.mat                      # EEG data for Subject 6 — MATLAB .mat file
            ├── s7.mat                      # EEG data for Subject 7 — MATLAB .mat file
            ├── s8.mat                      # EEG data for Subject 8 — MATLAB .mat file
            ├── s9.mat                      # EEG data for Subject 9 — MATLAB .mat file
            └── s10.mat                     # EEG data for Subject 10 — MATLAB .mat file

```


## 📂 Folder Descriptions
## 📂 Folder & File Descriptions

| Folder / File        | Content Description                                      | Link                                       |
| -------------------- | -------------------------------------------------------- | ------------------------------------------ |
| **README.md**        | Overview of the Summer School, project, and skills      | [README.md](./README.md)                   |
| **Event-Notes/**     | Session notes, tutorials, workshops                      | [Event-Notes](./Event-Notes)               |
| ├── Event-Notes-Day1.md | Intro to neurotechnology, EEG basics, SSVEP, P300     | [Day1](./Event-Notes/Event-Notes-Day1.md) |
| ├── Event-Notes-Day2.md | EEG preprocessing, ICA, artifact removal              | [Day2](./Event-Notes/Event-Notes-Day2.md) |
| ├── Event-Notes-Day3.md | Feature extraction, ERP & SSVEP analysis              | [Day3](./Event-Notes/Event-Notes-Day3.md) |
| ├── Event-Notes-Day4.md | Machine learning for EEG, CCA, SVM                    | [Day4](./Event-Notes/Event-Notes-Day4.md) |
| └── Event-Notes-Day5.md | Future directions, ethics, project presentations      | [Day5](./Event-Notes/Event-Notes-Day5.md) |
| **Project/**         | EEG analysis project resources                           | [Project](./Project)                       |
| ├── SSVEP-CCA-Analysis-Report.md  | Main project report | [Report](./Project/SSVEP-CCA-Analysis-Report.md) |
| ├── presentation/  | Project presentation slides                              | [Presentation](./Project/presentation/SSVEP-CCA-Project-Presentation.pdf) |
| ├── scripts/       | Jupyter Notebook with EEG preprocessing & CCA analysis  | [Notebook](./Project/scripts/SSVEP_CCA_Analysis_Project_Notebook.ipynb) |
| ├── results/       | Final analysis results                                   | [Results](./Project/results/cca_ssvep_results.xls) |
| ├── figures/       | Graphs & visualizations supporting analysis             | [Figures](./Project/figures)               |
| │   ├── accuracy_boxplot.png           | Accuracy comparison across subjects                 | [Link](./Project/figures/accuracy_boxplot.png) |
| │   ├── accuracy_per_subject.png       | Accuracy per individual subject                     | [Link](./Project/figures/accuracy_per_subject.png) |
| │   ├── confusion_matrix_last_subject.png | Confusion matrix for last subject                 | [Link](./Project/figures/confusion_matrix_last_subject.png) |
| │   ├── max_cca_corr_hist_last_subject.png | Histogram of max CCA correlation                  | [Link](./Project/figures/max_cca_corr_hist_last_subject.png) |
| │   ├── sample_eeg_signal.png          | Example EEG signal from dataset                     | [Link](./Project/figures/sample_eeg_signal.png) |
| │   └── true_vs_predicted_labels.png   | True vs predicted labels plot                        | [Link](./Project/figures/true_vs_predicted_labels.png) |
| └── data/          | EEG data files for all subjects — MATLAB .mat files     | [Data](./Project/data)                       |
|     ├── s1.mat       | EEG data for Subject 1 — MATLAB .mat file               | [s1](./Project/data/s1.mat)                 |
|     ├── s2.mat       | EEG data for Subject 2 — MATLAB .mat file               | [s2](./Project/data/s2.mat)                 |
|     ├── s3.mat       | EEG data for Subject 3 — MATLAB .mat file               | [s3](./Project/data/s3.mat)                 |
|     ├── s4.mat       | EEG data for Subject 4 — MATLAB .mat file               | [s4](./Project/data/s4.mat)                 |
|     ├── s5.mat       | EEG data for Subject 5 — MATLAB .mat file               | [s5](./Project/data/s5.mat)                 |
|     ├── s6.mat       | EEG data for Subject 6 — MATLAB .mat file               | [s6](./Project/data/s6.mat)                 |
|     ├── s7.mat       | EEG data for Subject 7 — MATLAB .mat file               | [s7](./Project/data/s7.mat)                 |
|     ├── s8.mat       | EEG data for Subject 8 — MATLAB .mat file               | [s8](./Project/data/s8.mat)                 |
|     ├── s9.mat       | EEG data for Subject 9 — MATLAB .mat file               | [s9](./Project/data/s9.mat)                 |
|     └── s10.mat      | EEG data for Subject 10 — MATLAB .mat file              | [s10](./Project/data/s10.mat)               |



---

## 🎯 Relevance to My Field

As an MSc candidate in **Biochemistry & Molecular Biology**, specializing in **Molecular Cancer Biology**, this summer school offered **hands-on experience in neurotechnology and EEG-based brain research**, enhancing my ability to integrate computational and experimental approaches. Key outcomes include:

* Practical **EEG data collection, preprocessing, and analysis**.
* Deepened understanding of **signal processing and feature extraction** techniques.
* Application of **machine learning models** to biomedical datasets.
* Experience in **project-based teamwork, documentation, and scientific reporting**.
* Awareness of **ethical considerations** in human-subject neurotechnology research.

This training significantly strengthened my **computational and experimental skills**, providing a bridge between molecular biology and **cutting-edge brain-computer interface technologies**, relevant for **neuroscience and neuro-oncology research**.

---

## 🛠️ Skills Acquired

* **EEG experimental design and data acquisition**
* **Signal preprocessing and artifact removal**(MATLAB with EEGLAB toolbox)
* **Feature extraction** (temporal, spectral, time-frequency domains)
* **Machine learning applied to EEG datasets** (CCA)
* **Jupyter Notebook workflow development** for reproducible research
* **Data visualization and analysis** for neurotechnology projects
* **Scientific project reporting and presentation**
* **Collaborative teamwork** in research projects


---

## ✍️ Author & Contribution

**Mohamed H. Hussein — MSc Candidate, Biochemistry & Molecular Biology, Ain Shams University**

* Participated in all summer school sessions, tutorials, and workshops on **neurotechnology** and **EEG-based research**.
* Performed **EEG data acquisition**, **signal preprocessing**, **feature extraction**, and **machine learning analysis** in the project lab.
* Co-developed the **project presentation** with a teammate, enhanced the initial **Jupyter Notebook** based on workshop materials, and jointly presented the results.
* Re-engineered **independently** the **entire Jupyter Notebook code** and substantially improved it to produce a **fully reproducible workflow**, including **enhanced processing steps**,**figures**, **clearer documentation**, and a **clean, structured analytical pipeline** suitable for public sharing and reuse.
* Prepared **independently** detailed **Event Notes** for all five sessions and developed the complete **Analysis Project Report**.
* Created **independently** the entire **GitHub folder**, including all **Jupyter Notebooks**, **presentation slides**, **Event Notes**, and the **project Analysis Report**, with a **well-organized folder structure** ensuring clarity and easy navigation.
* Gained hands-on experience integrating **molecular biology**, **computational analysis**, and **neurotechnology**, with strong relevance to **neuroscience** and **neuro-oncology** applications.

---

## 📝 Citation & Usage

This folder contains summary, notes, project materials, and the reproducible Jupyter Notebook, and is part of the **Research-Trainings-2024** repository.

**Citation:**
Hussein, Mohamed H. (2025). *Research Training 2024* [ Summary, Notes,and Project]. GitHub repository: [https://github.com/Mohamed-H-Hussein/Research-Trainings-2024](https://github.com/Mohamed-H-Hussein/Research-Trainings-2024)

**Usage:**
This folder serves as a **personal learning and skill-tracking resource** for:

* Reviewing EEG and neurotechnology concepts
* Practicing data analysis workflows learned during the summer school
* Supporting professional development and educational documentation
* Personal reference for ongoing and future neurotechnology projects

All materials authored by me are available for **educational and non-commercial use**, provided proper **citation is included**. Any reused or modified material should clearly acknowledge the original author. Summer School-provided materials remain under the **copyright and license of the original organizers**.

---

## 📜 License

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

This folder is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).
Full license: [https://creativecommons.org/licenses/by-nc/4.0/legalcode](https://creativecommons.org/licenses/by-nc/4.0/legalcode)

---

© 2025 Mohamed H. Hussein

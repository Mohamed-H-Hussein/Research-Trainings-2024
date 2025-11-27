# 🔬 Challenge 12 Analysis Report

## **Unraveling Epigenetic Signatures Associated with Prognostic Gene Expression Profiles in Glioblastoma**

**Supervised by:** Dr. Salma M. Abozeid – Postdoctoral Fellow & Lecturer of Bioinformatics, Faculty of Pharmacy & Biotechnology, German University in Cairo (GUC)

**Team:**

* **Maria Nasser** – Graduation Student, Faculty of Pharmacy & Biotechnology, German University in Cairo (GUC)
* **Mohamed Hossam (Mohamed H. Hussein)** – M.Sc. Candidate, Biochemistry and Molecular Biology, Ain Shams University, Cairo, Egypt

**Note:** This report was **prepared independently by Mohamed H. Hussein** after the BioHackathon to ensure reproducibility of analyses and suitability for **GitHub repository submission**.

---

## **1. Introduction**

Glioblastoma (GB) is among the most aggressive primary brain tumors, characterized by extensive cellular heterogeneity and poor clinical outcomes. Epigenetic modifications such as **DNA methylation** and **histone acetylation** play central roles in GB progression, transcriptional regulation, and therapeutic response.

Modern classification divides GB into molecular subtypes, including **IDH-mutant**, **RTK I**, **RTK II**, and **Mesenchymal (MES)**. Each subtype exhibits distinct epigenetic landscapes that influence gene expression programs and patient prognosis. This analysis investigates the **epigenetic landscape of GB**, focusing on **enhancers and super-enhancers (SEs)**, their associated **prognostic genes**, and **key transcription factors (TFs)** to identify subtype-specific regulatory mechanisms and potential therapeutic targets.

---

## **2. Objective of the Challenge**

The goal of this analysis was to systematically investigate:

1. Enhancers and super-enhancers (SEs) across GB subtypes
2. Their associated target genes and prognostic markers
3. Key transcription factors (TFs) driving subtype-specific regulatory circuits
4. Potential therapeutic targets linked to tumor aggressiveness and invasion

---

## **3. Data & Methods Overview**

A multi-step computational workflow was designed to integrate chromatin marks with genomic annotation and functional enrichment tools.

### **3.1 Tools and Pipelines Used**

| Category            | Tools                    | Purpose                                               |
| ------------------- | ------------------------ | ----------------------------------------------------- |
| Peak processing     | **BedTools**             | Overlap analysis of methylation and acetylation peaks |
| Peak annotation     | **ChIPseeker / GRanges** | Genomic feature annotation                            |
| Functional pathways | **ReactomePA**           | Biological pathway enrichment                         |
| Visual exploration  | **IGV**                  | Inspection of enhancer and super-enhancer regions     |
| SE-gene association | **GREAT**                | Linking regulatory regions to target genes            |
| Motif discovery     | **MEME Suite**           | Motif enrichment analysis                             |
| TF identification   | **JASPAR 2022**          | Predicting TF binding                                 |

---



## **4. Results Overview**

### **4.1 Enhancer Profiles Across Subtypes**

* Clear enhancer differences among IDH, RTK I/II, and MES.
* MES shows the highest enhancer activity.
* Functional enrichment linked to invasion, immune response, migration, and stemness.

### **4.2 Super-Enhancer Identification**

* **224 subtype-specific SEs** identified.
* Enrichment in **Rho GTPase signaling** and pathways linked to aggressiveness.

### **4.3 SE–Gene Associations**

* SEs located near key prognostic markers:

  * **IDH**
  * **CDKN2A**
  * **ATRX**
* Strong H3K27ac signals indicate active regulatory roles.

### **4.4 SE Linked to RHO Pathway**

* SE discovered **20 kb upstream of the RHO gene**.
* Rho GTPases (RhoA, Rac1, Cdc42) drive GB invasion and migration.

### **4.5 Motif & TF Analysis**

* Three enriched motifs identified in SE-Rho.
* Predicted TFs:

  * **RREB1, EGR1, KLF9, ZSCAN4, MSANTD3, NR5A1**
* Linked to tumor progression and cancer stemness.

---

## **5. Key Insights**

* Enhancer and SE signatures help classify GB subtypes.
* SE-Rho is a strong candidate driver of GB aggressiveness.
* SEs regulate key prognostic genes (IDH, ATRX, CDKN2A).
* Identified TFs may control invasion and progression programs.

---

## **6. Conclusion**

1. SEs are associated with major GB prognostic markers.
2. Rho GTPase signaling is consistently enriched across GB samples.
3. SE-Rho may contribute to GB progression.
4. TFs binding SE-Rho highlight a regulatory pathway worth investigating.
5. In vitro and in vivo studies are required for validation.
6. Targeting SE complexes represents a potential therapeutic strategy in GB.


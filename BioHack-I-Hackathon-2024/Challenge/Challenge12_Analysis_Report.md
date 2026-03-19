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

* SE regions were **associated with** key prognostic markers, including IDH, CDKN2A, and ATRX. Elevated H3K27ac signals are **consistent with active regulatory regions**, though functional validation is required.


### **4.4 SE Linked to RHO Pathway**

* A **putative super-enhancer** was identified approximately 20 kb upstream of the RHO gene, suggesting a potential role in pathways related to glioblastoma invasion and migration.

### **4.5 Motif & TF Analysis**

* Motif enrichment analysis identified three enriched motifs within SE regions. These motifs are **predicted to be recognized by TFs** including RREB1, EGR1, KLF9, ZSCAN4, MSANTD3, and NR5A1.

---

## **5. Key Insights**

* Enhancer and super-enhancer signatures are associated with GB subtype-specific epigenetic landscapes. 
* A putative SE near the RHO locus may be linked to pathways involved in GB invasion. 
* SE regions are associated with key prognostic genes, including IDH, ATRX, and CDKN2A. 
* Predicted TFs may contribute to transcriptional programs related to tumor progression. 

---

## **6. Conclusion**

1. Super-enhancers are associated with major GB prognostic markers.
2. Rho GTPase signaling is consistently enriched across GB samples.
3. A putative SE near RHO may contribute to GB-related pathways.
4. Predicted TFs highlight candidate regulatory mechanisms.
5. Experimental validation is required to confirm these findings.
6. These results provide a hypothesis-generating framework for future studies.


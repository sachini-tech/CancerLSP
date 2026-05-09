# Classification of Early and Late Stage Liver Hepatocellular Carcinoma Patients from their Genomics and Epigenomics Profiles

Welcome to the official repository for the study focused on classification of early and late stage Liver Hepatocellular Carcinoma (LIHC) using genomics and epigenomics data. The study utilizes RNA expression and DNA methylation profiles combined with machine learning approaches for cancer stage prediction.

Web Server: https://webs.iiitd.edu.in/raghava/cancerlsp/

---

## Citation

Kaur, H., Bhalla, S., & Raghava, G. P. S. (2019).  
**Classification of early and late stage liver hepatocellular carcinoma patients from their genomics and epigenomics profiles.**  
*PLOS ONE*, 14(9), e0221476.  
https://doi.org/10.1371/journal.pone.0221476

---

## About the Study

Liver Hepatocellular Carcinoma (LIHC) is one of the most common and deadly cancers worldwide. Early-stage diagnosis is critical for effective treatment and improved patient survival. This study presents computational models that classify:

- Early-stage vs Late-stage LIHC patients
- Cancerous vs Normal tissue samples
- Multi-class classification among normal, early-stage, and late-stage samples

The prediction models are based on:

- RNA transcript expression profiles
- DNA methylation CpG sites
- Hybrid genomics and epigenomics features

---

## Dataset Information

The study used TCGA-LIHC datasets containing:

### Samples

- 173 early-stage samples
- 177 late-stage samples
- 50 normal tissue samples

### Features

- 60,483 RNA transcripts
- 485,577 methylation CpG sites

Source: TCGA GDC Data Portal

---

## Methodology

### Data Processing

- RNA expression normalization using log2 transformation and z-score normalization
- Differential methylation analysis
- Differential expression analysis
## Key Findings

### Early vs Late Stage Classification

Hybrid models using:

- 21 CpG methylation sites
- 30 RNA transcripts

achieved:

- Accuracy: 78.87%
- AUC: 0.82

using Naïve Bayes classifier.

---

### Cancer vs Normal Classification

Models developed using:

- 5 RNA transcripts
- 5 CpG methylation sites

achieved:

- Accuracy: 96–98%
- AUC: 0.99

---

## Important Features Identified

### RNA Biomarkers

Examples include:

- NCAPH
- CYP4A22
- HSD17B6
- CLEC4G
- FCN2
- COLEC10

### CpG Methylation Biomarkers

Examples include:

- cg20457523
- cg07274716
- cg24035245

---

## Applications

- Liver cancer stage prediction
- Biomarker discovery
- Precision oncology
- Cancer genomics research
- Machine learning in healthcare

---

## Web Resource
Gajendra P. S. Raghava
raghava@iiitd.ac.in

CancerLSP Server:  
https://webs.iiitd.edu.in/raghava/cancerlsp/


Developed at:

- CSIR-Institute of Microbial Technology
- IIIT Delhi
 
 

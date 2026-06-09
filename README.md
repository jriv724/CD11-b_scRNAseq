# CD11b⁺ Myeloid Cell Dynamics in Multiple Myeloma

This repository contains analysis code and interactive visualizations supporting the study:

**Rivera J., Yan Q, et al., 2025**  
*Deciphering neutrophil dynamics in the focal lesion tumor microenvironment to overcome immunosuppression in multiple myeloma*  
Blood  
http://ashpublications.org/blood/article/146/20/2392/546480/Deciphering-neutrophil-dynamics-in-the-focal

---

## Overview

This project focuses on the role of **CD11b⁺ myeloid populations**, particularly neutrophils and monocytes, within the bone marrow and focal lesion tumor microenvironment in multiple myeloma.

The core objective is to understand how these cells:

- Contribute to local immunosuppression  
- Transition across maturation and activation states  
- Differ between bone marrow and osteolytic lesion environments  

Single-cell RNA-seq was used to resolve these dynamics at high resolution across patient samples.

---

## Key Findings (High-Level)

- Identification of distinct neutrophil maturation states within focal lesions  
- Evidence of transcriptional programs associated with immunosuppressive phenotypes  
- Divergence between bone marrow and lesion-associated myeloid compartments  
- Cross-species validation using mouse models  

---

## Interactive Figures

All figures are available as interactive HTML outputs:

### Main Figures

- Figure 1 — CD11b⁺ monocyte landscape  
  http://jriv724.github.io/CD11-b_scRNAseq/CD11b_monocytes_fig1.html

- Figure 2 — Feature expression and composition  
  http://jriv724.github.io/CD11-b_scRNAseq/figure2_feature_violin.html  

- Figure 2 (alternate layout)  
  http://jriv724.github.io/CD11-b_scRNAseq/Fig2.html  

- Figure 3 — Mature neutrophil states  
  http://jriv724.github.io/CD11-b_scRNAseq/Figure3_mature_neutrophils.html  

---

### Supplementary Figures

- Supplementary Figure 2  
  http://jriv724.github.io/CD11-b_scRNAseq/Supp_fig2.html  

- Supplementary Figure 3  
  http://jriv724.github.io/CD11-b_scRNAseq/supp_fig3.html  

---

### Additional Analyses

- Circular barplot (composition overview)  
  http://jriv724.github.io/CD11-b_scRNAseq/Circular_barplot.html  

- Mouse validation analysis  
  http://jriv724.github.io/CD11-b_scRNAseq/scMouse_analysis_git.html  

---

## Methods Summary

### Data
- Single-cell RNA-seq of CD11b⁺ populations  
- Samples derived from:
  - Bone marrow  
  - Osteolytic lesions  

### Analysis Workflow
- Preprocessing and QC (Scanpy / Seurat pipelines)
- Dimensionality reduction and clustering
- Differential expression analysis
- Cross-compartment comparisons (BM vs lesion)
- Cross-species validation (human vs mouse)

---

## Repository Structure

```text
scripts/        Analysis pipelines and processing scripts  
notebooks/      Exploratory and figure-generation notebooks  
figures/        Static figure exports  
docs/           HTML outputs for interactive figures  

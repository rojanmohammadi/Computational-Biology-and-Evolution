# Computational Genomics, Transcriptomics & Tumour Evolution 🧬

This repository contains advanced computational analyses focusing on the dynamic nature of cancer genomes, clonal evolution, and the tumour immune microenvironment. The projects integrate DNA/RNA sequencing data to infer phylogenetic trajectories and immune evasion mechanisms.

## 🎯 Key Learning Objectives & Applied Skills

### A. Tumour Evolution & Clonal Architecture
- **Phylogenetic Inference:** Inferring tumour evolutionary trees based on mutation data from single and multiple (sequential/temporal) samples.
- **Clonal Dynamics:** Using Gaussian finite mixture models (mClust) and EM algorithms to calculate Cancer Cell Fractions (CCF) and identify subclonal structures.
- **Single-Cell Analysis:** Utilizing single-cell DNA sequencing to decipher inter- and intra-tumour heterogeneity and genomic instability.

### B. Tumour Microenvironment (TME) & Immunogenicity
- **Immune Deconvolution:** Applying analytic techniques to bulk RNA-seq data to infer and compare the immune microenvironment across patient cohorts.
- **Neoantigen Discovery:** Implementing pipelines for HLA typing and neoantigen identification using integrated DNA and RNA-seq data.
- **Immune Evasion:** Identifying aberrations in antigen presentation machinery and understanding the interplay between cancer cells and the TME.
- **Immunotherapy Response:** Analyzing the determinants of tumour immunogenicity and their impact on patient survival and therapy resistance.

---

## 📁 Repository Structure

### 📂 [Clonal Evolution & Genomics](./Clonal_Evolution_and_CNA)
*Focus: Genomic instability and reconstructed evolutionary trajectories.*

- **[Copy Number Alteration (CNA) Analysis](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Computational-Biology-and-Evolution/blob/main/Clonal_Evolution_and_CNA/Copy-Number-Alteration-Analysis.html)**: Study of structural instability in high-grade serous ovarian cancer (HGSOC) cell lines.
- **[Genomic Instability Rate Report](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Computational-Biology-and-Evolution/blob/main/Clonal_Evolution_and_CNA/Genomic-Instability-Rate.html)**: Quantifying alteration rates and branch lengths in clonal lineages.
- **[Tumour Evolution & Phylogeny](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Computational-Biology-and-Evolution/blob/main/Clonal_Evolution_and_CNA/Tumour-Evolution-Phylogeny.html)**: Analysis of subclonal populations and phylogenetic tree reconstruction.

### 📂 [Immuno_Genomics_and_Pathways](./Immuno_Genomics_and_Pathways)
*Focus: Immune microenvironment deconvolution and metabolic signaling.*
- **[Metabolic Pathway Profiling](https://htmlpreview.github.io/?https://github.com/rojanmohammadi/Computational-Biology-and-Evolution/blob/main/Immuno_Genomics_and_Pathways/Pathway-Enrichment-and-Metabolic-Profiling.html)**: Distinguishing tumor vs. normal phenotypes through pathway enrichment.
- **[Immuno-Genomics & Tumor Evasion](./Immuno_Genomics_and_Pathways/Immuno-Genomics-and-Tumor-Evasion.pdf)**: Analysis of HLA typing, neoantigen presentation, and strategies for immune surveillance escape.

---

## 🛠 Tech Stack & Algorithms
- **Programming:** R (mClust, tidyverse, ggplot2, ChIPseeker).
- **Models:** Finite Mixture Models, Expectation-Maximization (EM), Dimension Reduction.
- **Workflows:** HLA typing, Neoantigen identification, RNA-seq Deconvolution.

---
*Note: Interactive HTML reports are best viewed via [GitHub HTML Preview](https://htmlpreview.github.io/).*

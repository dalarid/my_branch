---
title: "Project Objectives for Esophageal Cancer Research"
author: "Danielle Alarid"
date: "3/21/2021"
output: html_document
---

# Esophageal Cancer Project Objectives

```{r, echo=FALSE, out.width="40%", fig.align = 'center'}
knitr::include_graphics("https://upload.wikimedia.org/wikipedia/commons/1/14/2412_The_Esophagus.jpg")

```


## Overall goal
> To create pipeline datasets of esophageal carcinoma, isolate mutations, compute mutational burden, and to identify neoantigens and their likelihood of eliciting an immune response (fitness cost calculation).

## Datasets of Comparison
- Esophageal cancer mutations
vs
- Healthy esophagus

## Framework
Increase in mutations, increase in cancer, increase in neoantigens

## Tools
- **GitHub** for repositories
- **slurm** for batch scripting into the HPC
- **Rstudio** for regression models
- **VarScan** for PVAC protein snakemake
- **GATK** for identifying SNPs and indels in germline DNA and RNAseq data
- **STRELKA** for variant calling



# Literature Goals and Computational Learning Objectives

Literature | Computational
------------- | -------------
**Goal #1** Understand the principles of immunoediting as it applies to cancer escaping the immune system | Familiarize with Github and slurm
**Goal #2** Understand principles of neoantigen prediction/prioritization | Understand metadata and R Markdown
**Goal #3** Understand what is known about mutation/neoantigen progression in cancer precursors and invasive cancers generally | Understand the purpose of a config file and quality control
**Goal #4** Understand what is known about mutation progression in esophageal carcinoma specifically | Understand trimming, read mapping, and variant calling




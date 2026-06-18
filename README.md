# Podocerus Phenotypic Diversity Analysis

## Overview

This repository contains the analytical workflow used to investigate phenotypic diversity in the marine amphipod *Podocerus aff. cristatus*.

The project integrates image-derived phenotypes, phylogenetic analyses, statistical modeling, camouflage assessment, and ecological data to examine how color-pattern variation is distributed within a species and whether phenotypic diversity is best characterized as discrete morphs or continuous multivariate variation.

Analyses further evaluate relationships among phenotype, microhabitat use, camouflage performance, nudibranch resemblance, and genetic structure.

---

## Workflow Summary

### 1. Image Processing & Phenotype Extraction

`00_patternize_recolorize.Rmd`

* Image standardization and preprocessing
* Color calibration workflows
* Pattern extraction and quantification
* Preparation of image-derived phenotypic datasets

### 2. Phylogenetic Analyses

`Phylogenetic_analysis.Rmd`

* Sequence alignment and quality control
* Haplotype analyses
* Phylogenetic reconstruction
* Species delimitation analyses

### 3. Camouflage Analyses

`Model1_chromatic_contrast.Rmd`

* Chromatic contrast analyses
* Background matching assessments

`Model2_achromatic_contrast.Rmd`

* Achromatic contrast analyses
* Luminance-based camouflage metrics

`Model3_GabRat.Rmd`

* Outline disruption analyses
* GabRat edge-disruption metrics

### 4. Ecological & Statistical Models

`Model4_Occurrence.Rmd`

* Microhabitat association analyses
* Population occurrence models
* Phenotype-environment relationships

`Model5_chromatic_contrast.Rmd`

* Extended chromatic contrast analyses
* Evaluation of ecological predictors of camouflage performance

---

## Analytical Approaches

* Principal Components Analysis (PCA)
* Multivariate statistical analyses
* Bayesian generalized linear mixed models
* Model selection and comparison
* Permutation-based hypothesis testing
* Color-pattern clustering
* Phylogenetic inference
* Haplotype network analyses

---

## Software & Packages

Primary analyses were conducted using:

* R
* R Markdown
* tidyverse
* brms
* colordistance
* vegan
* cluster
* ape
* pegas
* ggtree
* ImageJ
* Geneious
* IQ-TREE

---

## Research Applications

This workflow demonstrates approaches for:

* Quantitative phenotype analysis
* Integration of imaging, ecological, and genetic datasets
* Bayesian statistical modeling
* Multivariate biological data analysis
* Camouflage and visual ecology research
* Reproducible scientific workflows

---

## Repository Structure

```text
analysis/
├── 00_patternize_recolorize.Rmd
├── Phylogenetic_analysis.Rmd
├── Model1_chromatic_contrast.Rmd
├── Model2_achromatic_contrast.Rmd
├── Model3_GabRat.Rmd
├── Model4_Occurrence.Rmd
└── Model5_chromatic_contrast.Rmd
```

---

## Associated Research

Cummings, B.C. *Unraveling Amphipod Diversity Across Phylogenetic, Phenotypic, and Community Scales*. PhD Dissertation, University of Florida (2026).

Cummings, B.C. *Continuous Phenotypic Diversity in Podocerus aff. cristatus*. Manuscript in preparation.

---

## Author

**Brittany Cummings, PhD**

Evolutionary Genomics Researcher

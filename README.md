# Podocerus Phenotypic Diversity Analysis

## Overview

This repository contains the analytical workflow used to investigate phenotypic diversity in the marine amphipod *Podocerus aff. cristatus*. The project integrates image analysis, color-pattern quantification, phylogenetic inference, statistical modeling, camouflage assessment, and ecological analyses within a reproducible R and R Markdown framework.

The study examined whether phenotypic variation within a widespread North American amphipod species is best characterized as discrete color morphs or continuous multivariate variation. Analyses further evaluated relationships among phenotype, microhabitat use, camouflage performance, nudibranch resemblance, and genetic structure.

---

## Analytical Components

### Image Processing & Standardization

* Image calibration and color standardization
* Geometric landmarking and image unwarping
* Region-of-interest (ROI) extraction
* Automated image preprocessing workflows

### Color & Pattern Quantification

* Color histogram generation
* Earth Mover's Distance (EMD) calculations
* Color-pattern clustering
* Phenotypic distance analyses

### Phylogenetic & Genetic Analyses

* Sequence alignment and quality control
* Haplotype network construction
* Phylogenetic inference
* Species delimitation analyses

### Statistical Modeling

* Principal Components Analysis (PCA)
* Multivariate statistical analyses
* Bayesian generalized linear mixed models
* Model selection and comparison
* Permutation-based hypothesis testing

### Camouflage Assessment

* Visual contrast calculations
* Chromatic similarity analyses
* Achromatic similarity analyses
* Outline disruption metrics
* Background matching assessments

### Ecological Analyses

* Microhabitat association analyses
* Population structure analyses
* Site-level comparisons
* Phenotype-environment relationships

### Visualization & Reporting

* Publication-quality figure generation
* Automated statistical summaries
* Reproducible manuscript outputs using R Markdown

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

## Repository Structure

```text
├── data/
├── scripts/
├── figures/
├── outputs/
└── README.md
```

---

## Research Applications

This workflow demonstrates approaches for:

* Reproducible biological data analysis
* Integration of imaging, ecological, and genetic datasets
* Statistical modeling of complex biological systems
* Multivariate phenotype quantification
* Scientific visualization and reporting

---

## Citation

If referencing this workflow, please cite:

Cummings, B.C. *Unraveling Amphipod Diversity Across Phylogenetic, Phenotypic, and Community Scales*. PhD Dissertation, University of Florida (2026).

---

## Author

**Brittany Cummings, PhD**
Evolutionary Genomics Researcher
University of Florida

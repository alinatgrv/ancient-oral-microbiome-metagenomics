# Dead Man's Teeth — Metagenomics Analysis

This repository contains the analysis of ancient dental calculus microbiome samples.

The project explores microbial communities preserved in medieval dental calculus using both:

- 16S rRNA amplicon sequencing
- shotgun metagenomics

The analysis includes:

- ASV inference using DADA2
- taxonomic classification using SILVA database
- microbiome composition analysis
- pathogen detection
- comparison of ancient and modern bacterial genomes

## Repository structure

```
dead-mans-teeth-metagenomics/
│
├── data/
│   ├── raw/            # raw sequencing data
│   └── processed/      # processed data
│
├── metadata/           # sample metadata
├── scripts/            # analysis scripts
├── results/            # output tables
├── figures/            # plots and visualizations
├── report/             # lab report
└── README.md
```
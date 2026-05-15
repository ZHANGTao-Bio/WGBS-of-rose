# WGBS analysis of rose flower opening

This repository contains computational pipelines and scripts for **whole-genome bisulfite sequencing (WGBS)** data generated from rose (*Rosa* sp.) petals at different stages of flower opening.

## Contents
- Raw data preprocessing (trimming, quality control)
- Methylation calling (Bismark, BS-Seeker2)
- Differential methylation analysis (methylKit, DSS)
- Annotation and functional enrichment
- Visualization (methylation heatmaps, circos plots, IGV tracks)

## Dependencies
- Nextflow / Snakemake workflows
- R/Bioconductor, Python (pandas, matplotlib)
- Genome reference: *Rosa chinensis* ‘Old Blush’ v2.0

## Usage
See individual script headers and `workflows/` directory for step-by-step instructions.

## Citation
If you use this code, please cite our paper (link/TBA).

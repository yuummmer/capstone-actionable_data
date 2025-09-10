# Capstone Project: Processing Actionable Data  
### Reproducing Transcriptomic Analyses from Neurodevelopmental Disorder Studies

## Project Overview
This project reproduces and extends elements of the analyses from  
*Integrative analysis of 115 transcriptomic studies decodes the molecular landscape of neurodevelopmental disorders* (2023).  

The goal is to practice end-to-end RNA-seq analysis — from data acquisition and normalization to differential expression, enrichment, and visualization — while exploring how transcriptomic integration can reveal shared molecular signatures in neurodevelopmental disorders.

## Project Goals
1. **Reproduce key findings at a smaller scale**  
   - Obtain publicly available datasets (GEO/Synapse/Zenodo).  
   - Generate normalized expression matrices with DESeq2 / edgeR.  
   - Replicate visualizations such as PCA, volcano plots, and heatmaps.

2. **Practice transcriptomic analysis workflows**  
   - Differential expression and gene set enrichment.  
   - Biological interpretation using clusterProfiler.  
   - Document a reproducible workflow.

3. **Evaluate integration approaches**  
   - Compare across multiple datasets or cohorts.  
   - Identify shared molecular signatures across studies.

4. **Develop computational skills**  
   - Use GitHub for version control and documentation.  
   - Produce publication-quality figures.  

5. **Communicate insights**  
   - Summarize results with clear figures and narratives.  
   - Reflect on challenges of large-scale meta-analysis.

## Repository Structure

capstone/
├── data/
│ ├── raw/ # unmodified datasets (downloaded)
│ └── processed/ # normalized & cleaned data
├── scripts/ # R scripts for analysis
├── results/
│ └── figures/ # plots, heatmaps, PCA, volcano plots
├── docs/ # notes, summaries, blog drafts
├── README.md # project overview (this file)
├── .gitignore # ignore raw data & large files
└── requirements.txt # package dependencies
# PDAC Data Integration using Miss-SNF
Assignment 2  - Scientific Visualization 2025/26

## 📁 Files

- [`Presentation`](Presentation.pdf): final presentation summarizing methodology, experiments, and results;
- [`Code`](Assignment2.ipynb): Jupyter notebook implementing the project workflow.

## 📚 Project Description

This project focuses on integrating multi-omics datasets for pancreatic ductal adenocarcinoma (PDAC), the most common and aggressive form of pancreatic cancer.

The workflow applies <b><i>miss-snf</i></b>, an adaptation of the similarity network fusion (snf) framework designed to handle missing data across multi-omics platforms.

The pipeline includes: 
- <b> missing point analysis</b>: evaluates missingness patterns across omics layers to understand data quality and structure;
- <b> <i> miss-snf </i> data integration</b>: builds sample-similarity networks for each omics type, adjusts for missing entries, and fuses them into a unified representation;
- <b> unsupervised clustering</b>: identifies potential molecular subtypes relevant to PDAC biology and progression;
- <b> survival analysis</b>: links discovered clusters to patient outcomes to assess clinical relevance.

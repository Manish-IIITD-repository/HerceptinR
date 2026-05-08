# HerceptinR: Herceptin Resistance Database for Breast Cancer

Welcome to the official documentation for **HerceptinR**, a comprehensive database designed to help researchers and clinicians understand the molecular mechanisms behind Trastuzumab (Herceptin) resistance in breast cancer patients. Herceptin is a frontline monoclonal antibody therapy for HER2-positive breast cancer, yet approximately 70% of patients experience de novo or acquired resistance.

**Web Server:** [http://crdd.osdd.net/raghava/herceptinr/](http://crdd.osdd.net/raghava/herceptinr/)

---

## Citation

Ahmad, S., Gupta, S., Kumar, R., Varshney, G. C., & Raghava, G. P. S. (2014).
**Herceptin Resistance Database for Understanding Mechanism of Resistance in Breast Cancer Patients.**
*Scientific Reports*, 4, 4483.
[https://doi.org/10.1038/srep04483](https://doi.org/10.1038/srep04483)

---

## About the Platform

HerceptinR provides a unified platform that correlates experimental assay data with deep genomic insights. By integrating inhomogeneous data from scattered sources, the database allows for a gross view of how mutations, gene expression, and copy number variations (CNV) contribute to drug resistance.

### Data Overview
* **Assay Data**: Information on 2,500 assays performed against various breast cancer cell lines.
* **Cell Lines**: Genomic and pharmacological profiles for 51 breast cancer cell lines (BCCs).
* **Supplementary Drugs**: Sensitivity data for 111 drugs/chemicals tested in combination with Herceptin.
* **Genomic Factors**: Integration of data from CCLE (Cancer Cell Line Encyclopedia) including 16,582 genes.

---

## Key Features

### Assay Exploration
* **Simple & Advanced Search**: Query assays by cell line name, supplementary drug, resistance status, or specific genomic alterations.
* **Browse PMIDs**: Access data acquired from 75 research articles with direct links to PubMed and full-text PDFs.
* **Alteration Analysis**: Browse 337 types of reported cell line alterations (e.g., siRNA silencing or ectopic expression) to see their impact on Herceptin efficacy.

### Genomic Analysis Tools
* **Mutation Search**: Explore the mutational status of key genes, searchable by protein family, domain, or subcellular localization.
* **Summary of Cell Line**: View a complete genomic "snapshot," including lists of over-expressed and under-expressed genes.
* **Multiple Cell Line Comparison**: Instantly compare up to five cell lines based on their mutational, expression, and CNV status.
* **Relative GE/CNVs**: Pairwise comparison tool to identify the ratio or difference in expression/CNV of specific genes between two cell lines.

### Visualization & Alignment
* **Drug Sensitivity Plots**: View drugs plotted in decreasing order of IC50 to identify the most effective supplementary drug candidates.
* **Alignment of Mutants**: Multiple sequence alignment of important mutant genes (e.g., PIK3CA, PTEN, TP53) using the Jalview applet.

---

## Technical Overview

* **Backend**: Apache HTTP Server 2.2 with MySQL 5.1.47.
* **Frontend**: PHP 5.2.9, HTML, and JavaScript.
* **Data Sources**: Integrated data from PubMed, CCLE, CancerDR, and UniProt.
* **Gene Sets**: Specifically tracks 22 genes involved in resistance via expression and 8 genes involved via mutation.

---

## Applications

* **Biomarker Discovery**: Identifying genomic signatures that predict whether a patient will respond to Herceptin.
* **Personalized Medicine**: Selecting the most appropriate supplementary drug combination based on the specific genomic constraints of a patient's cancer.
* **Target Identification**: Locating new molecular targets by studying alterations that reverse resistance in vitro.

---

## Contact & Authors

**G.P.S. Raghava** & **G.C.V. Varshney**
CSIR-Institute of Microbial Technology, Chandigarh, India.
**Email**: raghava@imtech.res.in / grish@imtech.res.in

---

## License

This resource is licensed under a **Creative Commons Attribution NonCommercial-ShareAlike 3.0 Unported License**.

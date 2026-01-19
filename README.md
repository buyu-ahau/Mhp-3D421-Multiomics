# Multi-omics analysis of Mhp-infected 3D4/21 cells

This repository contains the analysis scripts and code for the manuscript:
**"Multi-omics integration reveals a novel JUNB-ANXA1 axis regulating the immune response to Mycoplasma hyopneumoniae infection in porcine alveolar macrophages"**

## Data Availability
The raw sequencing data have been deposited in the **NCBI BioProject** database under accession number **PRJNA1251820**.

## Analysis Pipeline
The analysis workflow includes:
- **RNA-seq**: Quality control, alignment (HISAT2), quantification (featureCounts), and differential expression (DESeq2).
- **ATAC-seq**: Alignment (BWA-MEM), peak calling (MACS2), and motif analysis (HOMER).
- **CUT&Tag**: Histone modification profiling and integration.

## Contact
For any questions regarding the code, please open an issue or contact: **Yu Bu (Email: 15225568606@163.com)**

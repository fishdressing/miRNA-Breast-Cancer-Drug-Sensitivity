# Breast Cancer Drug Sensitivity Prediction Using miRNA-Derived Graph Representations and Graph Neural Networks
This dataset contains raw miRNA expression levels used in research regarding drug sensitivity prediction. This data was derived from TCGA-BRCA Repository through the GDC toolbox.
data_by_patient/: Contains subfolders named after TCGA barcodes
miRNA_ID: Unique miRBase identifier (e.g., hsa-mir-21).
read_count: Raw sequence reads.

## Dataset Source

- **Primary source:** The Cancer Genome Atlas Breast Cancer Invasive Carcinoma cohort (TCGA-BRCA)
- **Access platform:** Genomic Data Commons (GDC)
- **Data type:** miRNA expression quantification
- **File type:** miRBase21 miRNA quantification text files
- **Research use:** Drug sensitivity prediction using miRNA expression and graph neural networks

## Repository Structure

```text
project/
│
├── data_by_patient/
│   ├── TCGA-XX-XXXX/
│   │   ├── *.mirbase21.mirnas.quantification.txt
│   │   └── *.mirbase21.isoforms.quantification.txt
│   │
│   ├── TCGA-YY-YYYY/
│   │   ├── *.mirbase21.mirnas.quantification.txt
│   │   └── *.mirbase21.isoforms.quantification.txt
│   │
│   └── ...
│
├── BRCA_Drug_sensitivity.csv
├── metadata2.json
└── README.md

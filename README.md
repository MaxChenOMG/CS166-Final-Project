🧬 CS166 Final Project — Metabolomics Disease Classification
Comparing Abundance-Only Models vs. Molecular Structure Embeddings (Morgan FP & ChemBERTa)

This repository contains the full workflow, code, and analysis for my CS166 Computational Systems Biology final project.
The goal is to evaluate how molecular structural information (Morgan fingerprints or ChemBERTa embeddings) can improve—or fail to improve—classification performance when predicting disease status from LC-MS metabolomics data.


📚 Dataset Source

All data come from the public metabolomics repository MetaboLights:

MTBLS8920 — Breast Cancer vs. Healthy Controls
https://www.ebi.ac.uk/metabolights/MTBLS8920

Files used include:

LC-MS positive HILIC metabolite profiling

LC-MS negative (not used)

Sample metadata (s_MTBLS8920.txt)

QC samples were removed for ML consistency.


📦 CS166-Final-Project
│
├── CS166_Final_Project.ipynb
├── Morgan_fingerprint_Embedding.ipynb
├── Morgan_fingerprint_Embedding.pdf
│
├── m_MTBLS8920_LC-MS_positive_hilic_metabolite_profiling_v2_maf.tsv
├── m_MTBLS8920_LC-MS_negative_hilic_metabolite_profiling.tsv
├── s_MTBLS8920.txt
│
└── README.md

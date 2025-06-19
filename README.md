# TFM
This repository is part of my Master's thesis for the **Master's in Computational Social Sciences** at **Universidad Carlos III de Madrid**.  
**Academic Year**: 2024–2025

---

## 📘 Overview

This thesis investigates how R&D investment and patenting activity affect firm growth among top R&D investors in the European Union. The analysis uses firm-level panel data and employs a combination of:

- Panel OLS with fixed effects  
- Instrumental Variable (2SLS) estimation  
- Local Projections (IRFs)  
- Two-step Difference-GMM and System-GMM

---

## 📁 Folder Structure

```
├── README.md # Project documentation
├── merged_data_EU.qmd # Quarto source file (main report)
├── merged_data_EU.html # Rendered output of the analysis
├── merged_data_EU_files/ # HTML dependencies
├── patents count - back.csv # Raw patent data
├── TFM/
│ ├── TFM.Rproj # R project file
│ ├── combined_data.csv # Original merged dataset
│ ├── merged_data_imputed.csv # Imputed dataset used for modeling
│ └── EU800(2004–2024)/ # Subfolder with source data
```


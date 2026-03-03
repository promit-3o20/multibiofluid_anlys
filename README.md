<!-- # Project Title -->

## Overview

This project contains statistical analysis scripts, raw and processed datasets, and generated results (figures and tables).
The repository is organized into three main directories: `codes`, `data`, and `results`.

---

## Folder Structure

```
.
├── codes
│   ├── foo
│   │   ├── results.ipynb
│   │   └── statistical_analysis.ipynb
│   └── stat_anlys.py
├── data
│   ├── Combined.xlsx
│   ├── Copy new draft 6.xlsx
│   ├── DOC-20260118-WA0003-1.xlsx
│   ├── DOC-20260118-WA0003.xlsx
│   ├── intrmd
│   │   └── processed.xlsx
│   └── processed_combine.xlsx
└── results
    ├── 4.1_effect_size_with_heterogeneity.png
    ├── 4.1_effect_sizes_all_sheets.csv
    ├── 4.2_figure1_intergenecorr.png
    ├── 4.2_intergene_corr_all_compartments.csv
    ├── 4.3_urine_network_rewiring_results.csv
    └── 4.3_urine_significant_reversals.csv
```

---

## Directory Details

### 📂 `codes/`

Contains all analysis scripts and notebooks.

* `stat_anlys.py` – Main statistical analysis script.
* `foo/`

  * `statistical_analysis.ipynb` – Jupyter notebook for step-by-step analysis.
  * `results.ipynb` – Notebook for result exploration and visualization.

---

### 📂 `data/`

Contains raw and processed datasets used in the analysis.

* Raw Excel files (`.xlsx`)
* `intrmd/` – Intermediate processed files

  * `processed.xlsx` – Cleaned/processed dataset
* `processed_combine.xlsx` – Combined processed dataset

---

### 📂 `results/`

Contains output files generated from the analysis.

* `.png` – Generated figures and plots
* `.csv` – Statistical output tables and result summaries

---

## Workflow Overview

1. Raw data is stored in `data/`
2. Data preprocessing and statistical analysis are performed using scripts/notebooks in `codes/`
3. Outputs (figures and result tables) are saved in `results/`

---

## Requirements

* Python 3.9.
* Jupyter Notebook
* Required Python libraries (e.g., pandas, numpy, matplotlib, seaborn, scipy)

---

## Notes

* Do not modify raw data files directly.
* Intermediate files in `data/intrmd/` are generated during preprocessing.
* Final results should always be saved in the `results/` directory.

---

## Author

Pramit
Date: 03-03-2026

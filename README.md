# AkshajSharma_NOVATASK

## Task 1: Exploratory Data Analysis (EDA)

Exploratory data analysis on the SDSS (Sloan Digital Sky Survey) dataset, classifying astronomical objects as STAR, GALAXY, or QUASAR.

### Contents
- `Task 1.csv` — dataset (100,000 observations, 18 features)
- `Metadata.pdf` — column descriptions
- `nova-task1-eda.ipynb` — full EDA notebook

### Key Findings
- Fixed a hidden data quality issue: -9999 sentinel values in magnitude columns (u, g, z) were distorting statistics
- Magnitude distributions are bimodal, driven by class (stars are systematically brighter than galaxies/quasars)
- Redshift correlates with class: stars cluster near redshift ≈ 0, while galaxies/quasars show a spread toward higher redshift
- Observation activity shows a clear seasonal dip during June-August, likely due to shorter/less favorable observing conditions

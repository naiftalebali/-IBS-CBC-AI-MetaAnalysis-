# AI-Augmented CBC Meta-Analysis for IBS Diagnosis
Repository for "AI-Enhanced Complete Blood Count Markers for Irritable Bowel Syndrome" (DOI: [INSERT])

## Data Availability
- `data/aggregated_meta_data.csv`: Complete dataset for meta-analysis (study-level data)
- `data/yemen_cohort_raw.csv`: De-identified patient data from Yemen validation cohort
- Supplemental tables available in `data/supplemental_tables.xlsx`

## Code Reproducibility
### Meta-Analysis
```bash
cd code/meta_analysis
Rscript random_effects_model.R --input ../data/aggregated_meta_data.csv

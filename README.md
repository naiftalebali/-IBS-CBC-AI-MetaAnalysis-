## Data Availability
   - Global Studies: [aggregated_meta_data.csv](data/aggregated_meta_data.csv)
   - Yemen Cohort: [yemen_cohort_raw.csv](data/yemen_cohort_raw.csv)
   
   ## Reproducibility
   ```bash
   # Install dependencies
   pip install -r requirements.txt
   
   # Run meta-analysis
   Rscript code/meta_analysis/random_effects_model.R
   
   # Train AI model
   python code/AI_model/train_xgboost.py

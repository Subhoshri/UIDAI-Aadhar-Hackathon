# UIDAI Aadhaar Hackathon

## Problem Statement
This project analyses Aadhaar enrollment, demographic updates, and biometric updates to identify societal patterns, operational stress points, and opportunities for governance improvement.

## Datasets Used
The analysis uses three UIDAI-provided datasets:
- Enrolment dataset (age-wise enrolment counts)
- Demographic update dataset (age-wise demographic updates)
- Biometric update dataset (age-wise biometric updates)

The datasets used in this project were provided as part of the UIDAI Hackathon and consist of large, multi-file CSV datasets.
Due to size constraints, raw data files are not included in this repository.

Users can reproduce the analysis by downloading the Aadhaar Enrolment, Demographic Update, and Biometric Update datasets from the official UIDAI Hackathon data portal and placing them in the /data directory as described below.

## Repository Structure
- 01_data_ingestion_and_cleaning.ipynb: Data concatenation, cleaning, validation
- 02_feature_engineering_and_eda.ipynb: Feature engineering, aggregation, exploratory analysis
- data/
  ├── enrolment/
      ├── clean/
      ├── raw/
  ├── demographic/
      ├── clean/
      ├── raw/
  └── biometric/
      ├── clean/
      ├── raw/
 - intermediate/     

# CPP Multiverse Project - Stage 1 Registered Report analysis code

## Overview
We re-analyzed pilot data and used joint modeling techniques integrating the Drift Diffusion Model (DDM) with CPP data, investigating whether CPP serves as a robust ERP marker of evidence accumulation across various perceptual decision-making tasks.
 
## ​​Directory Structure​
.

├── 1_Preprocess_Data.py               # Raw EEG/behavioral data preprocessing

├── 2_Extract_Feature_for_DDM.py       # CPP feature extraction for DDM fitting

├── 3_Run_DDM_Models.py                # Main DDM fitting script

├── model.py                           # DDM model specifications

├── 4_Check_DDM_Models_Result.py       # Model diagnostics (e.g., convergence)

├── 5_Data_for_Two_Step.py             # Prepares data for two-stage analysis

├── 5_Two_Step.Rmd                     # Implements two-stage correlation (DDM-CPP)

├── 6_Figure4a&s1.Rmd                  # Generates main figures (Fig4a & S1)

├── 7_Sensitivity_analysis_run_model.ipynb  # Subject-level model robustness tests

├── 8_Sensitivity_analysis_load_model.ipynb # Sensitivity results comparison

│

├── Multiverse_Model_Data/             # Temporary DDM results (multiverse CPP)

└── Sensitivity_Model_Data/            # Temporary DDM results (sensitivity analysis)



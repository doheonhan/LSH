# LLM & Interpolation Hybrid
## |Paper| 
* Imbalanced Tabular Data Synthesis via LLM-Seeds and Interpolation

## |How to use|
### 1. LLM Quality.ipynb: LLM Quality Check in the paper (kNN distance / Uncertainty) 
### 2. Data Generation.ipynb: Data generation with SMOTE/BSM/ADA, LLM(GPT/DEV), and Hybrid. This includes generating few-shot and zero-shot datasets. Also, you can generate datasets for the Seed-sensitivity analysis and Ablation study.
### 3. Training and Testing.ipynb: Train (70%) with 5-fold cross-validation & Test (30%)
### 4. Results and Analysis.ipynb: Overall performance, performance with imbalance ratio, achievement rate (robustness)
### 5. Efficiency Experiment.ipynb: Runtime measuring
### 6. Additional files
* bayesiantests.py: For Bayesian Sign Test
* datagen.zip: LLM-based oversampler (LLM-oversampling method using API)
  - To choose 'gpt-4o-mini' or 'Devstral 2', find the file 'datagen/aiutils/openai_utils.py' and choose one of the two, activate it.
* df_meta_new.csv: Metadata of 60 datasets (seperately generated for all datasets)
* data_num.zip: 102 datasets (including 60 datasets)

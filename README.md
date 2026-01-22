# LLM SMOTE Hybrid (LSH)
## |Paper| 
* Synthetic Data Generation Tabular Data via LLM-Seeds and SMOTE Expansion

## |How to use|
### 1. Data Generation.ipynb: Data generation with SMOTE, LLM, and LSH. This includes the generation of few-shot and zero-shot datasets.
### 2. Training and Testing.ipynb: Train (70%) with 5-fold cross-validation & Test (30%)
### 3. Results and Analysis.ipynb: Overall performance, performance with imbalance ratio, achievement rate (robustness)
### 4. Efficiency Experiment.ipynb: Runtime measuring
### 5. Additional files
* bayesiantests.py: For Bayesian Sign Test
* datagen.zip: LLM-based oversampler
* df_meta_new.csv: Metadata of 60 datasets
* data_num.zip: 102 datasets (including 60 datasets)

# Corporate Sustainability Analysis of Companies
This project was part of a 50% weightage assignment for my Data Mining and Business Analytics module. I had to chose between 2 datasets, both with same columns containing metrics about 10,000 companies, to create predictive models to mine for insights to analyse and construct recommendations to help businesses improve their sustainability score. 

## About Project
Build predictive models to help businesses achieve their sustainability goals. The rationale is to learn how the activities of a company, such as their carbon emissions, recycling rates, etc., influences their likelihood of achieving sustainability goals, so that recommendations can be generated through interpreting the predictive models.

### Technical Stuff
Jupyter Notebook:
- Research on Corperate Sustainability + Info related and applicable to project
- Data Cleaning and Preparation
- Data/Features Engineering with Research and External data sources (To get bonus mark)
- Perform EDA

SAS EM Miner:
- Features Selection
- Data Modelling
- Model Comparison
- Model Interpretation

### About files:
- 2202934B_Data Cleaning.ipynb - jupyter notebook used for data cleaning and preparation.
- Normalize data - Normalize all numerical features using z-score scaling because doing so manually in SAS EM is torture.
- Min-max data - Normalize all numerical features using z-score scaling because of Polynomial interpretability.
- 2202934_DMBA.zip - SAS EM Miner file, zipped.
- P03_Javen Lai Le Yu.pdf - Report.

datasets:
- sustainability_data_set_1.csv - original dataset provided
- data_modelling.csv - dataset_1 after cleaning with jupyter notebook
- data_normalized.csv - data_modelling, but all numeric features normalized using z-score
- data_normalized2.csv - data_modelling, but all numeric features normalized using min-max
- env_ac_taxener_spreadsheet.xlsx - dataset integrated with dataset_1

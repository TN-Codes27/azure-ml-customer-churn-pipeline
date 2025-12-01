## Azure-ml-customer-churn-pipeline
End-to-end ML pipeline for Customer Churn Prediction using Azure Machine Learning, including data ingestion, training, model registry, deployment and monitoring


# Planned core technologies 
Python (3.10+)
Azure Machine Learning v2 SDK
Azure ML Pipelines
LightGBM / XGBoost
Azure Compute (CPU cluster)
Azure Online Endpoints
GitHub version control

# Basic repo structure
azure-ml-customer-churn-pipeline/
│
├── data/
│   ├── raw/               
│   └── processed/         
│
├── src/
│   ├── data_prep/         
│   ├── train/             
│   ├── evaluate/          
│   ├── score/            
│
├── pipelines/
│
├── azure/
│
├── notebooks/
│
├── tests/
│   ├── test_train.py
│   ├── test_data_prep.py
│
├── docs/
│
├── .gitignore
├── requirements.txt
├── README.md
└── LICENSE(may delete)

# Planned project overview 
Goal: Predict which customers are at risk of cancelling their contract
Model: Gradient boosting (LightGBM/XGBoost)
Pipeline: Multi-step Azure ML Pipeline
Deployment: Managed online endpoint
Monitoring: Data drift + prediction logging

# Planned results 
ROC-AUC
precision 
recall 

# Installation and pipeline
installation: pip install -m requirements.txt 
run pipeline: python pipelines/pipeline.py



# MLOps-DBX-AML

## Serving models via rest api

### Setup
* Launch an Azure Databricks cluster
* Install MLflow
* Install the Azure ML SDK
* Create or load an Azure ML Workspace
* Take a model previously trained on Databricks and stored on a dbfs storage

### Steps
* Build an Azure Container image for model deployment
* Deploy model to "dev" using Azure Container Instance (ACI)
* Query the deployed model in "dev"
* 
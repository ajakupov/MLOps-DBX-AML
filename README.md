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
* Deploy the model to "dev" using Azure Container Instance (ACI)
* Query the deployed model in "dev"
* Deploy the model to "prod" using Azure Kubernetes Services (AKS)
* Query the deploed model in "prod"
* #TODO How to update the production environment ?
    - e.g. train a new model, build an Azure Container image for the model and deploy it to the AKS cluser? 
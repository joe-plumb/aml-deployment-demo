# Azure Machine Learning Deployment Demonstration
## Steps
1. Look at workspace and view model
2. Look at code to register model (for awareness)
3. Look at model deployment code to package model with assets and deploy to webservice
4. Look at deployed model, validate by scoring data

## Key Takeaways
- Using AML SDK to register and collect assets
- Environments are portable definitions to ensure consitency between training and deployment - more here https://docs.microsoft.com/en-us/azure/machine-learning/concept-environments
- InferenceConfig and DeploymentConfig
- Curated environments available out of the box: https://docs.microsoft.com/en-us/azure/machine-learning/resource-curated-environments

## Further reading
- Most of the code was from here: https://github.com/Azure/MachineLearningNotebooks/blob/master/how-to-use-azureml/deployment/deploy-to-cloud/model-register-and-deploy.ipynb - I will package and send this code as well
- Details about deploying to ACI, and many other services here: https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-azure-container-instance
- Attach to existing AKS instance and deploy: https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-azure-kubernetes-service#attach-an-existing-aks-cluster
- Or, deploy to App Service (preview): https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-app-service 

## Next steps
- 

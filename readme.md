# 33.3.6 Mini-Project: End-to-end Churn Prediction Using SageMaker

This repository holds the files I created in doing the mini-project in AWS Sagemaker JupyterLab

### 33-3-6-StudentMLEMiniProjectChurnPredictionAWS_WalkerBruce.ipynb
With this notebook, I learned how to:
- store data in an S3 bucket and then read that data into a dataframe in my notebook
- pre-processing data, split the data for training, validation and testing; and then, write the processed/split data back to my S3 bucket
- use SageMaker to create an estimator using a built-in algorithm (XGBoost in this case)
- use a HyperparameterTuner to find the best hyperparameters
- create and train(fit) an estimator(model) using the tuned hyperparameters and training jobs
- look at the the debugger output to see how SageMaker decided which features had which importance in predicting the outcome

### 33-3-6-StudentMLEMiniProject_CustomerChurnPrediction_AWSPipelines_WalkerBruce.ipynb
With this notebook, I learned:
- how to use pipelines to create and train the SageMaker estimator/model in a detached, cloud-based
- that pipelines can be used to build/train the ML model in an unattended way so that long-running processes take place in the cloud
- the pipeline processes can be monitored/accessed at different times and/or from multiple machines
- the completion of the training job does not rely on my local machine being on and running.

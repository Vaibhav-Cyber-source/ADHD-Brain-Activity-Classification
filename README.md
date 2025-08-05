Project Description 
This project's objective is to help NHS General Practitioners to be able to early detect Attention Deficit Hyperactivity Disorder (ADHD) in patients aged below 25. From a mix of behavioural, cognitive, and MRI datasets, we created and tested two machine learning models (Logistic Regression and Random Forest) to be able to categorize patients as ADHD-positive or not.
Objectives
? Improve early ADHD diagnosis.
? Reduce clinician workload through intelligent screening tools
? Ensure fairness, accuracy, and GDPR compliance in predictions.
Dataset overview
? Demographic data
? Cognitive assessments (e.g., Strengths and Difficulties Questionnaire)
? MRI scan data
? Social and behavioural indicators
How to Run the Code
? The data preprocessing file is required to be run, and all the datasets are required to be explored. 
? After exploring the dataset, based on the common column, the datasets are required to be merged. 
? Missing values of the dataset are required to be removed, and a PCA analysis is performed to extract features. 
? The dataset is divided into three sets such as validation, training, and testing, to classify the ADHD patients. 
?   Save the datasets
? Datasets are required to be imported to find out the model outcomes.
? Implement machine learning models and explore the model performance. 
? Find out the best model 
Assumptions
? Missing values are imputed or removed where appropriate.
? The data is imbalanced; recall is prioritized to ensure ADHD cases are not missed.
? MRI and questionnaire features are both essential to prediction.
? Data splitting (train/validation/test) ensures unbiased evaluation.
Summary 
The Random Forest model was more accurate (70%) compared to Logistic Regression (68%). The models also performed poorly in identifying non-ADHD cases. SHAP analysis and feature importance exploration were done for model interpretability. The model needs improvement for clinical deployment.



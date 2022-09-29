# Predictive Analysis with Explainable AI

Telco data in tabular format was used to predict the output label. This notebook contains data cleaning, visualizing, and machine learning approaches to predict the output label. After predicting the label, Explainable AI was used to explain the model output. 

## Dataset

Dataser link: [**Kaggle**](https://www.kaggle.com/code/moshiurrahmanfaisal/predictive-analysis-with-explainable-ai)


## Model Accuracy

#### From the dataset 80% data was used for training and 20% for testing. 



| Machine Learning Models | Accuracy (%) |   Area Under the Curve (%) |
| :-------- | :------- | :------- | 
| `SVM` | `76.62%` | `85.27%`
| `XGBoost` | `89.08%` | `95.25%`
| `Random Forest` | `96.02%` | `99.55%`
| `Naive Bayes` | `76.11%` | `83.55%`
| `AdaBoost` | `79.79%` | `86.93%`
| `Logistics Regression` | `78.57%` | `85.38%`



## Explainable AI

#### LIME and SHAP was used to explain model's output. 


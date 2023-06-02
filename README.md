
# Student Performance Analysis using Machine Learning and Explainable AI

This project aims to analyze student performance based on their academic results from the previous and current years. Different ML algorithms were with XAI methods like LIME and SHAP were used to explain model output. 

## Dataset
The dataset was collected from https://rdcu.be/ddA5x. There are three different classes of data presented here. But we created our own three dataset classes for a better balance between the data. 

#### Table: Data distribution
| **Data Ragne** | **Class Name** | **Data Size**
| :-------- | :------- | :------- 
| >=83 | 0 | 522
| >=79 & <=82.99 | 1 | 547
| <79 | 2 | 477

## Model Accuracy
Differnt ML algorithems were used to measure the accuracy, precision, recall and f1-score of the model. Among all of them SVM gave the better result after doing hyperparamter tunning using random search. 

#### Table: Model Accuracy
| **Model** | **Accuracy** | **F1 Score** | **Marco AVG F1 Score**
| :-------- | :------- | :-------- | :------- 
| Random Forest  | 0.78 | 0.84 | 0.78
| XGBoost | 0.88 | 0.89 | 0.88
| SVM | 0.97 | 0.99 | 0.97
| Naive Bayes | 0.61 | 0.66 | 0.59
| AdaBoost | 0.87 | 0.89 | 0.87
| Logistic Regression | 0.93 | 0.96 | 0.93
| Descision Tree | 0.63 | 0.73 | 0.63

## XAI

We have used LIME and SHAP to expalin model's output.

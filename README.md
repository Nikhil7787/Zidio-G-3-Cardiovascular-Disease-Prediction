# Cardiovascular-Disease-Prediction
### **( Zidio Development Group-3 )** 
Welcome to the official repository for the "Cardiovascular Disease Prediction" project developed by the Zidio Development team. This project aims to utilize machine learning techniques to predict the likelihood of cardiovascular diseases in individuals, facilitating early detection and preventive measures. </br>


## Cardiovascular Disease Prediction Model
### Overview
This project aims to predict the presence or absence of cardiovascular disease based on various demographic, physical, and medical factors. We have developed an initial machine learning model using the provided dataset and evaluated its performance. The README provides an overview of the model's current performance, our plans for improving accuracy, and our intentions to further develop and deploy the model.</br>

## Basic info on data 

**Breakdown of the columns:** </br>

id: Identifier for each individual. </br>
age: Age of the individual in days. </br>
gender: Gender of the individual (1 for female, 2 for male). </br>
height: Height of the individual in centimeters. </br>
weight: Weight of the individual in kilograms. </br>
ap_hi: Systolic blood pressure. </br>
ap_lo: Diastolic blood pressure. </br>
cholesterol: Cholesterol level (1: normal, 2: above normal, 3: well above normal). </br>
gluc: Glucose level (1: normal, 2: above normal, 3: well above normal). </br>
smoke: Whether the individual smokes or not (0 for non-smoker, 1 for smoker). </br>
alco: Whether the individual consumes alcohol or not (0 for non-drinker, 1 for drinker). </br>
active: Whether the individual engages in regular physical activity or not (0 for inactive, 1 for active). </br>
cardio: Target variable indicating whether the individual has cardiovascular disease (0 for no disease, 1 for disease). </br>

Current Model Performance </br>
The initial machine learning model achieved the following results on the evaluation dataset: </br>
<br>
```
Accuracy: 0.7125714285714285
Classification Report:
              precision    recall  f1-score   support

           0       0.71      0.72      0.72      6988
           1       0.72      0.70      0.71      7012

    accuracy                           0.71     14000
   macro avg       0.71      0.71      0.71     14000
weighted avg       0.71      0.71      0.71     14000
```
<br>
<br>

### Plans for Improvement 
While the initial model shows promising results, we acknowledge that there is room for improvement. We plan to focus on the following areas to enhance the model's accuracy and overall performance: </br>

1.	Feature Engineering: Explore additional features and transformations to capture more information from the data. </br>
2.	Hyperparameter Tuning: Optimize the parameters of the chosen machine learning algorithm to maximize performance. </br>
3.	Ensemble Methods: Experiment with ensemble methods to combine multiple models for improved predictions. </br>
4.	Addressing Class Imbalance: Implement techniques to handle class imbalance if necessary. </br>
5.	Cross-Validation: Perform cross-validation to ensure the model's generalization ability and stability. </br>
6.	Further Data Exploration: Conduct deeper analysis of the data to uncover additional patterns and relationships. 


### Future Work
Once we have improved the model's accuracy and robustness, our next steps will include:</br>

Deployment: Deploying the model into a production environment where it can be used for real-time predictions. 

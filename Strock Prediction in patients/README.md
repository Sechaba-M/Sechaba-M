# Stroke Prediction

![im](Sechaba-M-Projects/Images/dataset-card.jpg)

### Overview
This repository contains a machine learning project focused on predicting the likelihood of stroke occurrence in patients based on various parameters. The project utilizes a dataset comprising features such as gender, age, hypertension, heart disease, marital status, work type, residence type, average glucose level, BMI, and smoking status to build a predictive model.

### Dataset
The dataset used in this project consists of the following parameters:
- Gender: The gender of the patient (Male, Female, or Other)
- Age: The age of the patient in years
- Hypertension: Whether the patient has hypertension (1 if true, 0 if false)
- Heart Disease: Whether the patient has heart disease (1 if true, 0 if false)
- Ever Married: Marital status of the patient (Yes or No)
- Work Type: Type of work the patient is engaged in (Private, Self-employed, Govt job, children, or Never worked)
- Residence Type: Type of residence of the patient (Urban or Rural)
- Average Glucose Level: The average glucose level in the patient's blood
- BMI: Body Mass Index (weight in kg / (height in m)^2)
- Smoking Status: Smoking status of the patient (formerly smoked, never smoked, or smokes)

### Methodology
1. **Data Preprocessing**: The dataset undergoes preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features.
2. **Feature Selection**: Relevant features are selected based on their importance for stroke prediction.
3. **Model Building**: Various machine learning algorithms such as logistic regression, decision trees, random forests, and gradient boosting are trained and evaluated to identify the best-performing model.
4. **Model Evaluation**: The performance of each model is assessed using evaluation metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
5. **Model Deployment**: The selected model is deployed for predicting stroke likelihood in new patient data.

### Usage
To use this project, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Run the Jupyter Notebook or Python script provided in the repository to train the model and make predictions.




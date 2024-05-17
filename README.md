# Diabetes Health Prediction Project 

![image](Images/medium.jpg)

**Context**

Diabetes is among the most prevalent chronic diseases in the United States, impacting millions of Americans each year and exerting a significant financial burden on the economy. Diabetes is a serious chronic disease in which individuals lose the ability to effectively regulate levels of glucose in the blood, and can lead to reduced quality of life and life expectancy. After different foods are broken down into sugars during digestion, the sugars are then released into the bloodstream. This signals the pancreas to release insulin. Insulin helps enable cells within the body to use those sugars in the bloodstream for energy. Diabetes is generally characterized by either the body not making enough insulin or being unable to use the insulin that is made as effectively as needed.

Complications like heart disease, vision loss, lower-limb amputation, and kidney disease are associated with chronically high levels of sugar remaining in the bloodstream for those with diabetes. While there is no cure for diabetes, strategies like losing weight, eating healthily, being active, and receiving medical treatments can mitigate the harms of this disease in many patients. Early diagnosis can lead to lifestyle changes and more effective treatment, making predictive models for diabetes risk important tools for public and public health officials.

The scale of this problem is also important to recognize. The Centers for Disease Control and Prevention has indicated that as of 2018, 34.2 million Americans have diabetes and 88 million have prediabetes. Furthermore, the CDC estimates that 1 in 5 diabetics, and roughly 8 in 10 prediabetics are unaware of their risk. While there are different types of diabetes, type II diabetes is the most common form and its prevalence varies by age, education, income, location, race, and other social determinants of health. Much of the burden of the disease falls on those of lower socioeconomic status as well. Diabetes also places a massive burden on the economy, with diagnosed diabetes costs of roughly $327 billion dollars and total costs with undiagnosed diabetes and prediabetes approaching $400 billion dollars annually.

**Overview**
This project aims to predict the prognosis and likelihood of developing cardiovascular events, hyperglycemic episodes exacerbated by infection, and the likelihood of catching communicable diseases in diabetic patients. By identifying key factors influencing these outcomes, the project aims to assist healthcare professionals in providing targeted interventions and improving patient outcomes.

**Methodology**
The project follows a data science approach, encompassing data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and interpretation. The methodology involves the following steps:

Data Preprocessing: Handling missing values, data cleaning, and normalization.
Exploratory Data Analysis (EDA): Analyzing the distribution of variables, identifying correlations, and gaining insights into the dataset.
Feature Engineering: Creating new features, selecting relevant features, and transforming variables as necessary.
Model Training: Developing machine learning models to predict the target outcomes.
Model Evaluation: Assessing model performance using appropriate metrics such as accuracy, precision, recall, and F1-score.
Interpretation: Interpreting model results to understand the importance of features and their impact on predictions.
Key Findings
The project identifies several key findings related to the prognosis and likelihood of developing cardiovascular events, hyperglycemic episodes, and catching communicable diseases in diabetic patients. These findings include:

Significant predictors influencing each outcome.
Correlations between various factors and the likelihood of specific events.
Insights into the relative importance of different features in predicting outcomes.
Future Directions
Future directions for this project may include:

Refinement of predictive models using advanced machine learning techniques.
Integration of real-time patient data for personalized predictions.
Collaboration with healthcare professionals to deploy the model in clinical settings.
Continuous monitoring and updating of the model to adapt to changing healthcare landscapes and patient populations.

**Content**

The Behavioral Risk Factor Surveillance System (BRFSS) is a health-related telephone survey that is collected annually by the CDC. Each year, the survey collects responses from over 400,000 Americans on health-related risk behaviors, chronic health conditions, and the use of preventative services. It has been conducted every year since 1984. For this project, a csv of the dataset available on Kaggle for the year 2015 was used. This original dataset contains responses from 441,455 individuals and has 330 features. These features are either questions directly asked of participants, or calculated variables based on individual participant responses.

**This dataset contains 3 files:**

diabetes _ 012 _ health _ indicators _ BRFSS2015.csv is a clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_012 has 3 classes. 0 is for no diabetes or only during pregnancy, 1 is for prediabetes, and 2 is for diabetes. There is class imbalance in this dataset. This dataset has 21 feature variables
diabetes _ binary _ 5050split _ health _ indicators _ BRFSS2015.csv is a clean dataset of 70,692 survey responses to the CDC's BRFSS2015. It has an equal 50-50 split of respondents with no diabetes and with either prediabetes or diabetes. The target variable Diabetes_binary has 2 classes. 0 is for no diabetes, and 1 is for prediabetes or diabetes. This dataset has 21 feature variables and is balanced.
diabetes _ binary _ health _ indicators _ BRFSS2015.csv is a clean dataset of 253,680 survey responses to the CDC's BRFSS2015. The target variable Diabetes_binary has 2 classes. 0 is for no diabetes, and 1 is for prediabetes or diabetes. This dataset has 21 feature variables and is not balanced.

## Dataset
The dataset used in this project contains clinical and demographic information of diabetic patients, including but not limited to:
- Diabetes_binary: Binary indicator for diabetes diagnosis.
- HighBP: Binary indicator for high blood pressure.
- HighChol: Binary indicator for high cholesterol.
- CholCheck: Frequency of cholesterol check.
- BMI: Body Mass Index (numeric).
- Smoker: Binary indicator for smoking status.
- Stroke: Binary indicator for stroke history.
- HeartDiseaseorAttack: Binary indicator for history of heart disease or heart attack.
- PhysActivity: Level of physical activity.
- Fruits: Frequency of fruit consumption.
- Veggies: Frequency of vegetable consumption.
- HvyAlcoholConsump: Binary indicator for heavy alcohol consumption.
- AnyHealthcare: Access to any healthcare.
- NoDocbcCost: Ability to afford healthcare.
- GenHlth: General health status.
- MentHlth: Mental health status.
- PhysHlth: Physical health status.
- DiffWalk: Difficulty walking.
- Sex: Gender of the patient.
- Age: Age of the patient.
- Education: Level of education.
- Income: Income level.

## Possible Analysis on Parameters
1. **Correlation Analysis**: Explore correlations between various parameters and the likelihood of developing specific health conditions. For example, investigate the correlation between BMI and the risk of cardiovascular events.

2. **Feature Importance**: Determine the importance of different parameters in predicting health outcomes. Utilize techniques such as feature importance plots or permutation importance to identify key predictors.

3. **Risk Factor Identification**: Identify parameters that significantly contribute to the risk of adverse health events. This could involve fitting logistic regression models or decision trees to assess the odds ratios or feature importances of each parameter.

4. **Population Segmentation**: Explore how different demographic and clinical parameters interact to influence health outcomes. Conduct clustering analysis or stratified analysis to identify distinct patient subgroups with varying risk profiles.

5. **Temporal Analysis**: Investigate how health parameters change over time and their impact on health outcomes. Utilize time-series analysis techniques to assess trends and associations between variables.

## Dependencies
The project relies on the following libraries:
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Usage
To reproduce the results of this project, follow these steps:
1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebooks in the specified order to execute the data preprocessing, EDA, feature engineering, model training, and evaluation.

## Contributors
- Sechaba Machaba

## License


---

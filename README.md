# CS210-Introduction-to-Data-Science
Group Project done for the CS210 Introduction to Data Science Course in Sabancı University Spring 2022

Data science spans a large variety of disciplines and requires a collection of skills. This course is intended to tour the basic techniques of data science from manipulation and summarizing the important characteristics of a data set, basic statistical modeling, web programming and visualization.

---

Motivation of the project and other group members contributed to the project can be found in the proposal report. 

Expected steps from the group were:

## Exploratory Data Analysis
- Visualize each attribute separately with respect to AHD (0: no disease, 1: disease)
- Visualize the relationship between some selected attributes and the final disease state (AHD: disease, no disease). For instance, you may choose [age, sex, Chol] as one attribute group and visualize against whether AHD is 0 or 1 (no disease/disease). Try to do this for several different attribute groups
- Analyze Chol, Fbs and ExAng values with respect to age and sex
- Analyze & visualize how each attribute changes with respect to age and sex
- Analyze & visualize the relationship between each attribute (without AHD) and chest pain 
- Analyze & visualize the relationship between two selected attributes, as well as whether they would lead to disease or not. That is, divide all the attributes into groups of two, and for each group, analyze whether that combination leads to disease or not. Consider all possible combinations.
- Introduction of at least four new features from additional datasets and visual explanations of them
- For both existing and new features, and usage of spatial visualization examples (as much as possible) are expected.

## Statistical Analysis & Hypothesis Testing
- Statistical tests to check whether the values of chest pain, RestBP and Chol contribute to heart disease or not. 
- Statistical tests to check whether age and sex contribute to heart disease or not
- Statistical tests to check if significant differences exist between age groups and sex that suffer from heart disease
- Statistical tests to check how all those attributes contribute to heart disease
- Utilizing at least four new features using extra datasets in hypothesis testing

## Machine Learning
- Prediction of heart disease given values of age, sex, chest pain and RestBP
- Perform hyper-parameter tuning to increase model performance
- Students are expected to introduce new approaches to their selected model in A to investigate their effects on model performance
- Students are expected to utilize at least two different machine learning models for prediction and compare their performance
- Build a system that can predict whether a person could suffer from heart disease when provided with values of those attributes. 
- Students should clearly present their reason for selecting that particular method
- Students are also expected to handle with scenarios of missing attributes. That is, when predicting, the provided personal data may have some missing attributes compared to the original training data
- Utilize at least four new features using additional datasets in machine learning models

---

## About Data

Dataset used for the project can be accessed from: [https://www.kaggle.com/meetnagadia/heart-disease](https://www.kaggle.com/meetnagadia/heart-disease)

Records of Patients having Heart Disease.
This file contains the records of patients with their health report .

There are 13 attributes:

- Age: Age (in years)
- Sex: gender (1 = male; 0 = female)
- ChestPain: Chest Pain type
-- typical angina (all criteria present)
-- atypical angina (two of three criteria satisfied)
-- non-anginal pain (less than one criteria satisfied)
-- asymptomatic (none of the criteria are satisfied)
- Restbps: Resting Blood pressure (in mmHg, upon admission to the hospital)
- Chol: serum cholesterol in mg/dL
- Fbs: fasting blood sugar > 120 mg/dL (likely to be diabetic) 1 = true; 0 = false
- RestECG: Resting electrocardiogram results
-- Value 0: normal
-- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
-- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
- MaxHR: Greatest number of beats per minute your heart can possibly reach during all-out strenuous exercise.
- Exang: exercise induced angina (1 = yes; 0 = no)
- Oldpeak: ST depression induced by exercise relative to rest (in mm, achieved by subtracting the lowest ST segment points during exercise and rest)
- Slope: the slope of the peak exercise ST segment, ST-T abnormalities are considered to be a crucial indicator for identifying presence of ischaemia
-- Value 1: upsloping
-- Value 2: flat
-- Value 3: downsloping
- Ca: number of major vessels (0-3) colored by fluoroscopy. Major cardial vessels are as goes: aorta, superior vena cava, inferior vena cava, pulmonary artery (oxygen-poor blood --> lungs), pulmonary veins (oxygen-rich blood --> heart), and coronary arteries (supplies blood to heart tissue).
- AHD: 0 = normal; 1 = fixed defect (heart tissue can't absorb thallium both under stress and in rest); 2 = reversible defect (heart tissue is unable to absorb thallium only under the exercise portion of the test)
- AHD: 0 = no disease, 1 = disease





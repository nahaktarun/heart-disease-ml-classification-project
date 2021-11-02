# heart-disease-ml-classification-project

Predicting Heart Disease Using machine learning¶
This notebook is using various python based Machine Learning and Data Science libraries in an attempt to build a machine learning model capable of Predicting wheather or not someone has heart disease based on their medical attributes

Following steps are taken to solve this problem:

Problem definition
Dat
Evaluation
Features
Models
Experimentation
1. Problem Defination
In a statement:

Given clinical parameter about a patient, can we predict wheather or not they have heart disease or not ?

2. Data
The original data came from the Cleaveland data from the UCI Machine LearningRepository.https://archive.ics.uci.edu/ml/datasets/heart+disease

There is also a version of it avilable in kaggle. https://www.kaggle.com/ronitf/heart-disease-uci

3. Evaluation
If we can reach 95% accuracy at predicting wheather or not a patient has heart disease during the proof of concept, we'll pursue the project.

4. Features
This is where you'll get different information about each of the features in your data.

Create data Dictionary

age - age in year
sex - (1 for male , 0 for female)
chest pain type (4 values)

0: Typical angina: chest pain related decreases blood supply to the heart
1: Atypical angina: chest pain not related to heart
2: Non- anginal pain: typically esophageal spasms ( non heart related)
3: Asysmtomatic: cheast pain not showing signs of disease
resting blood pressure

serum cholestoral in mg/dl
fasting blood sugar > 120 mg/dl
resting electrocardiographic results (values 0,1,2)
maximum heart rate achieved
exercise induced angina
oldpeak = ST depression induced by exercise relative to rest
the slope of the peak exercise ST segment
number of major vessels (0-3) colored by flourosopy
thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

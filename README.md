Introduction¶

According to World Health Organisation (WHO), stroke are the second leading cause of death and the third leading cause of disability globally. Stroke is the sudden death of some brain cells due to lack of oxygen when the blood flow to the brain is lost by blockage or rupture of an artery to the brain, it is also a leading cause of dementia and depression.

Nearly 800,000 people in the United States suffer from a stroke each year, with about three in four being first-time strokes. 80% of the time these strokes can be prevented, so putting in place proper education on the signs of stroke is very important. In this study, various models are build to predict if a person is subjected to stroke using available predictors

Overall Concept

The objective of this study is to construct a prediction model for predicting stroke and to assess the accuracy of the model.  We will explore seven different models to see which produces reliable and repeatable results. The models are: Decision Tree, Logistic Regression, Random Forest, Support Vector Machine, K Nearest Neighbour, Naive Bayes and KMeans Clustering. From the prediction outcome of the models, the best performance model will undergo the cross validation process to evaluate its repeatability. 

Data Source

A population of 5110 people are involved in this study with 2995 females and 2115 males.
The dataset for this study is extracted from Kaggle data respositories (https://www.kaggle.com/datasets) to predict whether a patient is likely to get stroke based on the following attribute information:

    1.  id                : unique identifier
    2.  gender            : "Male", "Female" or "Other"
    3.  age               : age of the patient
    4.  hypertension      : 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
    5.  heart_disease     : 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
    6.  ever_married      : "No" or "Yes"
    7.  work_type         : "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
    8.  Residence_type    : "Rural" or "Urban"
    9.  avg_glucose_level : average glucose level in blood
    10. bmi               : body mass index
    11. smoking_status    : "formerly smoked", "never smoked", "smokes" or "Unknown"
    12. stroke            : 1 if the patient had a stroke, 0 the patient do not have a stroke

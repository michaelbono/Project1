# Project1
Stroke Prediction - Logistic Regression

Michael Bono


This project provides an analysis of a health dataset related to stroke victims, an analysis of the features, and creation of a logistic model to predict stroke occurrences.


**Data Source**

This data was sourced from Kaggle at this link: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset/version/1.


**What's Included In This Repository **

- Project1.ipynb (Jupyter notebook consisting of the full code and analysis)
- healthcare-dataset-stroke-data.csv (source file from Kaggle containing data about patients and whether or not they had a stroke)
- This README.md file (a brief description and summary of the project, libraries used, methodology and motivation)


**Motivation**

I chose to predict likelihood of stroke as one of my loved ones had a stroke last year. While they are doing fine now, it was a very scary time for the family. I wanted to better understand the datapoints behind strokes and how the likelihood can be reduced. This dataset, while not exhaustive, provided many of the key factors I wanted to analyze in relation to stroke likelihood. I also wanted to test my skills experimenting with logistic regression in Python as well as scoring the model, which is not as easy as using R squared is for a linear model.


**Methodology**

This analysis followed the CRISP-DM method to gather, assess, clean, analyze, model, and visualize the data.


**Questions Asked**
1. People with which lifestyle choices (such as smoking, marital status, work type and place of residence) suffer strokes most often?
2. How much of an impact do pre-existing health conditions have on likelihood of stroke?
3. How much does a single year increase likelihood of stroke?


**Libraries Used**

- numpy
- pandas
- math
- matplotlib
- sklearn
- seaborn


**Summary of Results**

Through this process, we were able to answer our questions:

1. People with which lifestyle choices (such as smoking, marital status, work type and place of residence) suffer strokes most often?
- It appears that individuals who were self employed, married, and formerly smoked all had more strokes than individuals from other categories.
2. How much of an impact do pre-existing health conditions have on likelihood of stroke?
- Hypertension increases likelihood by 65%. Heart disease increases likelihood by 6%.
3. How much does a single year increase likelihood of stroke?
- Each year, stroke likelihood increases by e^0.083155, or 8.6% higher than the year before.

This analysis could be expanded to include a larger dataset with more observations of stroke occurrences, additional data points around health including cholesterol and stress levels, as well as incorporation of SMOTE algorithms to increase presence of the minority of the class.

**Thanks**

Thank you for checking out this project! I hope you learned something interesting.

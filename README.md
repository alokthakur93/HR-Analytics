![](https://img.shields.io/github/followers/alokthakur93?label=Follow%40alokthakur93&style=social)
![](https://img.shields.io/github/forks/alokthakur93/HR-Analytics?label=Fork&style=social)
![](https://img.shields.io/github/stars/alokthakur93/HR-Analytics?style=social)
![](https://img.shields.io/github/watchers/alokthakur93/HR-Analytics?style=social)
![](https://img.shields.io/github/issues/alokthakur93/HR-Analytics)
![](https://img.shields.io/github/repo-size/alokthakur93/HR-Analytics)
![](https://img.shields.io/github/languages/code-size/alokthakur93/HR-Analytics)

# HR Analytics : Job Change of Data Scientists

## Project Overview : 
* Designed a flask web app which predicts whether a person is looking for job change or will work for the company.
* Created different visualizations which helped in understanding the data more deeply.
* Done lot of pre-processing of data like encoding categorical variables etc.
* Performed model creation and model analysis to find out best suited model.
* Developed a client facing web app using Flask and deployed it on Heroku.

## Deployment Link : https://job-change-prediction.herokuapp.com/

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, imblearn, flask, pickle, plotly.

**For Web Framework Requirements:**  ```pip install -r requirements.txt```  

## Business Problem / Objective:
A company which is active in Big Data and Data Science wants to hire data scientists among people who successfully pass some courses which conduct by the company. Many people sign up for their training. Company wants to know which of these candidates are really wants to work for the company after training or looking for a new employment because it helps to reduce the cost and time as well as the quality of training or planning the courses and categorization of candidates. Information related to demographics, education, experience are in hands from candidates sign up and enrollment.

## Dataset details:
* The dataset was taken from Kaggle. To see the dataset visit this link: https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists

## Exploratory Data Analysis (EDA):
* Created different visualizations like count plot, scatter plot, Box plot to extract insights.

### Data Pre-processing:
* Done Label Encoding of categorical variables
* Imputed missing values using mode
* Up sampled the data using SMOTE because data set was imbalanced
* Normalized all the values

## Model Building:

After doing pre-processing of data, I split the data into train set and test set with test size of 30%.

![curve](https://raw.githubusercontent.com/alokthakur93/HR-Analytics/main/AUC_curve.PNG)

![cm](https://raw.githubusercontent.com/alokthakur93/HR-Analytics/main/heat%20map.PNG)

## Model evaluation:
* XGboost on normal data gives less miss-classification rate means it is correctly identifying candidates who will work for company
* It also have high specificity or True Negative rate means identifying those who are looking for job change
* Increased precision value when compared to other model


![](https://forthebadge.com/images/badges/made-with-python.svg)
 [<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org)
 ![](https://miro.medium.com/max/732/1*4krsnV59DxyWBFCtbUmUiw.jpeg)

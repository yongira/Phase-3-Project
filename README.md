# CHURN IN TELECOMS ANALYSIS
## 1.0 Overview
Churn analysis in the telecom industry aims to identify and reduce customer loss. This involves using data analytics, machine learning, and predicitive modeling to understand customer behaviour, detect early warning signs of churn, and create targeted plans. 
The target stakeholders include:

1. Executive Leadership - to align churn analysis outcomes with strategic business goals and customer retention strategies.
   
2. Customer Experience/Support Teams - to design and implement initiatives based on churn insights to improve satisfaction and loyalty, while proactively addressing issues that contribute to churn.

3. Sales and Marketing Teams - to craft targeted campaigns aimed at retaining at risk customers.

## 2.0	Business Understanding
It is important to track churn because a high churn rate can negatively impact a company's revenue and indicate dissatisfaction with their product or service.
### 2.1. Industry Context
In the telecom industry, external factors can play a significant role in influencing churn such as new competitiors, promotions and pricing, product differenciation, technological advancement, regulatory changes, economic conditions, social and cultural trends, natural disasters, global trends, customer preferrences for bundling, consumer awareness and education. Understanding these factors can help telecom companies adjust their strategies, improve customer retention, and better anticipate customer needs. To reduce churn, companies must stay competitive, adapt to technology trends, and respond effectively to both global and local external events.

### 2.2. Business Objective
The goal of churn analysis is to identify and anticipate customers who may churn as soon as possible. This can help the company rectify customer issues and satisfy their needs. The objectives we can address with this analysis could be to understand why customers leave the service and help the telecom company improve customer retention.

## 3.0	Data Sources and Understanding
For this project, we work with "Churn in Telecom's dataset" which contains the following information to help predict churn, e.g.,:

1. State - A two letter code for the customer's state of residence.

2. Account Length - The number of months the customer has been with the current provider.

3. Churn - A boolean variable that indicates the class of the sample.

Key Questions for Data Understanding:

- What is the overall churn rate?

- How does usage behaviour correlate with churn? Do customers who use less service (e.g., fewer calls or low data usage) tend to churn more?

- Is there a correlation between customer support interactions and churn? Do customers who contact support more often tend to churn more?

- Is there a relationship between spending or payment type and churn? Are high-spending customers less likely to churn?

- Are there any strong correlations between features? For example, account length might be negatively correlated with churn, or certain service features might have a strong relationship with churn likelihood.

## 4.0	Data Preparation
Steps:
  1.	Backing up of the data to avoid accidental loss during the data cleaning and loading the data.
  
  2.	Explore and Preprocess the Data. Use of .info() and .describe() to understand the dataset structure and summary statistics. Also, visualize data with histograms, boxplots, and correlation heatmaps to identify patterns.

  3.	We then identify missing data points (NULL or NaN values) and decide on how to handle them.
 
  4.	Convert categorical variables to numeric using one-hot encoding or label encoding.

  6.	Define Features and Target, Separating the independent variables (features) and dependent variable (target)

  7.	Split the data into training and test sets.
 
## 5.0	Modelling/ Analysis
The analysis includes use of classification algorithms like Logistic Regression and Random Forest to uncover insights. The models are then trained on the training data and evaluated on the test data.

Logisitics regression - 

### 5.1. Visualizations

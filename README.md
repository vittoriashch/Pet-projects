# Pet-projects
Here I post my pet projects in R and Python:)


# [Movie Recommendation System with Network and Sentiment Analysis](https://github.com/vittoriashch/Pet-projects/tree/main/R_projects)
This project aims to create an effective movie recommendation system using a combination of network analysis, text and sentiment analysis, and recommendation algorithms. The goal is to predict user preferences and suggest films tailored to their interests.

***Key Features:***

### Network Analysis : 
Identifies communities within films and suggests movies for users without clear preferences.

### Sentiment Analysis : 
Analyzes movie reviews to enhance recommendations by understanding user sentiment.

### Recommendation Systems : 
Implements Collaborative Filtering and Content-Based approaches to recommend movies.
This project evaluates the effectiveness of these methods and provides insights through data visualization.

# [Oil price prediction with the use of DL](https://github.com/vittoriashch/Pet-projects/blob/main/Python_projects/Oil_price_prediction%20(3).ipynb)

This project is dedicated to the development and deployment of several neural networks aimed at predicting Brent crude oil prices. The primary goal is to create a model capable of forecasting price fluctuations based on key factors influencing the current energy market and economic conditions.

## Objectives
The project aims to:
* Predict Brent Oil Prices: Utilize modern machine learning techniques to analyze and forecast price movements in the oil market.
* Analyze Influencing Factors: Investigate various economic and energy indicators, such as supply and demand, geopolitical events, regulatory changes, and other external factors that may impact prices.
* Optimize Models: Apply different neural network architectures, such as LSTM (Long Short-Term Memory) and RNN (Recurrent neural network), to achieve maximum prediction accuracy.

## Technologies

This project utilizes the following technologies:

- **Python**: The primary programming language.
- **Jupyter Notebook**: For interactive data analysis and visualization.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Tensorflow**: For deep learning algorithms and model evaluation.
- **Scikit-learn**: For machine learning algorithms and model evaluation.
- **Matplotlib**: For data visualization.
- **Yahoo Finance API**: For data gathering 

# [Causal Inference with Double Machine Learning on Tax Policy Simulation](https://github.com/vittoriashch/Pet-projects/blob/main/Python_projects/Double%20ML%20project.ipynb)

This project is a simulation-based exploration of the causal effects of tax policy on government revenues using Double Machine Learning (Double ML) and related causal inference techniques. It combines synthetic data generation, classification and regression modeling, and causal effect estimation to understand the impact of high versus low tax rates in complex economic environments.

## Objectives

* Simulate a realistic economic environment with policy-relevant variables such as fiscal deficit, tax progressivity, shadow economy size, inequality, and fiscal culture.
* Estimate causal effects of high tax rates on tax revenues using multiple approaches, including regression models, classification models, and state-of-the-art machine learning estimators.
* Compare treatment effect estimation methods, such as ATE, LATE, and CATE, under different assumptions using true potential outcomes and real-model predictions.


---

## Key Features

### Data Simulation & Causal Structure

- Designed nonlinear and heteroskedastic functional forms for tax revenue under treatment/control.
- Incorporated latent confounders to simulate real-world endogeneity.
- Modeled treatment assignment with logistic probabilities influenced by both observed and unobserved covariates.
- Visualized DAG structure and correlation matrix of features.

###  Classification Models

- Applied classifiers: `Gradient Boosting`, `Random Forest`, `KNN`, `Naive Bayes`, `Logistic Regression`.
- Performed hyperparameter tuning via cross-validation using accuracy and F1-score.
- Assessed models using ROC-AUC, profit-based confusion matrices, and threshold optimization.

### Regression Analysis

- Compared `Linear Regression`, `Random Forest`, and `XGBoost` to model tax revenue.
- Used RMSE and MAPE for evaluation across training, test, and cross-validation splits.
- Identified XGBoost as the most robust model for predicting complex patterns in tax revenue.

### Causal Inference

- Estimated:
  - **ATE (Average Treatment Effect)**
  - **LATE (Local Average Treatment Effect)**
  - **CATE (Conditional Average Treatment Effect)**
- Applied causal estimation techniques:
  - OLS regression
  - IPW (Inverse Probability Weighting)
  - Doubly Robust Estimation
  - Double Machine Learning (DML)
- Implemented learning algorithms for CATE estimation:
  - `S-Learner`, `T-Learner`, `X-Learner`, `R-Learner`, `Causal Transformation`
- Evaluated predictive accuracy using MSE and pseudo-outcome metrics.

---

## Technologies Used

- **Python**: core programming language
- **pandas**, **NumPy**, **SciPy**: data manipulation & simulation
- **scikit-learn**, **XGBoost**, **EconML**, **DoWhy**: modeling & causal inference
- **Matplotlib**, **Seaborn**: data visualization
- **Jupyter Notebook**: interactive coding environment

---

## Economic Insights

- Causal analysis highlights the role of **fiscal culture** and **inequality** in moderating treatment effects.
- Useful for evaluating the **economic impact of tax reforms** and informing public policy and business decisions.

---

## References

- Laffer, A. (1981). *The Laffer Curve: Past, Present, and Future*
- Goolsbee, Hall, & Katz (1999). *Behavioral Responses to Tax Policy*
- Trabandt & Uhlig (2009). *Optimal Taxation in EU and US*
- Chernozhukov et al. (2018). *Double/Debiased Machine Learning for Treatment and Structural Parameters*




# [Probability of Default](https://github.com/vittoriashch/Pet-projects/blob/main/Python_projects/Probability%20of%20default%20pet-project-4.ipynb)

This project is aimed to implement a predictive model to assess the probability of loan default using machine learning techniques. It analyzes various financial and personal characteristics of borrowers to predict whether they will be able to meet their loan obligations.

The Exploratory Data Analysis (EDA) section is complete and ready for you to explore and investigate. I'm currently finalizing the machine learning and estimation components, so stay tuned for updates!

## Table of Contents

- [Description](#description)
- [Technologies](#technologies)
- [Data](#data)
- [Model Evaluation](#model-evaluation)

## Description

The primary goal of this project is to predict the likelihood of a borrower defaulting on a loan. The project encompasses several key stages:

1. **Data Collection**: Gathering relevant datasets that contain borrower information.
2. **Data Preparation**: Cleaning and preprocessing the data to ensure it is ready for analysis.
3. **Exploratory Data Analysis (EDA)**: Visualizing and analyzing the data to identify patterns and insights.
4. **Model Training**: Using various machine learning algorithms to train models on the dataset.
5. **Model Evaluation**: Assessing the performance of the models using appropriate metrics.

## Technologies

This project utilizes the following technologies:

- **Python**: The primary programming language.
- **Jupyter Notebook**: For interactive data analysis and visualization.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Scikit-learn**: For machine learning algorithms and model evaluation.
- **Matplotlib**: For data visualization.
- **Seaborn**: For statistical data visualization.

## Data

This project uses [this Kaggle dataset](https://www.kaggle.com/datasets/wordsforthewise/lending-club)





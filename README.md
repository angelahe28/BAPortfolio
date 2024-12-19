# Portfolio Projects

In this section, I will list data analytics projects briefly describing the technology stack used to solve cases.

### Predicting High-Quality White Wines Using Machine Learning

**Code**:  [**Wine Quality Prediction**](https://github.com/angelahe28/BAPortfolio/blob/main/He_Angela_p1.ipynb)

**Goal**: To build a classification model capable of predicting whether a white wine will be judged as "high quality" based on its chemical properties, helping winemakers assess quality prior to judging events.

**Description**: This project leverages a dataset of white wines and their chemical properties to preduct whether a wine will be classified as "high quality" by professional judges. By analyzing features such as chlorides, sulfur dioxide levels, density, pH, and alchohol content, a decision tree model was used to classify wines into high-quality and non-high-quality categories. This analysis provides actionable insights for the wine industry to refine production processes and focus on quality indicators.

**Skills**: Data Cleaning and Preparation, Exploratory Data Analysis (EDA), Feature Importance Analysis, Visualization and Reporting

**Technology**: Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn

**Results**: Developed a decision tree model with an accuracy of 85% and an F1-score of 0.83 in predicting wine quality. Identified alchohol content and total sulfur dioxide as the most influential predictors of wine quality. 

### Automobile Price Prediction Using Simple and Multivariate Regression

**Code**:  [**Automobile Price Prediction**](https://github.com/angelahe28/BAPortfolio/blob/main/CIS%20508%20HW%20%232-1.ipynb)

**Goal**: To build predictive regression models for estimating the Manufacturer Suggested Retail Price (MSRP) of automobiles based on their attributes. This projects aims to identify key variables influencing car prices and optimize model performance using forward and backward selection techniques.

**Description**: This project uses a dataset containing thousands of automobiles and their characteristics to predict their MSRP. Two simple regression models were trained using the most impactful features and their performances was compared. Forward and backward variable selection techniques were applied to build and refine multivariate regression models, identifying the best set of predictors to minimize SSE. 

**Skills**: Data Cleaning and Exploration, Simple and Multivariate Regression Analysis, Feature Selection (Forward/Backward), Model Evaluation (SSE, R²), Visualization

**Technology**: Python, Pandas, NumPy, Statsmodels, Seaborn

**Results**: Final multivariate regression model achieved R² = 0.85 and reduced SSE by 40% compared to the baseline. As horsepower increases, MSRP tends ro rise, indicating that performance-oriented vehicles yield higher prices. Heavier cars often correlate with premium features and materials leading to higher prices. A combination of performance, size, and fuel efficiency contributes to overall MSRP variability. 

By understanding the factors that drive MSRP, manufacturers can refine their pricing models to better reflect customer demand and market trends. Understanding which attributes resonates most with pricing can guide targeted advertising campaigns. For example, promoting fuel-efficienct cars in regions where fuel prices are generally higher may drive revenue and overall profitability.

**Additional Insights:** 

**Simple Regression Models**:
- **Feature #1**: Horsepower
  * R² = 0.67: Horsepower alone explains 67% of the variance in MSRP.
  * SSE = 25,000: Moderate error in predicting MSRP using horsepower.
- **Feature #2**: Curb Weight
  * R² = 0.62: Curb weight explains 62% of the variance in MSRP.
  * SSE = 27,000: Slightly higher error compared to horsepower.
 
**Forward/Backward Selection**:
- Selected features for the multivariate regression model: Horsepower, Engine Size, Curb Weight, and Fuel Efficiency.
  * R² = 0.85: The final model explains **85%** of the variance in MSRP, significantly improving predictive accuracy.
  * SSE = 15,000: SSE was reduced by **40%**, demonstrating a better fit.

###Predicting Hotel Booking Cancellations with Machine Learning

**Code**:  [**Hotel Booking Cancellation Analysis**](https://github.com/angelahe28/BAPortfolio/blob/main/CIS_508_Hands_on_Exercise_4%20(3).ipynb)

**Project Overview**: In this project, I developed a machine learning model to predict hotel booking cancellations, enabling improved operational planning and customer retention stategies. By analyzing over 119,000 records of historical booking data, I explored multiple models including Logistic Regression, Random Forest, XGBoost, and kNN to determine the most accurate and actionable predictive framework. This project demonstrates my ability to analyze data, build predictive models, and translate findings into meaningful business recommendations.

**Goal**: To predict booking cancellations accurately and provide actionable insights for hotel management to optimize resource allocation, improve revenue forecasting, and enhance customer retention rates by identifying high-risk bookings.

**Skills*: Data Cleaning (address missing data, encode categorical variables, normalize features like lead time and booking changes), Exploratory Data Analysis (EDA), Logistic Regression, Random Forest, XG Boost, kNN, Hyperparameter Tuning (Grid Search for Random Forest and XG Boost)

Model	Accuracy	F1-Score	Precision	Recall
Logistic Regression	85%	0.83	0.82	0.84
Random Forest	88%	0.86	0.85	0.87
XGBoost (Best Model)	90%	0.88	0.87	0.89
k-Nearest Neighbors	83%	0.80	0.79	0.81






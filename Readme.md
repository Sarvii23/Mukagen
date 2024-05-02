# Master of Science Business Analytics - Capstone - Home Credit Default Risk Prediction

## Introduction
Home Credit operates across nine countries, offering various types of loans to individuals who may have limited or no credit history but possess steady incomes. These individuals are often underserved by traditional lenders. Home Credit aims to use data on borrower behavior to create predictive models that assess risk and determine appropriate loan amounts, enabling them to provide financial assistance responsibly while helping customers achieve their goals regardless of their credit history.

## Business Problem
Many potential borrowers that have insufficient or non-existent credit histories have trouble in accessing a secure loan and fall victim to untrustworthy moneylenders. Home Credit is working to broaden the financial inclusivity with the goal of providing a safe money lending experience to the populace which have insufficient or non-existent credit histories. Primarily, the challenge faced by Home Credit would be to determine the repayment abilities of such clients. 

## Project Objective
The primary goal of this project is to develop a predictive analytics system using supervised learning methods to assess the creditworthiness of loan candidates. The aim is to utilize a classification algorithm to forecast whether an applicant will meet their loan obligations or default. The target variable for this supervised classification model will be binary, indicating the applicant's ability to repay or not. The objective is to provide a reliable tool for financial institutions to make informed lending choices, ultimately minimizing default risks and optimizing their loan portfolios.

## Analytical Approach
In this predictive analytics project, we'll adopt a supervised learning approach to tackle the problem. We'll utilize a classification algorithm to predict whether a loan applicant will repay or default. Our model will incorporate various alternative data sources, such as telco and transactional data. The target variable for the supervised classification model will be binary, indicating whether the applicant is deemed capable of repayment or not.

## Solution
These notebooks will delve into the Exploration Data Analysis (EDA) of Home Credit default risk, encompassing data cleaning, explorations, hypothesis testing, and visualizations.

In this EDA, we'll utilize both the Application (Train/Test) dataset and the Bureau dataset to conduct hypothesis tests and clean the data, including analyzing transactional data from the Bureau dataset. Depending on the hypotheses, we'll visualize various plots, such as gender differences in default rates, the impact of income or credit sum on defaults, and how factors like client region, occupation, and family structure affect default rates.

Following the EDA, we'll build predictive models using the cleaned data to assess credit default risk. We'll focus on the target variable and employ various machine learning models, calculating metrics like accuracy and ROC values.

Our goal is to pinpoint the best-performing model based on Kaggle scores. We'll begin with Logistic regression and explore penalized regression like LASSO to address collinearity issues. Additionally, we'll investigate Random Forest, XGBoost, and Light XGBoost to gauge their efficacy in predicting credit default risk.

## Contribution
Contributor to the project initiated the Exploratory Data Analysis (EDA) by addressing missing values, exploring the dataset, and elucidating insights through hypothesis testing and visualizations. Contributed to tuning hyperparameters, identifying optimal combinations for each model to maximize predictive accuracy. Ensured alignment with business requirements by presenting and interpreting model confusion matrices to establish solutions. Additionally, focussed on implementing Light Gradient Boosting, documented the process in a notebook write-up, and conducted thorough evaluations of the models.

## Business Value
The model's ability to predict default rates enables Home Credit to proactively identify customers at risk of defaulting on their loans.
Modeling plays a pivotal role in mitigating the risk of non-performing assets, consequently bolstering the company's bottom line by minimizing losses attributed to defaults. Moreover, extending loans to underserved customers lacking credit history expands Home Credit's customer base and revenue streams, fostering inclusive growth and financial empowerment.
Embracing technology and machine learning in the financial sector not only drives business growth but also streamlines operations, enhancing efficiency and customer service. Through the optimized loan portfolio facilitated by the solution, Home Credit strategically allocates resources to applications with the highest expected returns relative to their associated risks, thereby maximizing profitability while maintaining a prudent risk profile.
Furthermore, enhanced profitability is achieved through improved risk assessment and portfolio optimization, enabling Home Credit to approve loans with favorable Risk-Adjusted Return on Capital (RAROC) values. This results in increased revenue generation while mitigating the adverse effects of defaults.

## Challenges
Dealing with missing values poses a significant challenge, requiring careful consideration regarding whether to impute them with measures like mean, median, or mode, or treat them as a separate category like 'None', for each column containing missing data.

Selecting an appropriate model is challenging due to high correlations between predictors and the risk of multicollinearity. It's crucial to choose models capable of handling these challenges effectively.

Prioritizing features was a major challenge due to the large volume of data from numerous files. This complexity made it difficult to determine which features to include in our predictive model during the feature engineering stage.

Resource constraints, such as limited computational power, presented challenges in scaling our analysis and implementing modeling techniques. Optimizing model training times and utilizing available resources efficiently required considerable effort.

Hyperparameter tuning is crucial for achieving optimal results, involving adjusting parameters to ensure the best fit with the dataset. The challenge lies in identifying the most suitable combination for each model to achieve optimal predictive accuracy.

## Lesson Learned
Visualizations played a crucial role in understanding hypotheses, aiding in the interpretation of patterns and relationships within the data. Integrating various datasets allowed for a comprehensive examination of the problem, facilitating thorough analysis and exploration of potential solutions.

To address class imbalance issues, particularly the majority class problem, we utilized under-sampling methods to balance the class distribution. Additionally, optimizing model performance involved careful model selection and hyperparameter tuning, resulting in improved outcomes.

Given the extensive datasets, feature engineering emerged as a critical component in extracting meaningful insights and enhancing model performance. This prompted exploration of various feature selection and extraction techniques.

From implementing machine learning algorithms such as LG Boost to fine-tuning parameters and evaluating performance metrics, I developed proficiency in model development and assessment. This enabled informed decision-making based on result interpretation, aligned with the business requirements of Home Credit.

## Attachments
**[EDA Notebook](https://github.com/Sarvii23/Mukagen/blob/main/EDA_Capstone_MSBA.ipynb)**

**[Modeling Notebook](https://github.com/Sarvii23/Mukagen/blob/main/Modelling_Capstone_MSBA.ipynb)**

**[Presentation](https://github.com/Sarvii23/Mukagen/blob/main/Capstone%202024-%20Group%207%20.pptx)**

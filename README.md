# Cybersecurity Behavior Category Prediction
# Objective of the Project

The primary goal of this project is to predict the cybersecurity behavior category of teenagers based on their digital activities and safety practices. By using machine learning techniques, the project will classify teenagers into predefined behavior categories to better understand patterns of safe or unsafe behavior in the digital space. This could potentially help in identifying areas where further education or intervention might be necessary to promote safer online behavior.
# Steps:

Clean and preprocess the dataset.
Perform exploratory data analysis (EDA).
Build a machine learning model to predict the Cybersecurity_Behavior_Category.
Evaluate model performance and provide insights.
# Introduction to the Project

In today’s increasingly digital world, cybersecurity is a growing concern, especially for younger users who are more active online. Teenagers often engage with various online platforms, social media, and digital services, exposing them to potential risks such as malware attacks, phishing attempts, and data breaches. These risks can vary depending on user behavior, device security practices, and overall online awareness.

This project, titled Cybersecurity Behavior Category Prediction, aims to classify users into three categories: Safe, Neutral, and Risky based on their cybersecurity practices and online behavior. By analyzing data such as malware detections, phishing attempts, social media usage, and login security, we can better understand the online habits that contribute to risky cybersecurity behaviors.

# Problem Statement

The problem addressed in this project is the prediction of a user’s Cybersecurity Behavior Category based on their interaction with the internet, device usage, and security habits. The objective is to create a model that accurately identifies whether a user is likely to engage in safe, neutral, or risky behavior based on their digital footprint. This prediction can help in targeted awareness campaigns, policy formulation, and personalized cybersecurity interventions to enhance overall safety online.

By analyzing the dataset, we seek to uncover key patterns and factors that influence risky online behavior, helping to predict and prevent potential cybersecurity threats among teenage users.

# About Dataset

This dataset captures the real-world online behavior of teenagers, focusing on e-safety awareness, cybersecurity risks, and device interactions. The data was collected from network activity logs and e-safety monitoring systems across various educational institutions and households in Texas and California. Spanning from January 2017 to October 2024, this dataset includes interactions with social media platforms, educational websites, and other online services, providing an in-depth look at teenage online activities in urban and suburban settings. The dataset is anonymized to protect user privacy and contains real incidents of network threats, security breaches, and cybersecurity behavior patterns observed in teenagers.

# Conclusion
In this project, we aimed to predict the Cybersecurity Behavior Category based on the provided dataset. The process involved various steps, including data preprocessing, feature engineering, model training, hyperparameter tuning, and evaluation. Here are the key takeaways:

# Data Preprocessing: 
We began by exploring the dataset, checking for null values, handling duplicates, detecting and correcting outliers, and dealing with skewness in numerical columns. This ensured that the dataset was clean and ready for modeling.

# Feature Engineering: 
We performed feature selection using correlation matrices and applied encoding for categorical variables. Standardization was then applied to numerical features to ensure all features were on the same scale for model training.

# Model Training: 
We trained several machine learning models including Logistic Regression, Decision Trees, Random Forest, SVM, and XGBoost. Each model was evaluated using metrics such as accuracy, precision, recall, and F1-score.

# Overfitting: 
To address overfitting, we applied regularization techniques such as limiting tree depth for Decision Trees and Random Forests, and used L2 regularization for Logistic Regression. Hyperparameter tuning was also employed to find the optimal model parameters.

#H yperparameter Tuning: 
Using GridSearchCV and RandomizedSearchCV, we optimized hyperparameters for models like Random Forest, SVM, and Logistic Regression, which significantly improved the model performance on the test set.

# Model Saving: 
Finally, we saved the best-performing model using a pipeline that combined both preprocessing and the model itself. This allows the model to be easily reused and deployed without having to repeat the preprocessing steps.

# Final Model Performance:
The best model, which was a Random Forest, achieved a high accuracy on both training and test datasets after hyperparameter tuning. This model is saved and ready for future use.


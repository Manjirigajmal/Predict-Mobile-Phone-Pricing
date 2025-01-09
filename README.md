# Predict-Mobile-Phone-Pricing
This repository contains the code and data for a machine learning model developed to predict mobile phone price categories (low, medium, high, very high) based on various phone features such as RAM, battery life, screen size, and more. The project utilizes multiple machine learning algorithms to classify mobile phones into distinct price categories, providing valuable insights for businesses and consumers.
Overview
This project focuses on classifying mobile phones into four price categories based on various features. Machine learning models such as Logistic Regression (LR), Random Forest (RF), XGBoost, Support Vector Machine (SVM), and K-Nearest Neighbors (KNN) are trained and evaluated to predict these categories. The goal is to provide a reliable price prediction tool that can help businesses in pricing strategies, inventory management, and customer satisfaction.
Data
The dataset used in this project contains various mobile phone features like RAM, battery life, screen size, and camera resolution, which are used to predict the price category of each phone.

The dataset is located in the data/ folder and is expected to be in CSV format. If the dataset is large, consider using data sampling techniques for model training.

Models
The following machine learning models have been implemented and evaluated in this project:

Logistic Regression (LR)
Accuracy: 97.67%
A simple but effective model, LR works well for binary and multiclass classification problems.
Feature selection was used to improve performance.
Random Forest (RF)
Accuracy: 91.17%
Random Forest creates an ensemble of decision trees to classify data based on various phone features.
Model performance improved after feature selection.
XGBoost
Accuracy: 94.17%
XGBoost is an optimized gradient boosting algorithm that excels in handling large datasets and complex data relationships.
Support Vector Machine (SVM)
Accuracy: 97.50%
SVM finds the best hyperplane to classify data points into different categories. It achieved near-perfect classification after hyperparameter tuning.
K-Nearest Neighbors (KNN)
Accuracy: 65.33%
KNN is a simple model that classifies data points based on their proximity to other data points. It performs well for extreme price categories but struggles with mid-range prices.
Model Evaluation
Each model was evaluated based on the following metrics:

Accuracy: Percentage of correctly classified instances.
Precision: The ability to classify only relevant instances.
Recall: The ability to identify all relevant instances.
F1-Score: Harmonic mean of precision and recall.
ROC-AUC: Area under the Receiver Operating Characteristic curve, which shows the model's ability to distinguish between classes.
Usage
To use the trained models for prediction, you can run the Jupyter notebook price_prediction.ipynb, which will walk you through the steps of loading the data, preprocessing it, training the models, and evaluating them. You can also make predictions on new data by following the example in the notebook.

Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Whether it's bug fixes, new features, or improvements to the documentation, contributions are always welcome!

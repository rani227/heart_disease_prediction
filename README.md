# heart_disease_prediction
Heart Disease Prediction using Machine Learning &amp; Deep Learning
This project focuses on developing and comparing multiple machine learning models to predict the presence of heart disease based on clinical attributes, using the UCI Heart Disease dataset (heart.csv). The goal is binary classification—identifying whether a patient is likely to have heart disease (target = 1) or not (target = 0).

Key Components:
Exploratory Data Analysis (EDA):
Performed thorough data inspection and visualization using Seaborn and Matplotlib to understand feature distributions, relationships, and class imbalances. Features such as chest pain type, thalassemia, and exercise-induced angina were found to be strongly correlated with heart disease.

Data Preparation:
Cleaned the dataset and split it into training and testing sets using an 80/20 ratio. Basic preprocessing steps ensured the data was ready for modeling.

Model Training and Evaluation:
Implemented and evaluated the following models:

Logistic Regression

Naive Bayes

Support Vector Machine (Linear Kernel)

K-Nearest Neighbors

Decision Tree (with random seed optimization)

Random Forest (with exhaustive seed tuning)

XGBoost

Feedforward Neural Network using Keras

Each model was evaluated using accuracy score on the test set. Among the models, XGBoost and the neural network achieved the highest accuracy, demonstrating their effectiveness in capturing complex patterns in the data.

Results Visualization:
A final comparison of model performance was presented using a bar plot to highlight the accuracy scores of all models.


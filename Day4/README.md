Task 4: Classification using Logistic Regression
Objective

The objective of this project is to build a binary classification model using Logistic Regression. The model is trained to classify data into two categories and evaluated using various performance metrics.

 Dataset
Dataset used: Breast Cancer Wisconsin Dataset
Source: Scikit-learn built-in dataset
Type: Binary Classification (Malignant vs Benign)
Tools & Libraries Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn
Steps Performed
1. Data Loading
Loaded dataset using sklearn.datasets
Separated features (X) and target (y)
2. Data Preprocessing
Performed train-test split (80-20)
Applied feature scaling using StandardScaler
3. Model Training
Used Logistic Regression from Scikit-learn
Trained the model on training data
4. Model Evaluation

Evaluated model using:

Confusion Matrix
Precision
Recall
ROC-AUC Score
5. Visualization
Plotted ROC Curve to analyze model performance
6. Threshold Tuning
Adjusted classification threshold to observe performance changes
Results
Model successfully classified the dataset with high accuracy
ROC-AUC score indicates strong model performance
Precision and Recall values show good balance

  Breast Cancer Prediction Using Logistic Regression


  Overview
  
This project involves building a machine learning model using Logistic Regression to predict whether breast cancer is benign or malignant based on certain input features. The dataset used for this project is the Breast Cancer Wisconsin dataset, which is available in the sklearn.datasets module.

The Breast Cancer Wisconsin dataset contains 569 samples of tumor data, each with 30 features. The target variable has two classes :
0: Malignant
1: Benign
The features include various measurements like mean radius, mean texture, mean perimeter, mean area, and more. The dataset is split into a training set and a test set, with 80% of the data used for training and 20% for testing.

Code Explanation

Loading the Dataset :
The Breast Cancer Wisconsin dataset is loaded using sklearn.datasets.load_breast_cancer(). This data is then converted into a pandas DataFrame for easy manipulation and analysis.

Data Exploration :
The first few rows of the data are displayed using data_frame.head().
The shape, info, and statistical summary of the dataset are checked.
The distribution of the target variable (benign vs. malignant) is analyzed.

Data Preprocessing :
The features are separated from the target variable, and the dataset is split into training and testing sets using train_test_split.

Model Training :
A Logistic Regression model is trained using the training data.

Model Evaluation :
The model is evaluated using the test data. The evaluation metrics include:

Accuracy :
Precision
Recall
F1-Score
Confusion Matrix
Classification Report
Predictive System:
A predictive system is built to predict whether a tumor is benign or malignant based on new input data.

Results :
Accuracy: The model's accuracy on the test data is printed.
Precision & F1 Score: Precision and F1 score are calculated for both training and testing data.
Confusion Matrix & Classification Report: The confusion matrix and classification report for the test data are displayed.

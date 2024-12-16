**Diabetes Prediction using Machine Learning**
This project predicts whether a person is diabetic or not using a machine learning model trained on the Diabetes Dataset. The dataset includes medical parameters such as glucose levels, blood pressure, BMI, and age. The prediction is made using a Support Vector Machine (SVM) classifier with a linear kernel.

**Project Workflow:**

**1)Data Preprocessing:**
Loaded the dataset using pandas and explored the data structure.
Standardized the feature values using StandardScaler to improve model performance.

**2)Model Training:**
Split the dataset into training and testing sets (80%-20%) while maintaining class distribution using stratified sampling.
Trained a Support Vector Machine (SVM) classifier with a linear kernel on the training data.

**3)Model Evaluation:**
Training Accuracy: 78.66%
Testing Accuracy: 77.27%
Evaluated the model using the accuracy_score metric.

**Prediction:**
Tested the model with sample input data to predict whether a person is diabetic or not.
Input data is preprocessed and standardized before being fed into the model.

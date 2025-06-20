# Image-Segmentation-Analysis
Image Segmentation Analysis using Neural Network


## Summary of Steps:

Data loading and preprocessing using pandas and LabelEncoder.

Feature selection and train-test split using sklearn.

Model training using a decision tree classifier.

Evaluation via accuracy, confusion matrix, and classification report.

Visual representation of the tree using plot_tree.

Final Result:

Achieved an accuracy of ~92.6% on the test set.

Classification report and confusion matrix confirm good performance across classes.


# Objective:
To build a predictive model for a multi-class classification task using decision tree and evaluate performance on test data.

# Workflow Summary:
## 1. Data Preparation
Imported structured dataset using pandas.

Performed LabelEncoder transformation on categorical variables.

Selected appropriate features and target for model input.

## 2. Data Splitting
Used train_test_split from sklearn.model_selection to divide data (80/20) into training and testing sets.

## 3. Model Training
Used DecisionTreeClassifier from sklearn.tree.

Fitted the model on training data.

## 4. Evaluation Metrics
Evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

Visualization:

Decision tree visualized using plot_tree from matplotlib.

# Results:
Accuracy on test set: ~92.6%

Confusion matrix showed few misclassifications.

Most classes were predicted with high precision and recall.



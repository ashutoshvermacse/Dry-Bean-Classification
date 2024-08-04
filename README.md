# Multiclass Classification Model Comparison on the Dry Bean Dataset

This project provides a comprehensive comparative analysis of various machine learning models applied to the 'Dry Bean' dataset from the UCI Machine Learning Repository. The aim is to evaluate the performance and effectiveness of different classification algorithms in identifying and categorizing dry bean species.

## **Dataset:**
------
- **`Source:`** UCI Machine Learning Repository
- **`Dataset Name:`** Dry Bean Dataset
- **`Description:`** The dataset consists of multiple features extracted from images of dry beans, such as area, perimeter, compactness, length, width, asymmetry coefficient, and others. The target variable represents different types of beans.

## **Classification Algorithms Used:**
-------
1. **Multinomial Logistic Regression:**
   - A generalized linear model used for multi-class classification tasks, extending logistic regression to handle more than two classes.
   
2. **Decision Trees:**
   - A non-parametric model that splits the dataset into subsets based on the value of input features, forming a tree structure for classification.
   
3. **Random Forest:**
   - An ensemble learning method that constructs multiple decision trees during training and outputs the mode of the classes for classification.
   
4. **XGBoost:**
   - An optimized gradient boosting algorithm that enhances the performance and speed of decision trees, suitable for large datasets.
   
5. **Support Vector Machine (SVM):**
   - A supervised learning model that finds the hyperplane that best separates the classes in the feature space.
   
6. **Neural Network:**
   - A model inspired by the structure of the human brain, consisting of interconnected layers of neurons that learn to classify input data through backpropagation.
   
7. **k-Nearest Neighbours (k-NN):**
   - A simple, instance-based learning algorithm that classifies data points based on the majority class of their k-nearest neighbours in the feature space.
   
8. **Naive Bayes:**
   - A probabilistic classifier based on Bayes' theorem, assuming independence between the features given the class label.

## **Results**
------
The project generates performance metrics and visualizations for each model:

- **`Confusion Matrices:`** Displayed for each model to show the classification performance.
- **`ROC Curves:`** Separate plots for each model to compare how well each model discriminates between classes.
- **`Performance Metrics:`** A comprehensive table showing accuracy, precision, recall, F1 score, and AUC values for all models.

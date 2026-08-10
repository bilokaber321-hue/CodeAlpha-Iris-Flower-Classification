

**Program:** CodeAlpha Data Science Internship  
**Task:** Unemployment Analysis with Python  
**Intern:** Bilal Akbar  
**Student ID:** CA/DF1/236331  
**Batch:** 10 August 2026 – 10 September 2026

# Iris Flower Classification

## Project Overview

This project is completed as part of the CodeAlpha Data Science Internship Program.

The objective of this project is to develop a machine learning classification model capable of predicting the species of an Iris flower based on its sepal and petal measurements.

The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis, visualization, model training, evaluation, and prediction.

## Objective

The main objectives of this project are:

- Explore and understand the Iris dataset
- Perform data cleaning and preprocessing
- Analyze relationships between features
- Visualize the dataset
- Train multiple machine learning classification models
- Compare model performance
- Select the best-performing model
- Evaluate predictions using appropriate metrics

## Dataset

The Iris dataset contains 150 observations belonging to three different Iris species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target

- Species

## Machine Learning Models

The following classification algorithms were evaluated:

- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine
- Decision Tree
- Random Forest

## Methodology

The project follows these steps:

1. Import required libraries
2. Load the dataset
3. Inspect the dataset
4. Check missing values and duplicates
5. Perform exploratory data analysis
6. Visualize feature distributions and relationships
7. Split the dataset into training and testing sets
8. Apply feature scaling where required
9. Train multiple classification models
10. Evaluate model performance
11. Compare classification results
12. Select the best-performing model
13. Generate predictions on unseen data

## Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The Support Vector Machine model achieved the strongest performance among the evaluated models, with approximately 96.67% test accuracy.

## Key Findings

- Petal measurements are highly effective features for identifying Iris species.
- Iris-setosa is clearly separated from the other two classes.
- Some overlap exists between Iris-versicolor and Iris-virginica.
- Machine learning models can classify the Iris species with high accuracy.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
CodeAlpha-Iris-Classification/
│
├── README.md
├── Iris_Flower_Classification.ipynb
│
├── data/
│   └── Iris.csv
│
└── outputs/
    ├── confusion_matrix.png
    ├── model_comparison.png
    ├── pairplot.png
    └── other_visualizations.png

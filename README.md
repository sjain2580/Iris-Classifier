# Iris Classifier

## Overview

This project is a simple machine learning pipeline that builds and evaluates a classifier to predict the species of Iris flowers. It uses the classic Iris dataset, a foundational benchmark in the field of machine learning. The project demonstrates core concepts of supervised learning, including classification, model evaluation, and the crucial practice of hyperparameter tuning to combat overfitting.

## Features

- Model Comparison: Trains and evaluates two distinct classification models: a Logistic Regression model and a Decision Tree classifier.

- Overfitting Demonstration: Illustrates the concept of overfitting by training a complex Decision Tree and showing its performance on both training and test data.

- Hyperparameter Tuning: Uses GridSearchCV to systematically find the optimal hyperparameters for the Decision Tree, creating a robust and well-generalized model.

- Performance Evaluation: Uses standard metrics like Accuracy and F1-Score to measure the performance of each model.

- Visualization: Generates plots to visualize the decision boundaries of each classifier, providing a clear understanding of how the models separate the data.

## Technologies Used

- Python: The core programming language.

- numpy: For numerical operations.

- scikit-learn: The primary machine learning library, used for all models, data splitting, and evaluation.

- matplotlib & seaborn: For creating all visualizations and plots.

## Data Analysis & Processing

The project begins by loading the Iris dataset from scikit-learn. For visualization purposes, only two features—sepal length and sepal width—are selected. The dataset is then split into a training set (70%) and a testing set (30%) to ensure that the models are evaluated on unseen data.

## Model Used

The project utilizes two main classifiers:

1. Logistic Regression: A linear model that uses a sigmoid function to classify data points into different categories. It is an excellent choice for a simple baseline model.

2. Decision Tree Classifier: A non-linear model that makes predictions by asking a series of questions about the features. This model is highly interpretable, and its complexity can be controlled through hyperparameters.

## Model Training

The models are trained on the preprocessed training data. The Decision Tree model, in particular, undergoes hyperparameter tuning using GridSearchCV. This method systematically tests a range of max_depth values to find the one that results in the best performance on validation data, effectively preventing the model from overfitting to the training set.

## How to Run the Project

1. Clone the repository:

```bash
git clone <https://github.com/sjain2580/Iris-Classifier.git>
cd <repository_name>
```

2. Create and activate a virtual environment (optional but recommended):python -m venv venv

- On Windows:
  
```bash
.\venv\Scripts\activate
```

- On macOS/Linux:

```bash
source venv/bin/activate
```

1. Run the notebook: Open the iris_classifier_notebook.md file in a Jupyter Notebook environment and run the cells in order.

## Visualization

The project generates several plots, including the decision boundaries for the Logistic Regression model, the overfitted Decision Tree, and the final, optimized Decision Tree. These plots visually demonstrate how each model makes its predictions and highlight the importance of proper tuning.

## Contributors

**<https://github.com/sjain2580>**
Feel free to fork this repository, submit issues, or pull requests to improve the project. Suggestions for model enhancement or additional visualizations are welcome!

## Connect with Me

Feel free to reach out if you have any questions or just want to connect!
**[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sjain04/)**
**[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/sjain2580)**
**[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:sjain040395@gmail.com)**

---

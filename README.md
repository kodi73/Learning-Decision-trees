# Drug Classification using Decision Trees

This project demonstrates how to build, visualize, and evaluate a decision tree classifier using a real-world dataset on drug prediction based on patient health parameters.

## Introduction

Decision tree classification is a powerful machine learning technique for making data-driven decisions. This notebook walks through the process of applying decision trees to the Drug200 dataset to predict the appropriate drug for a patient based on their characteristics.

## Dataset

The dataset used in this lab is available at: `https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/Module%203/data/drug200.csv`

It contains the following columns:
- Age (int64)
- Sex (object)
- BP (object)
- Cholesterol (object)
- Na_to_K (float64)
- Drug (object)

## Project Steps

The notebook covers the following steps:

1. **Data Loading and Exploration**: Load the dataset and perform initial data exploration to understand its structure and contents.
2. **Data Preprocessing**: Handle categorical features by encoding them into numerical representations.
3. **Feature Selection**: Analyze the correlation between input features and the target variable to identify the most influential features.
4. **Data Splitting**: Split the dataset into training and testing sets for model development and evaluation.
5. **Model Building**: Build a Decision Tree Classifier model.
6. **Model Training**: Train the decision tree model on the training data.
7. **Model Evaluation**: Evaluate the performance of the trained model using appropriate metrics.
8. **Model Visualization**: Visualize the trained decision tree.
9. **Hyperparameter Tuning (Optional)**: Experiment with different hyperparameters (like `max_depth`) to observe their impact on model performance.

## Dependencies

The following libraries are required to run this notebook:

- numpy
- pandas
- scikit-learn
- matplotlib

The required versions are installed at the beginning of the notebook using pip.

## Usage

1. Clone the repository.
2. Open the notebook in Google Colab or a Jupyter environment.
3. Run the cells sequentially to execute the project steps.

## Results

The notebook demonstrates how to build a decision tree model and evaluate its accuracy. It also shows how varying the `max_depth` hyperparameter can affect the model's performance.

## Author

Aditya Kumar

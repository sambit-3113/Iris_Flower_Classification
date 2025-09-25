
# Iris Flower Classification using Machine Learning

This project is aimed at classifying different species of Iris flowers using machine learning models and find out the best performing model. The dataset used is the Iris dataset, which contains measurements of 150 Iris flowers, classified into three species: Iris-setosa, Iris-versicolor, and Iris-virginica. We apply various machine learning algorithms to classify the flowers based on their features.

## Contents of the Zip File

The zip file contains the following files:

1.Iris Dataset: 
  This is the raw dataset, which includes four features (sepal length, sepal width, petal length, petal width) and the corresponding species label for each flower.
   - File: Iris.csv

2. Jupyter Notebook for EDA (Exploratory Data Analysis):  
   A notebook for performing EDA on the Iris dataset. This includes data cleaning, visualizations, and statistical summaries to understand the dataset better.
   - File: EDA.ipynb

3. Cleaned Iris Dataset (after EDA):
   A cleaned version of the original dataset, with missing values handled and any other necessary preprocessing steps completed.
   - File: Cleaned_Iris.csv

4. Jupyter Notebooks for Different Machine Learning Models:  
   These notebooks contain code for training different machine learning models on the dataset(cleaned_iris.csv). They include:
   - K_iris.ipynb: Knn, Random forest, Adaboost
   - S_iris.ipynb: Decision Tree, SVM(PCA and Non-PCA), Gaussian Naive Bayes, Gradient Boosting, XGBoost 
   - N_iris.ipynb: Logistic regression, ANN, Ensemble of Ensembles, Catboost Algorithm

5. Final Group Project Report:  
   The final report summarizing the entire project, including the problem statement, dataset description, model building process, evaluation metrics, and conclusions.
   - File: CognitiQ_Project_Report.pdf

## Requirements

To run the Jupyter Notebooks and models, you will need the following Python libraries:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- jupyter

You can install the required libraries using `pip`:

```
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

## Usage Instructions

1. Step 1: Load the Data
   Start by exploring the raw Iris dataset or the cleaned version using the `EDA.ipynb` notebook. The dataset is already available in the zip file.

2. Step 2: Data Preprocessing 
   Clean the data by handling any missing values or inconsistencies. This is done and the output dataframe is stored in the `Cleaned_Iris.csv` file.

3. Step 3: Model Training
   After data preprocessing, you can train machine learning models on the cleaned dataset. The provided notebooks for KNN, SVM, and Random Forest show how to implement each model. These models can be trained by running the respective notebooks (`KNN_Model.ipynb`, `SVM_Model.ipynb`, or `Random_Forest_Model.ipynb`).

4. Step 4: Model Evaluation 
   The models will output accuracy scores, confusion matrices, and classification reports. Evaluate the performance of the models and choose the best one.

## Project Summary

- Dataset: The Iris dataset, a well-known dataset for classification tasks, with four features and three classes.
- Objective: To classify Iris flowers based on their features using machine learning algorithms and find out the best performing model.
- Techniques Used: Exploratory Data Analysis (EDA), Data Preprocessing, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Random Forest models.

## Licensing Info

Developed by Sambit Sahoo(1), Kirti Agrawal(1), and Nirman Jaiswal(1) under the supervision of Prof.Samiran Das as part of the semester group project for the course DSE315 Data Science in Practice. 

# Titanic Survival Prediction - Machine Learning Project

## Project Overview

This project focuses on building a **Machine Learning classification model** to predict whether a passenger survived the Titanic disaster. The objective is to preprocess the data, perform feature engineering, train multiple machine learning algorithms, evaluate their performance, and select the best-performing model.

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Project Structure

```
Pluto_ML_Project
│
├── MLM_P&E.ipynb
├── train[1].csv
└── README.md

```

## Project Workflow

### Data Loading & Exploration

* Imported the Titanic dataset using Pandas.
* Checked dataset shape, structure, and data types.
* Analyzed missing values and statistical information.

### Data Preprocessing

Performed:

* Handled missing values in Age and Embarked columns.
* Removed irrelevant features such as PassengerId, Name, Ticket, and Cabin.
* Converted categorical variables into numerical format.
* Split the dataset into training and testing sets using an 80/20 split.

### Feature Engineering

Performed:

* Correlation analysis to understand feature relationships.
* Feature importance analysis using machine learning techniques.
* Selected important features that influence survival prediction.

## Machine Learning Models

Trained and evaluated three classification algorithms:

* Logistic Regression
* Random Forest Classifier
* K-Nearest Neighbors (KNN)

## Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Best Model

* Selected the best-performing model based on evaluation metrics.
* Logistic Regression achieved the highest performance on the test dataset.
* The final model was chosen for Titanic survival prediction.

## Key Insights

* Passenger gender was one of the most influential factors affecting survival.
* Passenger class and fare had a significant relationship with survival probability.
* Proper data preprocessing improved model performance.
* Logistic Regression provided reliable classification results for this dataset.

## How to Run

1. Open the notebook in Google Colab.
2. Upload the Titanic dataset (`train.csv`).
3. Install required Python libraries if needed.
4. Run all cells sequentially.
5. View model performance and prediction results.

## Learning Outcomes

* Learned machine learning data preprocessing techniques.
* Practiced feature engineering and feature selection.
* Built and compared multiple classification models.
* Improved understanding of model evaluation metrics.
* Gained practical experience in solving real-world classification problems.

## Author

Pavendhan B

Aspiring AI/ML Engineer

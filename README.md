# Social Media Usage Analysis and Current Status Classification

This repository contains a Jupyter notebook for a machine learning project that analyzes social media usage and demographic data from India to predict a user's **'Current Status'** (e.g., Working professional, Student, Sabbatical).

The project explores data preprocessing, feature encoding, and the performance of multiple classification algorithms on the dataset.

## Project Methodology

The analysis and classification process includes:

1.  **Data Loading & Exploration**: Loading the `Social Media Usage India.csv` dataset and inspecting its structure and for missing values.
2.  **Data Preprocessing**: Using `LabelEncoder` to convert categorical features into a format suitable for machine learning models.
3.  **Model Training & Evaluation**: Splitting the data into training and testing sets (the notebook experiments with 80/20, 70/30, and 60/40 splits) and comparing the performance of various classification models.

## Models Evaluated

The notebook evaluates the following machine learning models for predicting a user's current status:

* Logistic Regression
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Random Forest Classifier
* Gradient Boosting Classifier
* Decision Tree Classifier
* Gaussian Naive Bayes
* Multilayer Perceptron (MLPClassifier)

## Setup and Installation

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd <your-repo-name>

# German Credit Analysis

This project involves analyzing the German Credit dataset to predict credit risk (Good or Bad) using machine learning techniques. It focuses on data cleaning, exploratory data analysis (EDA), data preprocessing, clustering, and classification. The analysis aims to provide insights into the key factors affecting credit risk and improve the accuracy of credit scoring.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Key Features](#key-features)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Results](#results)

## Project Overview
The goal of this project is to analyze the German Credit dataset and develop a classification model that predicts whether a credit applicant is a good or bad risk. This involves:
- Data preprocessing and cleaning.
- Exploratory Data Analysis (EDA) to uncover insights.
- Building and evaluating machine learning models.

## Dataset Description
The dataset contains information about 1,000 credit applicants, including attributes such as:
- Age: Age of the individual
- Sex: Gender of the individual
- Job: Type of job (0 - Unskilled & Non-Resident, 1 - Unskilled & Resident, 2 - Skilled, 3 - Highly Skilled)
- Housing: Housing status (Own, Rent, or Free)
- Saving Accounts: Savings account balance
- Checking Account: Checking account balance
- Credit Amount: Amount of credit taken
- Duration: Duration of the credit in months
- Purpose: Purpose of the credit (e.g., car, education, etc.)

Target Variable:  
- **Risk**: `Good` (1) or `Bad` (0)

The dataset can be found in **Kaggle**: [German Credit Analysis || A Risk Perspective](https://www.kaggle.com/code/janiobachmann/german-credit-analysis-a-risk-perspective)

## Technologies Used
- **Programming Language**: Python  
- **Libraries**:  
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Machine Learning Techniques**:  
  - Random Forest Classifier
  - PCA
  - KMeans Clustering

## Key Features
- **Exploratory Data Analysis (EDA)**: 
  - Visualize data distributions.
  - Handle missing values and perform log transformations.
- **Clustering and PCA**:
  - Use KMeans clustering to identify patterns.
  - Apply PCA for dimensionality reduction and visualization.
- **Classification Model**:
  - Random Forest Classifier to predict credit risk.
  - Evaluation using confusion matrices, classification reports, and ROC AUC scores.
- **Confusion Matrix Visualization**:
  - Heatmap visualization for clear interpretation of classification results.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/aritro98/German-Credit-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd German-Credit-Analysis
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook German_Credit_Data.ipynb
   ```
2. Run the cells to explore the data, perform analysis, and build machine learning models.

## Results
The project successfully identifies patterns in credit data and predicts credit risk with the following highlights:
- **Classification Accuracy**: Achieved using a Random Forest model.
- **Confusion Matrix**: Provides clear insights into true positives, true negatives, false positives, and false negatives.
- **ROC AUC Score**: Indicates the model's ability to distinguish between Good and Bad credit risk.

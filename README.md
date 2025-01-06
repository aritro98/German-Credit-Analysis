# German Credit Analysis

Analyzed a dataset of 1,000 credit applicants to classify credit risk as good or bad. This project focuses on data cleaning, exploratory data analysis, and predictive modeling using machine learning techniques. The analysis aims to provide insights into the key factors affecting credit risk and improve the accuracy of credit scoring.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Technologies Used](#technologies-used)
- [Key Insights](#key-insights)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Results](#results)

---

## Project Overview
The goal of this project is to analyze the German Credit dataset and develop a classification model that predicts whether a credit applicant is a good or bad risk. This involves:
- Data preprocessing and cleaning.
- Exploratory Data Analysis (EDA) to uncover insights.
- Building and evaluating machine learning models.

---

## Dataset Description
The dataset contains information about 1,000 credit applicants, including attributes such as:
- Age
- Gender
- Job Type
- Loan Purpose
- Credit Amount
- Duration of Credit
- Other financial and demographic features

Target Variable:  
- **Risk**: `Good` (1) or `Bad` (0)

The dataset is provided in the file: `data/german_credit_data(in).csv`.

---

## Technologies Used
- **Programming Language**: Python  
- **Libraries**:  
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Jupyter Notebook

---

## Key Insights
- **Age Group**: Younger applicants tend to have a higher risk.
- **Loan Amount**: Higher loan amounts correlate with increased risk.
- **Duration**: Longer credit durations often result in a bad risk classification.
- Other factors like job type and loan purpose also significantly impact credit risk.

---

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/German-Credit-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd German-Credit-Analysis
   ```
3. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Linux/Mac
   venv\Scripts\activate     # For Windows
   ```
4. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook notebooks/German_Credit_Aritro_Dutta.ipynb
   ```
2. Run the cells to explore the data, perform analysis, and build machine learning models.

---

## Results
The machine learning models achieved the following performance:
- **Logistic Regression**: 85% accuracy
- **Random Forest**: 92% accuracy
- **Support Vector Machine (SVM)**: 89% accuracy

These results indicate that Random Forest performed the best in classifying credit risk.

---

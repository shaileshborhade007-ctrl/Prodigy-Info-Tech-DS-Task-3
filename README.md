
# Task-03: Decision Tree Classification

## Overview
This repository contains the solution for **Task-03**, which focuses on building a **Decision Tree Classifier** to predict whether a customer will subscribe to a **bank term deposit** based on demographic, behavioral, and economic features.  
The task emphasizes model building, evaluation, and feature importance analysis.

##  Dataset
- Dataset Name:Bank Marketing Dataset  
- File Used: `bank-additional-full.csv`  
- Source:UCI Machine Learning Repository / Prodigy Infotech  
- Description: 
  The dataset contains information related to direct marketing campaigns of a Portuguese banking institution, including customer demographics, contact details, and economic indicators.

## Objective
- Build a Decision Tree classification model  
- Predict customer subscription (`yes` / `no`)  
- Analyze important features influencing the prediction  
- Evaluate model performance using classification metrics  

## Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

## Step-by-Step Process
1. Imported required Python libraries  
2. Loaded and explored the dataset  
3. Handled categorical variables using encoding  
4. Split the dataset into training and testing sets  
5. Trained a Decision Tree Classifier  
6. Evaluated the model using accuracy and classification report  
7. Generated confusion matrix  
8. Visualized the decision tree  
9. Analyzed feature importance  

## Visualizations Performed
- Decision Tree structure  
- Feature Importance bar chart  
- Confusion Matrix

## Key Insights
- **Call duration** is the most influential feature in predicting customer subscription  
- Behavioral features have a higher impact than demographic features  
- Economic indicators also play a significant role  
- Decision Trees provide clear and interpretable decision rules  

## Results & Findings
- The model achieved high accuracy  
- Most non-subscribers were predicted correctly  
- The model performs well in identifying customer behavior patterns  

## Conclusion 
In this task, a Decision Tree Classifier was developed to predict whether a customer would subscribe to a bank term deposit using demographic, behavioral, and economic features from the Bank Marketing dataset. The dataset was carefully preprocessed by encoding categorical variables and splitting the data into training and testing sets.
The trained model achieved strong predictive performance with high accuracy, demonstrating its ability to effectively distinguish between subscribing and non-subscribing customers. Evaluation using a classification report and confusion matrix showed that the model performs particularly well in identifying non-subscribers, while still maintaining
reasonable recall for actual subscribers despite class imbalance.The decision tree visualization provided clear interpretability, revealing that behavioral and economic factors such as call duration, employment variation rate (nr.employed), days since last contact (pdays), and consumer confidence index are the most influential determinants of 
customer decisions. Feature importance analysis further confirmed that these factors have a significantly greater impact than demographic attributes like age, job, or marital status.Overall, this task demonstrates that Decision Tree models are highly effective for marketing analytics due to their transparency and interpretability. The insights 
derived from the model can support data-driven marketing strategies by helping banks focus on high-potential customers, optimize campaign timing, and improve customer engagement, ultimately leading to better conversion rates.


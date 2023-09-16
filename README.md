# Online Shoppers Purchasing Intention Classification

## Table of Contents
- [Introduction](#introduction)
- [Abstract](#abstract)
- [Data Description](#data-description)
- [Methods](#methods)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Balancing the Dataset](#balancing-the-dataset)
- [Results](#results)
- [Discussion](#discussion)

---

## Introduction
This project focuses on predicting online shoppers' purchasing intentions based on their website activity. Accurate predictions can empower online retailers to optimize their website design, marketing strategies, and customer engagement efforts. The binary classification problem distinguishes between "True" (shoppers make a purchase) and "False" (shoppers do not make a purchase) outcomes.

## Abstract
In this project, we dive into the world of online shopper behavior analysis, aiming to predict whether a visitor will make a purchase during their online session. To achieve this, we explore various factors, such as the time of day, average time spent on individual products, the user's region, and more. Our comprehensive analysis comprises Exploratory Data Analysis (EDA), Feature Engineering, Feature Selection, and rigorous model comparison.

## Data Description
- **Dataset**: 12,330 records with 18 features
- **Target Variable**: "Revenue" indicates whether a purchase was made.
- **Imbalance**: About 84.5% of sessions show no purchase (negative class), while 15.5% result in a purchase (positive class).
- **Features**: Administrative, Informational, and Product-Related metrics, as well as categorical attributes like month, operating system, browser, region, traffic type, visitor type, and weekend indicator.

## Methods
1. **Logistic Regression**: A parametric classification model used for binary outcomes.
2. **Naïve Bayes**: Leveraging Gaussian Naïve Bayes for probability computation.
3. **Neural Networks**: Harnessing multi-layer neural networks, akin to the human brain, for complex pattern recognition.

## Exploratory Data Analysis (EDA)
- **Understanding Data**: We start by gaining a deep understanding of the data, examining its types and checking for null values.
- **Feature Engineering**: We employ feature engineering techniques to enhance the quality of our dataset, including handling correlated features.
- **Data Visualization**: We visualize the data to uncover insightful trends, such as monthly revenue patterns, visitor types, and activity on weekends versus weekdays.

## Balancing the Dataset
- To mitigate the class imbalance issue, we utilize the Synthetic Minority Oversampling Technique (SMOTE) for oversampling the minority class, resulting in a balanced dataset.

## Results
- We evaluate three models: Logistic Regression, Naïve Bayes, and Neural Networks.
- Model performance is assessed using precision, recall, and the F1-score.
- Both Logistic Regression and Neural Networks deliver promising results, with trade-offs between precision and recall depending on the threshold.

## Discussion
- Feature engineering and dataset balancing play pivotal roles in enhancing model performance.
- Logistic Regression and Neural Networks emerge as the top-performing models.
- Consider fine-tuning the threshold to align predictions with specific business objectives.

For detailed findings and comprehensive insights, please refer to our project report.

---

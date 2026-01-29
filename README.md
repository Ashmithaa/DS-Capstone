## Product Performance Analysis and Predictive Modeling on Flipkart E-Commerce Data
-----
## Project Overview

- This capstone project implements an end-to-end data science pipeline to analyze Flipkart e-commerce product data. The project focuses on extracting unstructured web data, transforming it into a structured format, and applying data analysis, clustering, and machine learning techniques to generate actionable business insights.

- Python is used for web scraping, data processing, and modeling, while MySQL is used for structured data storage. The project demonstrates a real-world, industry-relevant analytics workflow.

## Problem Statement

- Flipkart product data is available only in unstructured web formats, making analysis difficult. Key challenges include:

- Scattered and unstructured product data

- Manual analysis being inefficient and error-prone

- Lack of centralized relational storage

- No predictive insights into pricing and product performance

- Difficulty identifying high- and low-performing products

- This project addresses these issues using Python, SQL, and Machine Learning.

## Project Objectives

- Collect product data from Flipkart using Python web scraping

- Clean and preprocess raw product data

- Design and implement a relational MySQL database

- Perform exploratory data analysis (EDA)

- Apply unsupervised learning for product segmentation

- Build supervised learning models for product classification

- Tune models and evaluate performance

- Extract meaningful business insights
------
## Dataset Description

The dataset was created by scraping product data from an e-commerce website.

- Attributes Collected

- Product Name

- Price

- Category

- Ratings

- Number of Reviews

  ## Tools and Technologies

- Python

- Pandas, NumPy

- BeautifulSoup / Scrapy

- Matplotlib, Seaborn

- Scikit-learn

- MySQL

- SQLAlchemy

- Jupyter Notebook

## Methodology

## Web Scraping

Identified an e-commerce website that permits scraping

Extracted product name, price, category, ratings, and reviews

Followed ethical scraping practices

Stored scraped data in CSV format

## Data Cleaning and Exploratory Data Analysis (EDA)

Handled missing values

Removed duplicate and irrelevant records

Standardized currency formats and text casing

Converted columns to appropriate data types

## EDA Performed

Price distribution analysis

Category-wise product counts

Rating distribution

Relationship between ratings and number of reviews

EDA insights guided feature selection for modeling.

## Data Storage

Designed a relational database schema

Connected Python to MySQL using SQLAlchemy

Stored cleaned data into SQL tables

Enabled efficient querying and reuse

## Unsupervised Learning – Clustering
## Objective

To identify hidden patterns and group similar products based on numerical features.

## Algorithm Used

K-Means Clustering

## Features Used

Product Price

Product Rating

Number of Reviews

## Feature Scaling

Applied standardization to normalize feature scales

## Optimal Cluster Selection

Elbow Method

Silhouette Score

## Cluster Interpretation

Low-Price Products: Budget-friendly items with moderate ratings and fewer reviews

Mid-Range Products: Balanced pricing and customer engagement

Premium Products: High-priced products with strong ratings and high review counts

## Supervised Learning – Product Classification
## Problem Definition

The task was formulated as a classification problem to predict product categories using numerical and encoded features.

## Features Used

Product Price

Product Rating

Number of Reviews

Encoded category features

## Models Implemented

Logistic Regression

Support Vector Machine (SVM)

k-Nearest Neighbors (k-NN)

Random Forest

XGBoost

## Evaluation Metrics

Accuracy

Precision

Recall

F1 Score

## Hyperparameter Tuning and Optimization
## Method

GridSearchCV with Cross-Validation

SMOTE applied for class imbalance

## Models Tuned

Logistic Regression

Random Forest

## Observations

Logistic Regression showed better generalization

L2 regularization improved stability

Random Forest showed marginal improvement but signs of overfitting

## Final Model Selection

Selected Model: Logistic Regression

## Reasons

Higher accuracy and F1 score

Better generalization

Lower computational cost

High interpretability for business use

This demonstrates that simpler models can outperform complex models when data relationships are predominantly linear.

-------
## Author
**Ashmithaa Pradeep** - Data Analytics & Data Science

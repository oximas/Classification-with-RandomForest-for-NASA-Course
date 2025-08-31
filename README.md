# Classification with Random Forest – NASA AI Course

This repository contains a simple demonstration of using the **Random Forest Classifier** with **scikit-learn** as part of the AI & Machine Learning for Space Apps course.

## Overview
- Algorithm: Random Forest Classifier (from `sklearn.ensemble`)
- Dataset: Iris dataset (built-in with scikit-learn)
- Task: Classify iris plants into 3 species based on flower measurements

## Requirements
- Python 3.x  
- scikit-learn  
- pandas (optional, for dataset handling)

Install dependencies:
```bash
pip install scikit-learn pandas
```
Usage
Open the notebook in Google Colab or locally:
```
jupyter notebook RandomForest_Iris.ipynb
```
Steps covered in the notebook:

Load the Iris dataset

Split into training and testing sets

Train a RandomForestClassifier

Make predictions

Evaluate accuracy

Results
Random Forest achieves high accuracy (>98%) on the Iris dataset

Demonstrates a simple but powerful ML workflow

Context
This project is used in the NASA Space Apps AI & Machine Learning Course (Session 1) to introduce participants to supervised learning with scikit-learn.

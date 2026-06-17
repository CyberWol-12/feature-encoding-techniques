#  Feature Encoding Techniques

A comprehensive Data Science project focused on understanding and implementing various Feature Encoding techniques used in Machine Learning and Feature Engineering.

This repository demonstrates how categorical variables can be transformed into machine-learning-ready features using different encoding strategies and real-world datasets.

---

## 📌 Project Overview

Feature Encoding is one of the most important steps in Data Preprocessing and Feature Engineering. Different encoding techniques can significantly impact model performance, dimensionality, and interpretability.

In this project, I explored and implemented multiple encoding techniques and analyzed their behavior on real-world datasets.

---

## 🛠️ Encoding Techniques Implemented

### ✅ Label Encoding
Converts categorical values into numerical labels.

### ✅ One-Hot Encoding
Creates binary columns for each category.

### ✅ Ordinal Encoding
Encodes categories based on a predefined order.

### ✅ Frequency Encoding
Replaces categories with their frequency counts.

### ✅ Target Encoding
Encodes categories using target variable statistics.

### ✅ Binary Encoding
Converts categories into binary representations.

### ✅ Hash Encoding
Uses hashing functions to encode categorical features efficiently.

---

## 📂 Datasets Used

### 🚢 Titanic Dataset
- Missing Value Analysis
- Categorical Feature Handling
- Feature Encoding

### 🛒 BigMart Sales Dataset
- Feature Engineering
- Categorical Variable Transformation
- Encoding Techniques

### 🚗 Mercedes-Benz Dataset
- High Cardinality Features
- Advanced Encoding Approaches
- Feature Representation Analysis

### 🏥 Smart Healthcare Dataset
- Data Cleaning
- Feature Transformation
- Preprocessing Workflow

---

## 📚 Libraries Used

```python
import pandas as pd
import numpy as np

from sklearn.preprocessing import (
    LabelEncoder,
    OneHotEncoder,
    OrdinalEncoder
)

import matplotlib.pyplot as plt
import seaborn as sns
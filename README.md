# Support Vector Machine Checkpoint

# 🎯 What You're Aiming For.
In this checkpoint, we are going to work on the 'Electric Vehicle Data' dataset that was provided by Kaggle as part of the Electric Vehicle Price Prediction competition.

### Dataset description: 
  This dataset contains information on the Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) that are currently registered with the Washington State Department of Licensing (DOL). This dataset was introduced as part of an official invitation-based competition on Kaggle. Our SVM model should answer the question "This is my car's model & make, along with a few other parameters, what price can this vehicle be brought or sold?”

### ➡️ Dataset link: [https://drive.google.com/file/d/1kZ299dY3rKLvvnfTsaPtfrUbZb7k31of/view?usp=sharing]

### ➡️ Columns Explanation: [https://www.kaggle.com/datasets/rithurajnambiar/electric-vehicle-data]

# ℹ️ Instructions:
1. **Import Data and Perform Basic Data Exploration:**
   - Load the dataset and explore its basic structure and statistics.
   - Display general information and summary statistics about the dataset.
   
2. **Data Preparation:**
   - Import the dataset and perform basic exploration.
   - Handle corrupted and missing values.
   - Encode categorical features.
   - Handle outliers and remove duplicates.
   - Select the target variable and feature set.
   - Split the dataset into training and test sets.
   
3. **Build and Train an SVM Model:**
   - Construct and train an SVM model on the training set.
   
4. **Evaluate Model Performance:**
   - Assess the model performance on the test set using relevant evaluation metrics.

# 🛠️ Tools and Libraries:
- Python: Core programming language
- Pandas: Data manipulation and analysis
- NumPy: Numerical computations
- Matplotlib: Data visualization
- Seaborn: Statistical data visualization
- SciPy: Scientific computing
- Scikit-learn: Machine learning algorithms

**Libraries Used:**
```python
import pandas as pd
import numpy as np
from sklearn.svm import SVR
from sklearn.ensemble import RandomForestRegressor
```

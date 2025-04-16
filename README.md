# Black-Friday-Purchase-Prediction 

### Overview
This project aims to predict whether a customer will make a high-value purchase (greater than ₹10,000) during the Black Friday sale using customer demographic data and product interactions. It's a classification project built using Python, pandas, scikit-learn, and visualized with Matplotlib and Seaborn.

###  Dataset Summary
The dataset contains transaction-level purchase data including:

- User_ID, Product_ID
- Gender, Age, Occupation
- City_Category, Stay_In_Current_City_Years
- Marital_Status
- Product_Category_1, 2, 3
- Purchase (target column)

### Problem Statement
The goal is to classify whether a purchase is high-value (Purchase > 10,000) or not. This is framed as a binary classification task.

###  Methodology
## Data Preprocessing:
Handling missing values

Encoding categorical variables (Gender, City_Category, etc.)

Mapping age ranges to numerical values

Converting the target column into binary

### Model
- RandomForestClassifier from scikit-learn
- Train-test split with evaluation metrics:
- Confusion Matrix
- Classification Report
- Accuracy Score

### Visualizations
 - Bar plot of purchases by age
- Pie chart of gender-based purchases
- Line plot of product category purchases
- Confusion matrix heatmap

### Results
The model demonstrates a good ability to classify high-value purchasers, which can help businesses in:

- Customer targeting
- Personalized marketing
- Sales forecasting


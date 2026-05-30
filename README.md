# 🍽️ Zomato Data Analysis Project

## 📌 Project Overview

This project focuses on analyzing Zomato restaurant data using **Python, Pandas, NumPy, Matplotlib, and Seaborn**. The objective is to perform data cleaning, exploratory data analysis (EDA), and visualization to uncover insights about restaurant types, customer preferences, ratings, votes, and ordering behavior.

---

## 🎯 Project Objectives

- Understand restaurant distribution across categories.
- Analyze customer voting patterns.
- Explore restaurant ratings.
- Identify average spending preferences of customers.
- Compare online and offline ordering performance.
- Discover relationships between restaurant types and order modes.

---

## 📂 Dataset Information

The dataset contains information about restaurants listed on Zomato, including:

- Restaurant Type
- Ratings
- Votes
- Approximate Cost
- Online Ordering Availability
- Customer Preferences
- Other Restaurant Attributes

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📋 Project Workflow

## Step 1: Importing Python Libraries

Imported the required libraries for:

- Data manipulation
- Data visualization
- Exploratory data analysis

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## Step 2: Load CSV Data

Loaded the Zomato dataset into a Pandas DataFrame for analysis.

```python
df = pd.read_csv("Zomato data.csv")
```

---

## Step 3: Data Cleaning

Performed data cleaning operations to prepare the dataset for analysis.

### ✔ Data Type Conversion

Converted the `rate` column into a numerical format for accurate analysis and visualization.

---

# 📊 Exploratory Data Analysis & Visualizations

The following business questions were explored during the analysis.

---

## Q1. What is the most common type of restaurant?

### Analysis
Examined the distribution of restaurant categories.

### Conclusion

✅ **Majority of restaurants fall under the Dining category.**

---

## Q2. How many votes does each restaurant type receive?

### Analysis
Compared customer votes across restaurant categories.

### Conclusion

✅ **Dining restaurants received the highest number of customer votes.**

---

## Q3. What ratings do most restaurants receive?

### Analysis
Studied the distribution of restaurant ratings.

### Conclusion

✅ **Most restaurants received ratings between 3.5 and 4.0.**

---

## Q4. What is the average spending preference of couples?

### Analysis
Analyzed approximate spending patterns.

### Conclusion

✅ **Most customers prefer restaurants with an average order cost of around ₹300.**

---

## Q5. Which ordering mode receives the highest ratings?

### Analysis
Compared ratings between online and offline ordering modes.

### Conclusion

✅ **Online orders receive higher ratings compared to offline orders.**

---

## 🔥 Heatmap Analysis

A heatmap was created to understand the relationship between restaurant type and ordering mode.

### Main Insights

| Restaurant Type | Preferred Order Mode |
|----------------|----------------------|
| Dining | Offline |
| Cafe | Online |
| Buffet | Online |
| Others | Online |

### Conclusion

✅ **Dining restaurants primarily receive offline orders, while Cafes, Buffets, and Other restaurant categories receive more online orders.**

---

# 📈 Visualizations Included

- Restaurant Type Distribution
- Votes by Restaurant Type
- Ratings Distribution
- Average Spending Analysis
- Online vs Offline Ratings Comparison
- Restaurant Type vs Order Mode Heatmap

---

# 📁 Project Structure

```text
ZOMATO-DATA-ANALYSIS-PROJECT/
│
├── Zomato Product Analysis Project.ipynb
├── Zomato data.csv
├── README.md
├── .gitignore
│
└── images/
    ├── restaurant_type_distribution.png
    ├── votes_by_restaurant_type.png
    ├── ratings_distribution.png
    ├── spending_analysis.png
    ├── online_offline_rating.png
    └── heatmap.png
```

---

# 🔍 Key Insights

- Dining is the most common restaurant category.
- Dining restaurants receive the highest number of customer votes.
- Most restaurants have ratings between 3.5 and 4.0.
- Customers generally prefer spending around ₹300 per order.
- Online ordering tends to receive better ratings.
- Cafes and Buffets show stronger online-ordering behavior compared to Dining restaurants.


# 🎓 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation
- Statistical Interpretation
- Pandas Data Manipulation

---

# 👨‍💻 Author

**Abhideepta**

MCA Student | Aspiring Data Scientist | Machine Learning & Generative AI Enthusiast

---

⭐ If you found this project useful, consider giving it a star on GitHub.
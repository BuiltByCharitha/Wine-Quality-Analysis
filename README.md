# Wine-Quality-Analysis
Detailed analysis of Wine Quality Dataset - Comparing various models 

## Project Overview

This project focuses on analyzing the Wine Quality Dataset using Data Science, Machine Learning, and Business Analytics techniques. The primary goal is to explore the relationship between different wine attributes and their quality, classified as good or bad.

## Dataset

The dataset consists of 11 independent features and a target column (`quality`), which has been encoded as:

- `1 → Good Quality`
- `0 → Bad Quality`

The dataset contains no missing values.
It is downloaded from - https://archive.ics.uci.edu/dataset/186/wine+quality

## Methodology

### Part A: Data Preprocessing & Exploratory Data Analysis (EDA)

- **Class Distribution**: The dataset is balanced, as there is no significant difference in the count of good and bad wine samples.
  
- **Feature Correlation**:
    - `sulphates` and `alcohol` show the highest positive correlation with wine quality.
    - Some independent features show significant inter-correlation, such as `citric acid` and `fixed acidity` (0.67), and a negative correlation between `pH` and `fixed acidity`.

### Part B: Model Building

- Machine Learning models were trained to classify wine quality.
- Performance metrics were used to evaluate model effectiveness.

## Results & Insights

- Key attributes that influence wine quality were identified.
- The analysis provides insights that can be useful for winemakers to improve wine quality.

## Tools & Libraries Used

- **Python**
- **Jupyter Notebook**
- **Pandas, NumPy** (Data Processing)
- **Matplotlib, Seaborn** (Visualization)
- **Scikit-learn** (Machine Learning Models)

## How to Run the Notebook

1. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

# Cryptocurrency-Price-Analysis-and-Prediction-2015-2024
## 📊 Overview
This repository explores historical cryptocurrency price trends, focusing on key metrics such as open prices, close prices, volume, and volatility from 2015 to 2024. The project applies data visualization and machine learning techniques to predict future price movements.

## Key features include:

- Data cleaning and transformation using Python libraries like pandas and numpy.
- Exploratory Data Analysis (EDA) with matplotlib and seaborn.
- Machine Learning Models to predict price increases or decreases.
- Outlier detection and removal using statistical methods.
## 🔍 Features
###  1️⃣ Data Analysis
    - Historical price trends from 2015 to 2024.
    - Visualization of metrics like open, close, high, low, and volume.
    - Outlier detection using IQR and visualization via boxplots and histograms.
## 2️⃣ Predictive Modeling
###   Feature engineering:
      - open-close: Difference between opening and closing prices.
      - low-high: Difference between the lowest and highest prices.
      - Target variable (1 for price increase, 0 for price decrease).
      - Classification using a Random Forest Classifier, achieving high accuracy.
      - Confusion matrix and classification report for model evaluation.
## 🚀 Getting Started
###   Prerequisites
      - Ensure you have the following installed: Python 3.8+
      - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `requests`, `beautifulsoup4`
## Installation
    - Clone this repository:
```bash
  git clone https://github.com/yourusername/crypto-price-analysis.git
## 🛠️ Usage
###  1️⃣ Data Collection
      - Modify the script to scrape data for your desired cryptocurrency: "ETH-USD" (I USE)

## 2️⃣ Run Analysis
Execute the Jupyter notebooks in the notebooks/ folder for:
    - Data preprocessing and visualization.
    - Predictive model training and evaluation.

## 📈 Results
**Accuracy:** Achieved a score of 1.00 using the Random Forest Classifier on the test dataset.
**Insights:**
Price movements are strongly influenced by historical price trends and trading volume.
Visualizations like boxplots and heatmaps help detect patterns and correlations.

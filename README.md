# Google Play Store Data Wrangling & EDA

## 📊 Project Overview
This project provides a comprehensive guide to data wrangling and exploratory data analysis (EDA) on the Google Play Store dataset. The goal is to prepare the data for building a regression model to predict app ratings. The notebook covers all essential steps, from data cleaning to feature engineering and encoding, with clear explanations and visualizations.

---

## 📁 Dataset
- **Source:** [Google Play Store on Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps)
- **File:** `Datasets/googleplaystore.csv`
- **Target Variable:** `Rating`

---

## 🛠️ Key Steps & Methods
1. **Data Loading & Exploration**
   - Import libraries and load the dataset
   - Inspect data structure, types, and summary statistics
2. **Data Cleaning**
   - Remove duplicates
   - Correct data types for each column
   - Handle missing values using appropriate imputation strategies
3. **Outlier Detection & Treatment**
   - Visualize distributions and identify outliers
   - Apply transformations (log, boxcox, yeo-johnson) to normalize skewed features
4. **Feature Engineering**
   - Create new features (e.g., `is_paid`, `Price_log`)
   - Drop redundant or problematic columns
5. **Categorical Analysis & Cleaning**
   - Analyze and clean categorical features
   - Remove erroneous categories and redundant columns
6. **Encoding**
   - Apply One-Hot Encoding to categorical variables for machine learning compatibility
7. **Exploratory Data Analysis (EDA)**
   - Univariate, bivariate, and multivariate analysis
   - Visualizations: histograms, boxplots, countplots, heatmaps, pairplots

---

## 📈 Results & Insights
- The dataset is thoroughly cleaned and transformed, ready for regression modeling.
- Outliers and data anomalies are handled with domain knowledge and statistical techniques.
- Feature engineering and encoding ensure the data is suitable for machine learning algorithms.

---

## 🚀 How to Use
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/google-playstore-eda.git
   cd google-playstore-eda
   ```
2. **Install Requirements**
   - Make sure you have Python 3.x installed.
   - Install required libraries:
     ```sh
     pip install pandas numpy matplotlib seaborn scikit-learn scipy missingno
     ```
3. **Run the Notebook**
   - Open `Dataset` in Jupyter Notebook or VS Code.
   - Run all cells to reproduce the analysis.

---

## 📝 Author
- **Rana Umar**

---

## 💡 Potential Enhancements
- Add a modeling section to train and evaluate regression models.
- Include more advanced feature engineering or hyperparameter tuning.
- Expand the README with example outputs or screenshots.

---

## ⭐ Project Value
This project demonstrates strong data wrangling, EDA, and feature engineering skills. It is a valuable addition to your portfolio and is ready to be showcased on GitHub.

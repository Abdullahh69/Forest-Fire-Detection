# 🌲 Forest Fire Prediction using Machine Learning

This project is part of an **Applied Machine Learning group assignment** focused on predicting forest fires in Algeria using historical weather data and machine learning techniques.

## 👥 Team Members

- Md Abdullah Mia (x7626122)  
- Md Ashikuzzaman Eshti (x5389574)  
- Abdullah Chaudhry (x7393734)  
- Muhammad Safi (x5032223)

## 📌 Objective

To analyze and model the **Algerian Forest Fires dataset** using Exploratory Data Analysis (EDA) and a set of machine learning algorithms, with the goal of predicting forest fire occurrences.

## 📂 Dataset

The dataset contains daily meteorological and fire data for two regions of Algeria — **Bejaia** and **Sidi Bel-Abbes**, from **June to September 2012**.

### Features include:
- **Date**: Day/Month/Year
- **Temperature**: Max temperature at noon (°C)
- **Relative Humidity (RH)**: %
- **Wind Speed (Ws)**: km/h
- **Rain**: mm
- **FWI System indices**: FFMC, DMC, DC, ISI, BUI, FWI
- **Region**
- **Class**: `fire` or `not fire`

## ⚙️ Project Structure

### 🔍 1. Exploratory Data Analysis (EDA)
- Identifying missing data
- Region-wise splitting
- Class distribution
- Monthly trend analysis
- Correlation heatmaps
- Temperature distribution

### 🧹 2. Data Preprocessing
- Label cleaning
- Missing value handling
- Feature encoding
- Scaling
- Train-test split

### 📊 3. Machine Learning Models
Implemented the following classifiers:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost (XGBClassifier)

### ⭐ 4. Feature Importance
Top important features for prediction:
- FFMC
- ISI
- FWI
- RH
- DMC

## ✅ Results

Each model was evaluated using **confusion matrices** and overall accuracy scores. The best performing model was chosen based on prediction accuracy and feature significance.

## 🧠 Conclusion

Machine Learning provides a powerful tool for early forest fire prediction. This proactive approach aids forest management agencies in preventing environmental and economic damage.

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies (e.g., `pandas`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`)
3. Run the notebook or script with the dataset

---

## 📈 Sample Output

- EDA visualizations (class distribution, temperature trends)
- Confusion matrices for each model
- Feature importance bar charts

---

## 📬 Contact

For questions or feedback, feel free to contact any of the team members listed above.

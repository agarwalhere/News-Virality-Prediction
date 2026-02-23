# 📰 News Virality Prediction

This project focuses on predicting whether a news article will go **viral** based on various content and metadata features. The dataset used is the **Online News Popularity Dataset** from UCI Machine Learning Repository.

---

## 📌 Project Overview

The goal of this project is to:
- Analyze features that influence news article popularity
- Perform feature engineering to improve model performance
- Build and evaluate machine learning models for **virality prediction**

A binary classification approach is used where:
- **Viral (1):** Article exceeds a certain popularity threshold  
- **Non-Viral (0):** Otherwise  

---

## 📂 Dataset

- Source: UCI Machine Learning Repository  
- Dataset: **Online News Popularity**
- Contains features like:
  - Number of words in the article
  - Number of images/videos
  - Keyword statistics
  - Social media engagement metrics

---

## ⚙️ Workflow

### 1. Data Loading & Cleaning
- Downloaded dataset programmatically
- Cleaned column names
- Removed irrelevant columns (`url`, `shares`)
- Created a **target variable (`viral`)**
- Handled missing values
- Split into training and testing sets

---

### 2. Exploratory Data Analysis (EDA)
- Visualized distributions of numerical features
- Identified:
  - Skewness
  - Outliers
- Generated correlation heatmaps to detect multicollinearity

---

### 3. Feature Engineering
- Created new meaningful features from existing ones
- Transformed skewed variables
- Selected relevant features to improve model performance

---

### 4. Model Building
- Applied machine learning algorithms (classification models)
- Trained models on processed dataset

---

### 5. Model Evaluation
- Evaluated using standard metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Compared performance before and after feature engineering

---

## 📊 Key Insights

- Feature engineering significantly improved model performance  
- Certain content-based features strongly influence virality  
- Removing highly correlated and irrelevant features improved generalization  

---

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries:**
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
- **Tools:** Jupyter Notebook  

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/news-virality.git
cd news-virality

# 🍷 Wine Quality Dataset - Exploratory Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on the [Wine Quality Dataset (Red Wine)](https://archive.ics.uci.edu/ml/datasets/Wine+Quality). The goal is to understand the data distribution, uncover relationships between features, detect outliers, and make preliminary inferences about factors influencing wine quality.

## 📁 Dataset

The dataset used is `winequality-white.csv`, `winequality-red.csv` which contains physicochemical properties of red wine samples along with quality ratings.

### Features

- `fixed acidity`, `volatile acidity`, `citric acid`, `residual sugar`, `chlorides`
- `free sulfur dioxide`, `total sulfur dioxide`, `density`, `pH`, `sulphates`
- `alcohol`
- `quality` (target variable: 0–10 rating scale)

---

## 📊 Project Structure

| Step | Description |
|------|-------------|
| 1️⃣ | Generate **summary statistics** (mean, median, std, etc.) |
| 2️⃣ | Create **histograms and boxplots** for numeric features |
| 3️⃣ | Visualize **feature relationships** via correlation matrix and pairplots |
| 4️⃣ | Identify **patterns, trends, and anomalies** |
| 5️⃣ | Make basic **feature-level inferences** from visual analysis |

## 📈 Visualizations

- 📦 **Boxplots** show outliers in `residual sugar`, `chlorides`, and `total sulfur dioxide`.
- 📊 **Histograms** display skewed distributions for several features.
- 🔍 **Correlation Matrix** reveals:
  - `alcohol` positively correlates with `quality`
  - `volatile acidity` negatively correlates with `quality`
  - `density` inversely related to `alcohol`

---

## 💡 Inferences

- Wines with higher **alcohol** tend to have better quality ratings.
- High **volatile acidity** generally results in poorer quality.
- Outliers in sulphates and residual sugar could influence model performance and need preprocessing.
---

## 📌 Author

**Vedant** — B.Tech Computer Science, ML Enthusiast  
*Open to collaborations in Data Science and AI projects!*
---

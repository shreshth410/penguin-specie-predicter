# 🐧 Demonstration of Exploratory Data Analysis on a Penguin Specie Dataset (DAIA4)

## 📘 Project Overview
This project explores **data analysis and machine learning techniques** using the *Palmer Penguins dataset*. The objective is to perform **data preprocessing**, **classification**, and **clustering** to understand the relationships between various penguin species and their characteristics.

The notebook demonstrates both **supervised** (Logistic Regression) and **unsupervised** (K-Means Clustering) learning workflows.

---

## 📂 Files
- **`DAIA4.ipynb`** — Jupyter Notebook containing all analysis, visualizations, and results.
- **`penguins.csv`** — Dataset used for training and analysis (must be placed in the correct directory).

---

## ⚙️ Requirements

Install the required Python libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

---

## 🧭 Workflow

1. **Data Loading and Exploration**
   - Reads the `penguins.csv` dataset using pandas.
   - Displays data statistics and identifies missing values.

2. **Data Cleaning**
   - Drops missing or null entries to ensure data consistency.
   - Encodes categorical variables using `LabelEncoder` and `OrdinalEncoder`.

3. **Feature Scaling**
   - Standardizes numerical features using `StandardScaler`.

4. **Modeling**
   - **Logistic Regression** is applied for species classification.
   - **K-Means Clustering** is used to group penguins based on feature similarity.

5. **Evaluation**
   - Uses metrics such as:
     - `accuracy_score`
     - `silhouette_score`
     - `adjusted_rand_score`
     - `normalized_mutual_info_score`
   - Confusion matrix for classification performance.

6. **Visualization**
   - Data distribution and model results are visualized using `Matplotlib` and `Seaborn`.

---

## 📊 Results Summary
- The Logistic Regression model achieved good accuracy in classifying penguin species.
- K-Means clustering effectively grouped species with reasonable cluster purity.
- Visual analysis confirmed strong separation between species based on key features.

---

## 🚀 How to Run

1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook DAIA4.ipynb
   ```
2. Execute cells sequentially from top to bottom.
3. Ensure that the dataset path in the code matches your local setup.

---

## 🧠 Concepts Demonstrated
- Data Cleaning & Preprocessing  
- Feature Scaling  
- Classification (Supervised Learning)  
- Clustering (Unsupervised Learning)  
- Model Evaluation & Visualization  

---

## 🏁 Conclusion
This notebook demonstrates end-to-end data analysis — from **data cleaning** to **machine learning model evaluation** — using the Palmer Penguins dataset. It serves as a practical exercise in applying core data science techniques to real-world biological data.

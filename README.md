# 🌍 Global Pollution Analysis and Energy Recovery

## 📌 Overview
This project classifies countries into **Low, Medium, or High** pollution severity categories using machine learning models (Naive Bayes, KNN, Decision Tree). It analyzes pollution levels, energy consumption, and environmental factors to provide actionable insights.

---

## 🛠️ Features
- **Data Preprocessing**: Handles missing data, feature scaling, and categorical encoding.
- **Feature Engineering**: Creates new metrics like `Total_Pollution_Index` and `Energy_Recovery_Rate`.
- **Machine Learning Models**:
  - **Naive Bayes**: Simple probabilistic classifier.
  - **KNN**: Finds optimal neighbors for classification.
  - **Decision Tree**: Interpretable model with feature importance.
- **Evaluation**: Compares models using accuracy, F1-score, and confusion matrices.
- **Visualizations**: Pollution distribution, model performance, and top polluted countries.

---

## 📂 Files
- `Global_Pollution_Analysis.csv`: Dataset with pollution and energy metrics.
- `pollution_classification.ipynb`: Jupyter Notebook with full code and analysis.

---

## 🚀 Quick Start
1. **Clone the repo**:
   ```bash
   git clone https://github.com/your-username/global-pollution-analysis.git
   ```
2. **Install dependencies**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. **Run the notebook**:
   ```bash
   jupyter notebook pollution_classification.ipynb
   ```

---

## 📊 Results
- **Best Model**: Decision Tree (highest accuracy and F1-score).
- **Key Insights**:
  - Top polluted countries need urgent policy changes.
  - Energy recovery efficiency varies significantly across nations.


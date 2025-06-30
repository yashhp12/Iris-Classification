# 🌸 Iris Flower Classification using Python (Pandas + Matplotlib + Seaborn)

A machine learning project to classify Iris flower species based on sepal and petal measurements. This is a beginner-friendly project demonstrating data exploration, visualization, and model training using the classic Iris dataset.

---

## 📁 Dataset

- **Name**: Iris Flower Dataset
- **Source**: [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/iris) or Kaggle
- **Features**:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
  - Species (Setosa, Versicolor, Virginica)

---

## 🧰 Tools & Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (if you did classification)

---

## 🔍 Key Steps in the Project

1. **Loaded the dataset** using `pandas.read_csv()`
2. **Dropped unnecessary columns** (e.g., `Id`)
3. **Exploratory Data Analysis (EDA)**:
   - Statistical summary using `.describe()`
   - Correlation heatmap
   - Pair plots to understand class separability
4. **Data Visualization**:
   - Box plots for feature distribution
   - Scatter plots to view separability between classes
5. **(Optional)** Classification:
   - Trained a model (e.g., Logistic Regression or KNN)
   - Evaluated model accuracy and predictions

---

## 📊 Sample Insights

- 🌸 Setosa is linearly separable from other classes based on petal measurements.
- 📈 Petal length and width are strong predictors of species.
- 🧪 Simple classifiers can achieve high accuracy (~95%+) on this dataset.

---

# 🍷 Wine Quality Prediction using Machine Learning

## 📌 Project Overview

This project focuses on **analyzing and predicting the quality of red wine** using **data analysis and machine learning techniques**. By studying the relationship between **physicochemical properties** of wine and its **quality score**, the project aims to identify key factors influencing wine quality and build predictive models.

The project is implemented in **Python** using a Jupyter Notebook: `wine quality.ipynb`, and is suitable for **data science learners, ML enthusiasts, and portfolio demonstration**.

---

## 🎯 Objectives

* Perform **exploratory data analysis (EDA)** on wine quality data
* Understand how chemical attributes affect wine quality
* Build and evaluate **machine learning models** for quality prediction
* Compare model performance using evaluation metrics
* Draw meaningful business and analytical insights

---

## 📂 Project Structure

```
├──Wine-Quality-Analysis/
│
├── Data/
│   └── wineQualityReds.csv
│
├── Notebooks/
│   └── Wine_Quality.ipynb
│
├── outputs/
│   ├── count_plot_quality.png
│   ├── correlation_heatmap.png
│   ├── alcohol_vs_quality.png
│   └── eda_visualizations.png
│
├── README.md
│
```

---

## 🧾 Dataset Information

* **Source:** UCI Machine Learning Repository
* **Dataset:** Red Wine Quality Dataset
* **Records:** 1,599 samples
* **Target Variable:** `quality` (score between 0 and 10)

### 🔬 Features Description

| Feature              | Description                        |
| -------------------- | ---------------------------------- |
| fixed acidity        | Non-volatile acids in wine         |
| volatile acidity     | Acetic acid content                |
| citric acid          | Freshness indicator                |
| residual sugar       | Sugar remaining after fermentation |
| chlorides            | Salt content                       |
| free sulfur dioxide  | SO₂ that prevents microbial growth |
| total sulfur dioxide | Total SO₂ content                  |
| density              | Density of wine                    |
| pH                   | Acidity level                      |
| sulphates            | Wine preservative                  |
| alcohol              | Alcohol percentage                 |
| quality              | Wine quality score (target)        |

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA phase includes:

* Checking **missing values and data types**
* Statistical summary using `describe()`
* Distribution analysis of numerical features
* Correlation heatmap to identify strong relationships
* Insights on how alcohol, sulphates, and acidity affect quality

📊 **Key Observations:**

* Alcohol shows a **strong positive correlation** with wine quality
* Volatile acidity has a **negative impact** on quality
* Most wines fall between **quality scores 5 and 6**

---

## 🤖 Machine Learning Models Used

The following models were implemented and evaluated:

* **Logistic Regression / Linear Regression**
* **Decision Tree Classifier**
* **Random Forest Classifier**
* *(Optional extensions: KNN, SVM)*

### ⚙️ Model Workflow

1. Feature-target separation
2. Train-test split
3. Feature scaling (where required)
4. Model training
5. Model evaluation

---

## 📈 Model Evaluation Metrics

Models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision, Recall, F1-Score
* Cross-validation (if applied)

🏆 **Best Performing Model:** Random Forest (based on accuracy and stability)

---

## 🛠️ Technologies & Libraries

* **Programming Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries Used:**

  * NumPy
  * Pandas
  * Matplotlib
  * Seaborn
  * Scikit-learn

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/Wine-Quality-Prediction.git
```

2. Navigate to the project directory
3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run `wine quality.ipynb` cell by cell

---

## 📌 Results & Insights

* Chemical properties significantly influence wine quality
* Higher alcohol and sulphate levels generally improve quality
* Machine learning models can effectively predict wine quality with good accuracy


## 👩‍💻 Author

**Sravani Thammineni**
Aspiring Data Analyst / Data Scientist

---

## ⭐ Acknowledgements

* UCI Machine Learning Repository
* Scikit-learn Documentation
* Kaggle & Open-source community

---

⭐ *If you find this project useful, feel free to star the repository!*
 # Wine-Quality-Analysis
The Wine Quality Analysis project examines how chemical characteristics affect wine quality ratings. By analyzing real-world wine data, the project uncovers key factors that contribute to high-quality wines using data analysis and visualization techniques.

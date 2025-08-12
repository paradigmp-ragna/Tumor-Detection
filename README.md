# Tumor Detection Project

## 📌 Overview
This project focuses on detecting whether a tumor is malignant or benign using patient diagnostic data.  
The main objective is to apply data analysis and machine learning techniques to classify tumors accurately, which can support early detection and medical decision-making.

## 📂 Project Structure
- **Tumor Detection.ipynb** – Jupyter Notebook containing:
  - Data loading and exploration
  - Cleaning and preprocessing
  - Exploratory Data Analysis (EDA)
  - Model training and testing
  - Performance evaluation
- **dataset.csv** *(not included here)* – Dataset containing tumor features and labels.

## 🛠️ Technologies Used
- **Python 3**
- **Pandas** – Data handling and preprocessing
- **NumPy** – Numerical operations
- **Matplotlib / Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models and evaluation tools

## 📊 Workflow
1. **Load Data** – Import dataset into a Pandas DataFrame.
2. **Preprocessing** – Handle missing values, encode categorical data, normalize numerical features.
3. **EDA** – Visualize feature distributions and correlations.
4. **Modeling** – Train classification models such as Logistic Regression, Decision Tree, and Random Forest.
5. **Evaluation** – Measure performance using accuracy, precision, recall, F1-score, and confusion matrix.

## 🔍 Key Insights
- Certain features such as mean radius, texture, and smoothness strongly influence tumor classification.
- The Random Forest classifier provided the highest accuracy and balanced performance.

## 🚀 How to Run
1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

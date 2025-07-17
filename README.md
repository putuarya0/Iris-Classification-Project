# Iris Classification Project

This project uses the classic Iris flower dataset to build and evaluate machine learning models that classify Iris flowers into three species.

## 📊 Dataset

The Iris dataset consists of 150 records and includes the following features:

- `sepal length (cm)`
- `sepal width (cm)`
- `petal length (cm)`
- `petal width (cm)`
- `species` (target)

## 🔍 Objective

To train and evaluate classifiers that can accurately predict the species of an Iris flower based on its features.

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib, Seaborn
- Scikit-learn

## ⚙️ ML Workflow

1. **Data Loading**  
   Load `iris.csv` using Pandas.

2. **Exploratory Data Analysis**  
   Use `.info()`, `.describe()`, and `.sample()` to understand the structure and distribution of the data.

3. **Preprocessing**  
   Feature scaling using `StandardScaler`.

4. **Model Training**  
   - Logistic Regression
   - K-Nearest Neighbors (KNN)

5. **Evaluation Metrics**  
   - Accuracy
   - Confusion Matrix
   - Precision, Recall, F1-Score

## 📈 Results

Both models are evaluated using accuracy and classification metrics. Based on the simplicity and separability of the Iris dataset, models like Logistic Regression and KNN perform well.

## 📁 Files

- `iris.ipynb`: Jupyter notebook containing the complete analysis and model training.
- `iris.csv`: The dataset used for training/testing.

## 🧠 Credits

- Dataset: UCI Machine Learning Repository
- Author: [Your Name]

# ML Pipeline Project (Synthetic Dataset)

## 📌 Project Overview
This project demonstrates a complete Machine Learning pipeline using a synthetic student dataset. It includes data generation, preprocessing, EDA, feature engineering, model training, and evaluation using proper Git version control.

---

## 📊 Dataset
- Synthetic dataset (student performance)
- Target variable: `Pass` (0 = Fail, 1 = Pass)

---

## ⚙️ Steps Performed (MLDLC)

### 1. Data Generation
- Created synthetic dataset using Python

### 2. Data Gathering
- Loaded dataset using pandas
- Checked structure and summary

### 3. Data Preprocessing
- Handled missing values
- Cleaned data

### 4. Exploratory Data Analysis (EDA)
- Analyzed distributions
- Checked correlations

### 5. Feature Engineering
- Created new features:
  - TotalMarks
  - AverageMarks
  - StudyEfficiency

### 6. Model Training
- Used Logistic Regression

### 7. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 🌿 Branching Strategy
- `main` → Basic ML pipeline
- `sahib` → Improved ML pipeline with enhancements

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Git & GitHub

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python main.py
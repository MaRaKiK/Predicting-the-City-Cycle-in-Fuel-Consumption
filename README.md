# Predicting-the-City-Cycle-in-Fuel-Consumption

# 🚗 Fuel Efficiency Classification

## 📌 Project Overview
This project focuses on developing a **Proof of Concept (POC) for predicting fuel efficiency (MPG)** based on vehicle attributes. The goal is to assist **car rental companies** in making informed fleet updates. Initially a regression problem, the dataset is now reframed into a **classification task**, categorizing vehicles into **low, medium, and high fuel efficiency**.

## 📂 Dataset
- **Source**: Auto MPG Dataset (398 instances, 8 attributes) (mpg.data.xlsx)
- **Attributes**:
  - `mpg` (target, converted to categorical: Low, Medium, High)
  - `cylinders`, `displacement`, `horsepower`, `weight`, `acceleration`, `model year`, `origin`, `car name`

## 🛠 Project Workflow
### 🔍 1. Exploratory Data Analysis (EDA)
- Investigating of data distribution and patterns
- Visualizing trends using graphs like boxplots, scatter plots, correlation maps.
- Identifying missing values & outliers

📌 **Deliverable**: `D01_ Exploratory Data Analysis.ipynb` [D01_ Exploratory Data Analysis.ipynb] (https://colab.research.google.com/drive/1gPD8ems-U4O63ywihd1C644mmFLoz5qc?authuser=1#scrollTo=3gkUfcx1Z8r0)

---

### ⚙️ 2. Data Preprocessing
- Handling missing values
- Check for duplicated values
- Encoding categorical features
- Feature scaling & selection
- Outlier detection & removal

📌 **Deliverable**: `D02_Preprocessing.ipynb` [D02_Preprocessing.ipynb](https://colab.research.google.com/drive/114H7a4XymcgdKyaq9JHHNF9buoe5_LfB?authuser=1#scrollTo=zgYepZ5qwb1L&line=1&uniqifier=1)

---

### 🤖 3. Model Development & Evaluation
- Implementing **classification models** using `scikit-learn`
- Training, hyperparameter tuning, cross-validation
- Evaluating using appropriate metrics (accuracy, F1-score, etc.)

📌 **Deliverables**: `D03_Model_Training.ipynb`, `D03_Model_Evaluation.ipynb`, `D03_Predictions.ipynb`

---

## 🚀 How to Run the Project
### 🔧 Prerequisites
Ensure you have the following installed:
```bash
pip install -r requirements.txt
```

### ▶️ Run the Notebooks
1. Open Jupyter Notebook or Google Colab
2. Execute the notebooks in the following order:
   - `D01_EDA.ipynb`
   - `D02_Preprocessing.ipynb`
   - `D03_Model_Training.ipynb`
   - `D03_Model_Evaluation.ipynb`

---

## 📁 Repository Structure
```
📦 Fuel-Efficiency-Prediction
 ├── 📂 data               # Dataset & processed files
 ├── 📂 notebooks          # Jupyter notebooks for each stage
 ├── 📂 models             # Saved model files
 ├── 📜 requirements.txt   # Dependencies
 ├── 📜 README.md          # Project Documentation
```

---

## 🏆 Team & Contributions
This project was developed as part of a **Data Science & Business Intelligence Bootcamp** in collaboration with **WeLead x Code.hub**.

👥 **Team Members**:
- [Your Name](https://github.com/yourgithub)  

🔗 **Find us on GitHub**: [Repository Link](https://github.com/your-repo)

---

## 📢 Final Presentation & Submission
- **Submission Deadline**: 24 February
- **Presentation Format**: To be discussed in class
- **Final Submission**: Uploaded to GitHub main branch & MS Teams

---

📌 *This repository showcases the practical application of data science techniques in real-world business scenarios. Feel free to explore and contribute!* 🚀

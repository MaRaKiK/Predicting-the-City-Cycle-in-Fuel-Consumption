# Predicting-the-City-Cycle-in-Fuel-Consumption

# 🚗 Fuel Efficiency Classification

## 📌 Project Overview
This project focuses on developing a **Proof of Concept (POC) for predicting fuel efficiency (MPG)** based on vehicle attributes. The goal is to assist **car rental companies** in making informed fleet updates. Initially a regression problem, the dataset is now reframed into a **classification task**, categorizing vehicles into **low, medium, and high fuel efficiency**.

## 📂 Dataset
The project is developed based on [Code.Hub - Group Project - WE LEAD - Bootcamp on Data Science & Business Intelligence (1).pdf] file's requirements. 

- **Source**: Auto MPG Dataset (398 instances, 8 attributes) (mpg.data.xlsx)
- **Attributes**:
  - `mpg` (target, converted to categorical: Low, Medium, High)
  - `cylinders`, `displacement`, `horsepower`, `weight`, `acceleration`, `model year`, `origin`, `car name`

## 🛠 Project Workflow
### 🔍 1. Exploratory Data Analysis (EDA)
- Investigating of data distribution and patterns
- Visualizing trends using graphs like boxplots, scatter plots, correlation maps.
- Identifying missing values & outliers

📌 **Deliverable**: `D01_ Exploratory Data Analysis.ipynb` [D01_ Exploratory Data Analysis.ipynb](https://colab.research.google.com/drive/1gPD8ems-U4O63ywihd1C644mmFLoz5qc?authuser=1#scrollTo=3gkUfcx1Z8r0)

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
- Evaluating using appropriate metrics (accuracy, F1-score, precision, recall etc.)

📌 **Deliverables**: `D03_01 Decision Tree.ipynb` [D03_01 Decision Tree.ipynb](https://colab.research.google.com/drive/1q9dSU0PASsEoQv2ksQLQZOEAKyEOk6kT?authuser=1#scrollTo=SdvHVRSx64WX&line=1&uniqifier=1), `D03_02 KNN - Balanced.ipynb` [D03_02 KNN - Balanced.ipynb](https://colab.research.google.com/drive/14eExd_iME3twV2YZ1kFiDOL2cdvGsDig?authuser=1#scrollTo=SdvHVRSx64WX&line=1&uniqifier=1), `D03_02 KNN.ipynb` [D03_02 KNN.ipynb](https://colab.research.google.com/drive/1owNwwJzs_op0Gj5DWQ4SI4CS1oQOT7ph?authuser=1#scrollTo=SdvHVRSx64WX&line=1&uniqifier=1), `D03_03 Logistic Regression.ipynb` [D03_03 Logistic Regression.ipynb](https://colab.research.google.com/drive/1Xllzo7byskgdDmzYl_FGkpwI3l4gncp_?authuser=1#scrollTo=SdvHVRSx64WX&line=1&uniqifier=1),`D03_04 Decision Tree - Balanced.ipynb` [D03_04 Decision Tree - Balanced.ipynb](https://colab.research.google.com/drive/1XAFCUEJ_zvKHLjsp1ytOzkHQNf_WhWoJ?authuser=1#scrollTo=SdvHVRSx64WX&line=1&uniqifier=1), `D03_05 XGBoost .ipynb` [D03_05 XGBoost .ipynb](https://colab.research.google.com/drive/1atqWSEBD337oJrhuN83986bmusrkEzcO?authuser=1#scrollTo=R-Ydxa3vr5hn&line=1&uniqifier=1), `D03_06 Logistic Regression - Balanced.ipynb` [D03_06 Logistic Regression - Balanced.ipynb](https://colab.research.google.com/drive/1Srz-eF2x1xR587IOka6DICNtGGZd_dHa?authuser=1#scrollTo=SdvHVRSx64WX&line=1&uniqifier=1), `D03_Cross_Validation_Log_Reg_Balanced.ipynb` [D03_Cross_Validation_Log_Reg_Balanced.ipynb](https://colab.research.google.com/drive/1LgRkQPi7K10_h1Ct2OL7D276R39Pt7cj?authuser=1#scrollTo=DIMz85yuqss_&line=1&uniqifier=1), `Cross Validation KNN - Balanced.ipynb` [Cross Validation KNN - Balanced.ipynb](https://colab.research.google.com/drive/15FV11IJ35Geo8EoKLD6fIOLoFqcGyh9N?authuser=1#scrollTo=SdvHVRSx64WX&line=1&uniqifier=1)

---

## 🚀 How to Run the Project
### 🔧 Using Google Colad
Ensure you only have download locally the mpg.data.xlsx file

### ▶️ Run the Notebooks
1. Open each one of the deliverables using Google Colab
2. Execute the notebooks in the following order (by clicking on run in each kernel of every file starting from the top to the bottom of every file):
   - `D01_ Exploratory Data Analysis.ipynb`
   - `D02_Preprocessing.ipynb`
   - `D03_02 KNN.ipynb`
   - `D03_02 KNN - Balanced.ipynb`
   - `Cross Validation KNN - Balanced.ipynb`
  
P.S For every algorithm you choose to run the order should be the same, Exploratory Data Analysis at first, Preprocessing as a second step, run the algorithm you choose as third step, and for the last step you should run a Cross validation if the file exists.

---

## 📁 Repository Structure
```
📦 Fuel-Efficiency-Prediction
 ├── 📂 data               # mpg.data.xlsx
 ├── 📂 notebooks          # Jupyter notebooks for each stage
 ├── 📜 README.md          # Project Documentation
```

---

## 🏆 Team & Contributions
This project was developed as part of a **Data Science & Business Intelligence Bootcamp** in collaboration with **WeLead x Code.hub**. This project developed in a team of 5 members. Angeliki, Dimitra, Irida, Magda, Maria  

🔗 **Find me on GitHub**: [Maria Kosmarika](https://github.com/MaRaKiK)

---

📌 *Dive into real-world data science for business! This repository showcases practical applications and is open to your contributions and ideas too!* 🚀

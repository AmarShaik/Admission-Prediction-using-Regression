#Admission Prediction using Regression

This project uses **Linear Regression** to predict the chances of a student’s admission into a university based on their academic profile.  
It was created as part of a class exercise to understand how regression models work in machine learning.

---

## Project Overview
The goal of this project is to predict the **Chance of Admit** (between 0 and 1) based on various features such as GRE, TOEFL, CGPA, and more.  
We use the **Admission_Predict_Ver1.1.csv** dataset and apply **Linear Regression** from scikit-learn.

---

## Dataset Description
The dataset contains student profiles with the following columns:

- **GRE Score** – Graduate Record Exam score (out of 340)  
- **TOEFL Score** – Test of English as a Foreign Language score (out of 120)  
- **University Rating** – University prestige rating (1–5)  
- **SOP** – Statement of Purpose strength (1–5)  
- **LOR** – Letter of Recommendation strength (1–5)  
- **CGPA** – Undergraduate GPA (out of 10)  
- **Research** – Research experience (0 = No, 1 = Yes)  
- **Chance of Admit** – Target variable (0–1 probability)

---

##  Steps in the Notebook
1. **Import Libraries** – pandas, numpy, matplotlib, scikit-learn  
2. **Load Dataset** – `Admission_Predict_Ver1.1.csv`  
3. **Data Cleaning** – Drop unnecessary columns (`Serial No.`)  
4. **Split Data** – Train (80%) and Test (20%) sets  
5. **Train Model** – Linear Regression is applied  
6. **Make Predictions** – Predict admission chances on test data  
7. **Evaluate Model** – Using R² score  
8. **Visualize** – Scatter plot of Actual vs Predicted chances

---

## Model Performance
- Evaluation Metric: **R² Score**  
- The scatter plot shows how close predictions are to the actual values.  
- Higher R² means better accuracy.

---

## How to Run

### 1. Clone this repository
```bash
git clone https://github.com/<your-username>/Admission_Prediction_using_Regression.git

### 2. Install dependencies

pip install pandas numpy matplotlib scikit-learn

### 3. Open the Jupyter Notebook

jupyter notebook Admission_Prediction_using_Regression.ipynb

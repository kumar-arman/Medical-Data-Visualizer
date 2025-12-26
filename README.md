# Medical Data Visualizer

This project analyzes and visualizes medical examination data using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**.  
It is part of the **freeCodeCamp – Data Analysis with Python Certification**.

---

## 📌 Project Objective

The objective of this project is to explore relationships between:
- Cardiovascular disease
- Body measurements
- Blood test results
- Lifestyle choices

The analysis is performed using data visualization techniques and statistical correlations.

---

## 📊 Dataset Information

- Dataset Name: `medical_examination.csv`
- Source: freeCodeCamp / UCI Medical Examination Dataset
- Each row represents a patient
- Columns include:
  - Age (in days)
  - Height (cm)
  - Weight (kg)
  - Blood pressure (systolic & diastolic)
  - Cholesterol and glucose levels
  - Lifestyle indicators (smoking, alcohol, physical activity)
  - Presence of cardiovascular disease (`cardio`)

---

## 🛠️ Technologies Used

- Python 3.11
- Pandas
- Matplotlib
- Seaborn
- NumPy
- VS Code
- Git & GitHub

---

## 📂 Project Structure

medical-data-visualizer/
│
├── medical_examination.csv
├── medical_data_visualizer.py
├── main.py
├── README.md
└── .gitignore


---

## ⚙️ Features Implemented

### 1. Data Preprocessing
- Added an **overweight** column using BMI calculation
- Normalized cholesterol and glucose values:
  - 0 → good
  - 1 → bad

### 2. Categorical Data Visualization
- Created a categorical bar plot showing:
  - Cholesterol
  - Glucose
  - Smoking
  - Alcohol intake
  - Physical activity
  - Overweight status
- Compared distributions for patients with and without cardiovascular disease

### 3. Heat Map Visualization
- Cleaned incorrect and extreme data values
- Generated a correlation matrix
- Visualized correlations using a heatmap

---

## ▶️ How to Run the Project

Make sure **Python 3.11** is installed.

### Install dependencies:
```bash
py -3.11 -m pip install pandas matplotlib seaborn numpy
Run the project:
py -3.11 main.py

📈 Output

After running the project, the following files are generated:

catplot.png → Categorical bar plot

heatmap.png → Correlation heat map

These plots visually summarize key medical insights.

🎯 Key Learnings

Data cleaning and preprocessing

BMI calculation and feature engineering

Data reshaping using pd.melt()

Grouping and aggregation

Data visualization using Seaborn and Matplotlib

Correlation analysis

Working with real-world datasets

📤 Submission

This project is submitted as part of the freeCodeCamp Data Analysis with Python Certification.

📜 License

This project is open-source and intended for educational purposes.


---

# 💾 SAVE THE FILE
Press:


Ctrl + S


---

# 📤 COMMIT & PUSH README TO GITHUB

Run these commands:

```bash
git add README.md
git commit -m "Added README for Medical Data Visualizer"
git push origin main

# 🏥 Hospital Patient Data Analysis

## 📌 Project Overview

The Hospital Patient Data Analysis project is developed using Python, Pandas, and Matplotlib to analyze hospital patient records. The project processes patient data, performs data cleaning, and generates insights about disease distribution, age groups, and admission trends. It also visualizes the results using charts for better understanding and decision-making.

This project demonstrates fundamental data analytics techniques including data preprocessing, exploratory data analysis (EDA), and data visualization.

---

## 🎯 Objectives

* Analyze patient records efficiently.
* Identify the most common diseases.
* Categorize patients into age groups.
* Determine peak admission periods.
* Generate visual reports using charts.
* Practice data analytics using Python.

---

## 📂 Dataset Information

The dataset contains hospital patient records with the following attributes:

| Column Name    | Description                       |
| -------------- | --------------------------------- |
| Patient_ID     | Unique patient identifier         |
| Age            | Patient age                       |
| Disease        | Diagnosed disease                 |
| Gender         | Patient gender                    |
| Admission_Date | Date of hospital admission        |
| Stay_Days      | Number of days stayed in hospital |

### Sample Dataset

```csv
Patient_ID,Age,Disease,Gender,Admission_Date,Stay_Days
1,25,Fever,Male,2024-01-05,3
2,45,Diabetes,Female,2024-01-10,5
3,67,Heart Disease,Male,2024-02-12,10
```

---

## 🛠 Technologies Used

* Python
* Pandas
* Matplotlib
* CSV Dataset
* Jupyter Notebook / VS Code

---

## ⚙️ Features

### Data Cleaning

* Removes duplicate records.
* Handles missing values.
* Converts admission dates into datetime format.

### Disease Analysis

* Counts patients by disease.
* Identifies the most common disease.

### Age Group Analysis

Patients are categorized into:

* Children
* Young Adults
* Adults
* Senior Adults
* Elderly

### Admission Trend Analysis

* Calculates monthly admissions.
* Identifies peak admission month.

### Data Visualization

* Bar Chart for disease distribution.
* Pie Chart for age group distribution.
* Line Chart for monthly admission trends.

---

## 📊 Output

### Disease Count Analysis

Displays the number of patients affected by each disease.

### Age Group Distribution

Shows patient distribution across different age categories.

### Peak Admission Month

Determines the month with the highest number of admissions.

### Summary Report

Provides:

* Total Patients
* Most Common Disease
* Peak Admission Month

---

## 📈 Visualizations

The project generates:

1. Patient Count by Disease (Bar Chart)
2. Patient Distribution by Age Group (Pie Chart)
3. Monthly Patient Admissions Trend (Line Chart)

---

## 🚀 How to Run

### Install Required Libraries

```bash
pip install pandas matplotlib
```

### Run the Project

```bash
python hospital_patient_analysis.py
```

---

## 📁 Project Structure

```text
Hospital-Patient-Data-Analysis/
│
├── hospital_patient_analysis.py
├── hospital_patients.csv
├── README.md
└── screenshots/
    ├── dataset_preview.png
    ├── disease_chart.png
    ├── age_group_chart.png
    └── admission_trend.png
```

---

## ⚠️ Challenges Faced

* Handling date formatting correctly.
* Organizing patient records for analysis.
* Creating meaningful visualizations.
* Categorizing age groups accurately.

---

## 📚 Learning Outcomes

### Technical Skills

* Python Programming
* Pandas Data Analysis
* Data Cleaning
* Data Visualization
* CSV File Handling

### Practical Experience

* Working with healthcare datasets.
* Performing exploratory data analysis.
* Generating business insights from data.
* Creating professional project documentation.

---

## ✅ Conclusion

The Hospital Patient Data Analysis project successfully analyzes hospital patient records and provides valuable insights regarding disease prevalence, age distribution, and admission trends. The use of Python, Pandas, and Matplotlib enables efficient data processing and visualization. This project demonstrates how data analytics can support healthcare management and improve decision-making through data-driven insights.

---

## 👨‍💻 Author

Mani Kanda

Python Data Analytics Project

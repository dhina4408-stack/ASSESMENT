# 📊 Indian Startup Funding Analysis – Week 2 Assessment

## 📌 Project Overview

This project is part of **The Unlox Academy – Week 2 Assessment**. The objective is to perform **Data Cleaning, Exploratory Data Analysis (EDA), and Business Insights** using the **Indian Startup Funding** dataset with Python and Pandas.

The dataset contains funding information for Indian startups, including company names, cities, industries, funding stages, investment amounts, investors, funding dates, and founded years. The data contains intentionally messy values that require preprocessing before analysis.

---

## 🎯 Objectives

- Load and inspect a real-world CSV dataset.
- Clean and standardize inconsistent data.
- Handle missing values and duplicate records.
- Convert text-based values into usable numeric and datetime formats.
- Perform filtering, transformation, aggregation, and grouping.
- Generate business insights from startup funding data.

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- NumPy
- Google Colab / Jupyter Notebook

---

## 📂 Dataset

**Dataset Name:**

`indian_startups_fundingDADS.csv`

The dataset contains approximately **468 startup funding records** with information such as:

- Startup Name
- City
- Industry
- Funding Stage
- Funding Amount
- Funding Date
- Investors
- Founded Year

---

## 🧹 Data Cleaning Performed

The following preprocessing steps were completed before analysis:

- Renamed columns to snake_case format.
- Removed leading and trailing spaces.
- Standardized startup and city names.
- Standardized city aliases:
  - Bangalore → Bengaluru
  - BLR → Bengaluru
  - Bombay → Mumbai
  - Gurgaon → Gurugram
  - Delhi → New Delhi
  - Calcutta → Kolkata
  - Madras → Chennai
- Standardized industry names.
- Standardized funding stage names.
- Cleaned funding amount by removing:
  - ₹
  - INR
  - Cr
  - Crore
  - Commas
- Converted funding amount into numeric values.
- Converted funding dates into datetime format.
- Removed duplicate records.

---

## 📈 Analysis Performed

### Data Inspection

- Dataset dimensions
- Missing value analysis
- Duplicate record detection
- Column inspection
- Statistical summary

### Data Cleaning Verification

- Unique city names
- Industry distribution
- Funding stage distribution
- Funding amount statistics
- Funding year analysis

### Filtering Operations

- Bengaluru startups with funding above ₹100 Cr
- Startups in Fintech, Edtech, and HealthTech
- Startups founded between 2015–2020
- Startup names containing "pay"

### Feature Engineering

- Funding Efficiency
- Funding Tier Classification
- Startup Era Classification
- Investor Count

### Grouping & Aggregation

- Average funding by industry
- City-wise funding statistics
- Highest funded industry
- Funding tier distribution
- Highest funded startup in each industry

### Business Insights

- Emerging startup identification
- Investor hub analysis
- Market saturation analysis

---

## 📚 Concepts Covered

- Data Loading
- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- String Operations
- Data Type Conversion
- Filtering
- Sorting
- GroupBy
- Aggregation
- Apply & Lambda Functions
- Crosstab
- Feature Engineering
- Exploratory Data Analysis (EDA)

---

## 🚀 How to Run

1. Clone the repository.

```bash
git clone <repository-link>
```

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Upload the dataset:

```
indian_startups_fundingDADS.csv
```

4. Run the notebook from top to bottom.

---

## 📁 Project Structure

```
Indian-Startup-Funding-Analysis/
│
├── Week2_Assessment_DhinaKaran.ipynb
├── indian_startups_fundingDADS.csv
├── README.md
└── screenshots/ (optional)
```

---

## 📌 Learning Outcomes

This project demonstrates practical skills in:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Business-oriented data analysis
- Pandas data manipulation
- Real-world dataset cleaning
- Analytical thinking using Python

---

## 👨‍💻 Author

**Dhina Karan**

M.Tech – Computer Science & Engineering

The Unlox Academy – Data Analytics & Data Science Program

---

## 📜 License

This project is created for educational purposes as part of The Unlox Academy Week 2 Assessment.

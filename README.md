# 🌍 Travel Analytics Agent

An AI-powered Travel Analytics Agent built using Python, Pandas, Matplotlib, and Excel Automation.

The agent automatically analyzes travel datasets and generates insights about traveler preferences, destinations, budgets, transportation methods, and accommodation choices. It also creates graphical reports and exports separate Excel files for further analysis.

---

# 📌 Project Overview

Travel companies often collect large amounts of traveler data.

Manually analyzing this data is time-consuming and inefficient.

This Travel Analytics Agent automates the entire process by:

* Reading travel datasets
* Analyzing male and female traveler preferences
* Identifying popular destinations
* Performing budget analysis
* Analyzing transportation choices
* Analyzing accommodation preferences
* Generating graphs
* Exporting Excel reports

---

# 🚀 Features

✅ Country-wise Male Traveler Analysis

✅ Country-wise Female Traveler Analysis

✅ Destination Popularity Analysis

✅ Budget Analysis

✅ Transportation Analysis

✅ Accommodation Analysis

✅ Automatic Graph Generation

✅ Excel Report Generation

✅ Google Colab Compatible

✅ Beginner-Friendly AI Agent Project

---

# 🛠️ Technologies Used

| Technology   | Purpose                 |
| ------------ | ----------------------- |
| Python       | Programming Language    |
| Pandas       | Data Processing         |
| Matplotlib   | Data Visualization      |
| OpenPyXL     | Excel Export            |
| Google Colab | Development Environment |

---

# 📂 Project Structure

```text
travel-analytics-agent/
│
├── Travel details dataset.csv
│
├── men_analysis.xlsx
├── women_analysis.xlsx
├── budget_analysis.xlsx
├── transport_analysis.xlsx
├── hotel_analysis.xlsx
│
├── app.ipynb
├── requirements.txt
└── README.md
```

---

# 📊 Dataset Information

The dataset contains:

* Traveler Gender
* Destination
* Accommodation Type
* Transportation Type
* Accommodation Cost
* Transportation Cost
* Travel Preferences

Example:

| Gender | Destination | Accommodation | Transport | Cost |
| ------ | ----------- | ------------- | --------- | ---- |
| Male   | Paris       | Hotel         | Flight    | 1200 |
| Female | Tokyo       | Hostel        | Train     | 800  |

---

# ⚙️ Installation

Install required libraries:

```bash
pip install pandas
pip install matplotlib
pip install openpyxl
```

---

# ▶️ How To Run

## Step 1: Upload Dataset

```python
from google.colab import files

uploaded = files.upload()
```

Upload:

```text
Travel details dataset.csv
```

---

## Step 2: Load Dataset

```python
import pandas as pd

df = pd.read_csv(
    "Travel details dataset.csv"
)
```

---

# 📈 Analysis Modules

## Male Traveler Analysis

The agent identifies which countries are most preferred by male travelers.

Output:

```text
Destination     Count
Paris           10
Tokyo           8
Dubai           7
```

---

## Female Traveler Analysis

The agent identifies which countries are most preferred by female travelers.

Output:

```text
Destination     Count
Tokyo           12
Paris           9
London          8
```

---

## Budget Analysis

The agent calculates average travel budget by destination.

Formula:

```text
Total Budget =
Accommodation Cost
+
Transportation Cost
```

Output:

```text
Destination     Avg Budget
Paris           1500
Tokyo           1800
Dubai           1200
```

---

## Transportation Analysis

The agent identifies preferred transportation methods.

Output:

```text
Flight          50
Train           40
Bus             20
Car             15
```

---

## Accommodation Analysis

The agent identifies accommodation preferences.

Output:

```text
Hotel           60
Hostel          40
Resort          20
Apartment       19
```

---

# 📊 Graph Generation

The agent automatically creates:

### Male Traveler Destination Graph

* Country vs Male Travelers

### Female Traveler Destination Graph

* Country vs Female Travelers

### Transportation Graph

* Transport Usage Distribution

### Accommodation Graph

* Accommodation Preference Distribution

---

# 📁 Excel Reports Generated

The system automatically generates:

### 1. men_analysis.xlsx

Contains:

* Destination
* Number of Male Travelers

---

### 2. women_analysis.xlsx

Contains:

* Destination
* Number of Female Travelers

---

### 3. budget_analysis.xlsx

Contains:

* Destination
* Average Budget

---

### 4. transport_analysis.xlsx

Contains:

* Transportation Type
* Traveler Count

---

### 5. hotel_analysis.xlsx

Contains:

* Accommodation Type
* Traveler Count

---

# 🔄 Agent Workflow

```text
Travel Dataset
        │
        ▼
Load CSV Dataset
        │
        ▼
Gender Analysis
        │
        ▼
Destination Analysis
        │
        ▼
Budget Analysis
        │
        ▼
Transportation Analysis
        │
        ▼
Accommodation Analysis
        │
        ▼
Graph Generation
        │
        ▼
Excel Report Generation
        │
        ▼
Download Reports
```

---

# 🎯 Applications

* Travel Agencies
* Tourism Analytics
* Customer Preference Analysis
* Market Research
* Travel Recommendation Systems
* Tourism Data Science Projects

---

# Advantages

* Automated Data Analysis
* Fast Report Generation
* Visual Insights
* Easy To Use
* Scalable For Large Datasets
* Multiple Excel Exports

---

# Limitations

* Requires Structured Dataset
* Depends On Data Quality
* No Real-Time Data Integration
* Basic Statistical Analysis Only

---

# Future Improvements

* AI Travel Recommendation Agent
* Interactive Dashboard
* Streamlit Web Application
* Predictive Travel Analytics
* Hotel Recommendation System
* Destination Recommendation System
* Multi-Dataset Support
* PDF Report Generation

---

# Learning Outcomes

After completing this project, you will understand:

* Data Analysis with Pandas
* Data Visualization
* Excel Automation
* Travel Data Analytics
* Report Generation
* AI Agent Development Concepts

---

# Resume Description

Developed a Travel Analytics Agent using Python, Pandas, and Matplotlib. The system analyzes traveler datasets, identifies destination preferences based on gender, performs budget, transportation, and accommodation analysis, generates visual reports, and exports multiple Excel-based analytical reports.

---

# 👨‍💻 Author

## Ajay Sagar

* Python Developer
* AI & Machine Learning Enthusiast
* B.Tech CSE Student

### Connect With Me

LinkedIn: https://www.linkedin.com/in/engineerajay

🚀 Building AI Projects and Learning New Technologies Every Day.

**Code the Future with Us..!**

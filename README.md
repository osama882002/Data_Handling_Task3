# 📊 Research Analytics Pipeline

📌 **Description**

This project demonstrates a complete data analysis workflow using **Python** and **Pandas**.

The pipeline includes:

- Loading multiple datasets
- Exploring and understanding data
- Cleaning dirty datasets
- Validating relationships
- Merging datasets
- Performing analytical operations
- Exporting clean results

---

# 📁 Project Structure

```text
research_analytics/
│
├── data_row/
│   ├── researchers.csv
│   ├── publications.json
│   └── funding.xlsx
│
├── output/
│   └── clean_research_data.csv
│
├── research_trail.py
├── requirements.txt
└── README.md
```

---

# ⚙️ Features

- Load CSV, JSON, and Excel datasets
- Perform Exploratory Data Analysis (EDA)
- Clean missing and invalid data
- Validate dataset relationships
- Merge datasets using Pandas
- Perform analytical operations
- Export cleaned merged dataset

---

# 📊 Analysis Performed

## CP1 — Researchers Analysis
- Sort researchers by joined year
- Filter active researchers
- Extract hidden message from last names

## CP2 — Publications Analysis
- Find the most cited paper
- Compare title with secret word

## CP3 — Funding Analysis
- Clean funding amounts
- Sum valid positive values
- Extract encoded year

---

# 🚀 How to Run

## Install dependencies

```bash
pip install -r requirements.txt
```

## Run the project

```bash
python research_analytics.py
```

---

# 📦 Requirements

- pandas
- openpyxl
- pyarrow
- numpy

Generate requirements file using:

```bash
pip freeze > requirements.txt
```

---

# 🧠 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Validation
- Data Merging
- Pandas Operations
- Data Pipeline Design

---

# ⭐ Notes

- Raw datasets are excluded using `.gitignore`
- The virtual environment (`venv/`) is not included in the repository
- The cleaned dataset is exported to:

```text
output/clean_research_data.csv
```

---

# 👨‍💻 Author

Osama  
Web Developer & Data Analytics Learner
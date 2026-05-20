# Research Analytics Pipeline

A complete data analysis pipeline built with **Python** and **Pandas** for analyzing research datasets.

This project demonstrates a real-world workflow for:

- Loading multiple datasets
- Exploring and understanding data
- Cleaning dirty datasets
- Validating relationships between datasets
- Merging datasets
- Performing analytical operations
- Exporting clean results

---

# Project Structure

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

# Datasets

## 1. researchers.csv

Contains researcher information such as:

- Researcher ID
- Name
- Research Field
- Institution
- Joined Year
- h-index
- Publications Count
- Activity Status

---

## 2. publications.json

Contains publication details such as:

- Publication ID
- Researcher ID
- Paper Title
- Citation Count
- Journal
- Open Access Status

---

## 3. funding.xlsx

Contains funding information such as:

- Grant ID
- Researcher ID
- Funding Body
- Funding Amount
- Project Title
- Award Year

---

# Technologies Used

- Python
- Pandas
- JSON Handling
- Excel Processing
- CSV Processing

---

# Features

## Data Loading

The project loads data from:

- CSV files
- JSON files
- Excel spreadsheets

---

## Exploratory Data Analysis (EDA)

The pipeline performs:

- Dataset exploration
- Shape analysis
- Column inspection
- Missing value detection
- Duplicate detection
- Data type inspection

---

# Data Cleaning Pipeline

The project includes reusable cleaning functions for:

## Researchers Dataset

- Handle missing last names
- Remove duplicate rows

## Publications Dataset

- Remove duplicates
- Handle missing titles
- Convert citations to numeric values
- Remove invalid citation values

## Funding Dataset

- Convert funding amounts to numeric values
- Remove invalid funding rows
- Remove negative values
- Handle null values

---

# Relationship Validation

The pipeline validates:

- researcher_id consistency across datasets
- relational integrity before merging

---

# Dataset Merging

Datasets are merged using:

```python
pd.merge()
```

The project demonstrates:

- INNER JOIN
- LEFT JOIN


---

# Analysis Performed

## CP1 — Researchers Analysis

- Sort researchers by joined year
- Filter active researchers
- Extract hidden message from last names

---

## CP2 — Publications Analysis

- Find paper with highest citations
- Compare paper title with secret word

---

## CP3 — Funding Analysis

- Clean funding amounts
- Sum valid positive funding values
- Extract encoded year from total funding

---

# Advanced Analysis

- Researcher with highest citations
- Field with highest funding
- Earliest active researcher

---

# Exported Output

The final cleaned merged dataset is exported to:

```text
output/clean_research_data.csv
```

---

# Requirements

The project dependencies are listed in:

```text
requirements.txt
```

Install all required packages using:

```bash
pip install -r requirements.txt
```

---

# How to Run

## Install dependencies

```bash
pip install -r requirements.txt
```

---

## Run the project

```bash
python research_trail.py
```

---

# Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Validation
- Data Merging
- Pandas Operations
- Data Pipeline Design
- Relationship Validation
- Aggregations and Analytics

---

# Key Learning Outcomes

This project demonstrates how to:

- Build reusable cleaning pipelines
- Handle dirty real-world data
- Validate dataset relationships
- Merge structured datasets
- Perform analytical operations with Pandas
- Design maintainable data workflows

---

> Note:
> Raw datasets are excluded from the repository using `.gitignore`.

# Author

Osama  
Web Developer & Data Analytics Learner
# Module 4: Data Handling

## Project Overview

This project demonstrates basic data handling with pandas. It loads structured and unstructured data from CSV, JSON, and text files, cleans the data, normalizes column names, performs simple exploratory data analysis, and exports a cleaned CSV file.

## Files

```text
module4-data-handling/
├── module4_data_ingestion.ipynb
├── requirements.txt
├── README.md
├── data/
│   ├── patients.csv
│   ├── diagnoses.json
│   └── patient_comments.txt
└── output/
    └── cleaned_patient_data.csv
```

## Setup

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install requirements:

```bash
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
module4_data_ingestion.ipynb
```

Run all cells from top to bottom.

## What the Notebook Does

- Loads CSV data with `pd.read_csv()`
- Loads JSON data with `pd.read_json()`
- Loads text data with `pd.read_csv()` using a separator
- Normalizes column names
- Checks missing values
- Fills missing values
- Removes duplicate records
- Performs basic EDA using `head()`, `describe()`, and `value_counts()`
- Combines datasets
- Exports a cleaned CSV file

## Output

The final cleaned file is saved as:

```text
output/cleaned_patient_data.csv
```

## Submission Files

Submit:

```text
module4_data_ingestion.ipynb
requirements.txt
README.md
data/
output/cleaned_patient_data.csv
```

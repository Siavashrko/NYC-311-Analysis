# NYC 311 Service Requests Analysis

A portfolio-ready data analysis project focused on NYC 311 service request data.

## Overview

This project explores how New York City residents submit service complaints and how those complaints are distributed across agencies, boroughs, and complaint types. The analysis follows a practical data workflow: loading raw data, auditing quality issues, cleaning the dataset, engineering features, performing exploratory analysis, and translating the results into business insights.

The goal is to turn a real-world operational dataset into a polished, reproducible, and presentation-ready project that demonstrates strong data handling and analytical reasoning.

---

## Why This Project Matters

NYC 311 data is a strong example of real-world service data because it contains both useful operational signals and common data-quality problems such as:

- missing values
- incomplete closed dates
- open complaints
- uneven complaint distribution across boroughs and departments

By auditing and cleaning the dataset before analysis, this project demonstrates practical decision-making that is important in business and public-sector analytics.

---

## Dataset

This project uses the NYC 311 Service Requests dataset, which includes information such as:

- complaint type
- agency and agency name
- borough and city
- created date and closed date
- request status
- location and zip code information

The dataset is useful for studying city service demand, complaint concentration, agency workload, and operational response behavior.

---

## Technical Stack

- Python
- pandas
- NumPy
- matplotlib
- seaborn
- Jupyter Notebook

---

## Core Questions

This analysis answers questions such as:

1. Which complaint types appear most often?
2. Which agencies receive the highest complaint volume?
3. Which boroughs generate the most requests?
4. Are complaint patterns concentrated by location or agency?
5. How long do complaints take to resolve?
6. Which issues are open, delayed, or repeatedly recurring?

---

## Key Findings

The project reveals several important patterns:

- A small number of complaint types dominate the dataset.
- Agency workload is unevenly distributed across departments.
- Borough-level demand is concentrated, with some areas generating far more requests than others.
- Most closed complaints are resolved quickly, but a smaller subset takes much longer.
- A meaningful share of records remain open, which matters for service operations and forecasting.

---

## Project Structure

```text
NYC-311-Analysis/
├── data/
│   └── 311-service-requests.csv
├── visuals/
│   ├── agency_complaints.png
│   ├── borough_complaints.png
│   ├── complaints_by_day.png
│   ├── complaints_by_month.png
│   ├── open_vs_closed.png
│   ├── resolution_time_distribution.png
│   └── top_complaints.png
├── 01_audit.ipynb
├── README.md
├── .gitignore
└── output/
    └── 311_cleaned.parquet
```

---

## Notebook Workflow

The notebook follows a structured workflow:

1. Load data
2. Audit data quality
3. Clean and validate the dataset
4. Engineer time-based features
5. Perform exploratory analysis
6. Summarize findings and recommendations
7. Export cleaned output

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/Siavashrko/NYC-311-Analysis.git
cd NYC-311-Analysis
```

Open the notebook:

```bash
jupyter notebook
```

Then open `01_audit.ipynb` and run the cells in order.

---

## Repository Status

This project is currently active and serves as a data portfolio piece focused on operational analysis, data cleaning, and business storytelling.

---

## Contact

- GitHub: https://github.com/Siavashrko
- Email: siavashrko@gmail.com

---

## Final Note

This project demonstrates a realistic data analysis workflow: from raw public data to cleaned, interpretable, and actionable insights. It is designed to show strong analytical thinking, reproducibility, and clear communication for a professional portfolio or job application.

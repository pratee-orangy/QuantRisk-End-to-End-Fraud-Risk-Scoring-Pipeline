# QuantRisk-End-to-End-Fraud-Risk-Scoring-Pipeline

🔍 Overview

This project implements an end-to-end customer fraud risk scoring pipeline using clean CSV data, Python (Jupyter Notebook), and business-driven logic.
It simulates real-world fraud monitoring by scoring customers based on transaction behavior and contextual risk indicators.

A key feature of this project is what-if analysis, which allows risk strategies to be adjusted dynamically by changing scoring weights.

📂 Data Pipeline

CSV → Python → Output CSV → Power BI

Raw data was cleaned and standardized in Excel
Cleaned data was exported as a processing-ready CSV
All calculations were performed in Python (Jupyter Notebook)
Final analytics output was exported as a CSV for dashboarding

⚙️ Python (Jupyter) – Core Features

Min–max normalization of transaction frequency and value
Weighted fraud risk score calculation
Configurable thresholds for business action
Risk categorization: Low / Medium / High
Recommended actions: No Action / Monitor / Review
Defensive data validation and quality checks

🔮 What-If Analysis (Key Highlight)

Multiple fraud strategies are supported by adjusting risk weights:
Baseline strategy
High transaction frequency focus
High transaction amount focus
High geographic risk focus
Each scenario recalculates risk scores, enabling side-by-side comparison of customer risk across strategies.

📊 Outputs

Normalized transaction metrics
Fraud risk score per customer
Risk bands and recommended actions
Scenario-based risk score comparisons

Final Output File:

customer_risk_intelligence_output.csv

📘 Documentation

A structured data dictionary is maintained to document all fields and business definitions, reflecting real enterprise practices.

🛠️ Tech Stack

Excel – Data cleaning & documentation

CSV – Clean data exchange format

Python (Pandas, NumPy) – Feature engineering & scoring

Jupyter Notebook – Analytical development

Power BI – Interactive dashboard 

✨ What Makes This Project Different

Business-driven, explainable risk scoring 

Built-in what-if strategy simulation

Clean separation of data, logic, and visualization layers

End-to-end, reproducible analytics pipeline

🚀 Future Enhancements

Interactive Power BI dashboard

Power BI what-if sliders

Real-time transaction ingestion

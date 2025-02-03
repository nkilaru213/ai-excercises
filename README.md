# ai-excercises
README - Transfers, Admissions, Prescriptions, and Diagnoses Data Analysis

Overview

This repository contains Python scripts for analyzing hospital transfer records, admissions, prescriptions, and diagnoses using structured data. The analysis includes filtering patient data, extracting meaningful insights, and visualizing trends from medical datasets.

Features

Transfers Data Analysis: Identifies trends in patient transfers, including the most common discharge locations and care units.

Admissions Data Analysis: Examines patient admissions by type, length of stay, and discharge locations.

Prescriptions Data Analysis: Extracts medication trends, dosage patterns, and commonly prescribed drugs.

Patients Data Analysis: Provides demographic insights, including age distributions and patient mortality rates.

Glucose Lab Item Extraction: Extracts blood glucose test item IDs for further analysis.

ICD Diagnoses Processing: Loads and analyzes diagnosis data to identify chronic conditions.

Chronic Diagnoses Insights: Filters diagnoses for chronic ICD-9 codes and determines the most frequent chronic conditions.

Dataset Details

The analysis is based on the following datasets:

Transfers Data: Includes patient movement records across hospital care units.

Admissions Data: Contains details on admission types, length of stay, and discharge details.

Prescriptions Data: Provides structured information on medications administered to patients.

Patients Data: Includes demographic information, age distributions, and mortality statistics.

Laboratory Data: Contains details of lab tests, including glucose tests.

ICD Diagnoses: Provides structured diagnosis records using ICD-9 codes.

Key Code Components

1. Transfers Analysis

Filters admissions to include only Emergency, Elective, and Urgent cases.

Determines the second most common discharge location.

2. Admissions Analysis

Analyzes admission trends by type.

Computes length of stay statistics for different admission categories.

Examines the most frequently used discharge locations.

3. Prescriptions Analysis

Identifies the most commonly prescribed medications.

Analyzes prescription dosage patterns and frequency of drug administration.

Evaluates medication trends based on admission types.

4. Patients Analysis

Examines age distributions across different hospitalizations.

Analyzes mortality rates within the dataset.

Identifies trends related to patient demographics.

5. Lab Item Extraction

Identifies glucose-related blood tests from lab records.

6. ICD Diagnoses Processing

Loads ICD-9 diagnoses from CSV files.

Filters diagnosis records to extract chronic conditions.

Counts the most frequently occurring chronic diagnoses.

How to Use

Load the dataset files into the appropriate directory.

Run the Python script to process and analyze the data.

Review the printed outputs for insights and trends.

Modify parameters as needed to refine the analysis.

Dependencies

Ensure the following Python libraries are installed:

pip install pandas matplotlib

Author

This project is developed for medical data analysis using Python.

License

MIT License


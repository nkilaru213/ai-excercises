# ai-excercises
README - Transfers, Admissions, Prescriptions, and Diagnoses Data Analysis using ICUSTAYS, LABEVENTS, D_LABITEMS, D_ICD_DIAGNOSES , DIAGNOSES_ICD

## Overview
This repository contains Python scripts for analyzing hospital transfer records, admissions, prescriptions, and diagnoses using structured data. 
The analysis includes filtering patient data, extracting meaningful insights, and visualizing trends from medical datasets.

## Features
- **Transfers Data Analysis**: Identifies trends in patient transfers, including the most common discharge locations and care units.
- **Admissions Data Analysis**: Examines patient admissions by type, length of stay, and discharge locations.
- **Prescriptions Data Analysis**: Extracts medication trends, dosage patterns, and commonly prescribed drugs.
- **Patients Data Analysis**: Provides demographic insights, including age distributions and patient mortality rates.
- **Glucose Lab Item Extraction**: Extracts blood glucose test item IDs for further analysis.
- **ICD Diagnoses Processing**: Loads and analyzes diagnosis data to identify chronic conditions.
- **Chronic Diagnoses Insights**: Filters diagnoses for chronic ICD-9 codes and determines the most frequent chronic conditions.

## Key Code Components

1. **Transfers Analysis**
  - Filters admissions to include only Emergency, Elective, and Urgent cases.
  - Determines the second most common discharge location.
2. **Admissions Analysis**
  - Analyzes admission trends by type.
  - Computes length of stay statistics for different admission categories.
  - Examines the most frequently used discharge locations.
3. **Prescriptions Analysis**
  - Identifies the most commonly prescribed medications.
  - Analyzes prescription dosage patterns and frequency of drug administration.
  - Evaluates medication trends based on admission types.
4. **Patients Analysis**
  - Examines age distributions across different hospitalizations.
  - Analyzes mortality rates within the dataset.
  - Identifies trends related to patient demographics.
5. **Lab Item Extraction**
  - Identifies glucose-related blood tests from lab records.
6. **ICD Diagnoses Processing**
  - Loads ICD-9 diagnoses from CSV files.

## How to Use
1. Load the dataset files into the appropriate directory.
2. Run the Python script to process and analyze the data.
3. Review the printed outputs for insights and trends.
4. Modify parameters as needed to refine the analysis.

## Dependencies
Ensure the following Python libraries are installed:
```bash
pip install pandas matplotlib

# DataForge
This project generates a synthetic healthcare dataset of 300 patients visiting Ogbete Hospital (Jan–Jun 2020). Using Python (NumPy, Pandas, Random), it creates realistic records with demographics, income, visit dates, vaccination, and BMI, offering a safe, ethical tool for research, learning, and data practice.
# Healthcare Dataset Generator

This project generates a **synthetic healthcare dataset** for 300 patients attending a clinic during the COVID-19 pandemic.  
It is designed for **educational and research practice**, allowing users to work with realistic healthcare data without privacy concerns.

## Features
- Generates **300 synthetic patient records**
- Includes the following variables:
  - Unique Hospital ID
  - Age Group (0–75 years)
  - Sex (male/female)
  - Annual Household Income
  - Date of Visit (Jan–Jun 2020)
  - Residential Area
  - Vaccination Status (Yes/No)
  - Body Mass Index (BMI, with decimals)
- Outputs dataset as an **Excel file** (`healthcare_dataset.xlsx`)

## Requirements
- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `random`

Install dependencies with:
```bash
pip install pandas numpy

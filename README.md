# DataForge
This project generates a synthetic healthcare dataset of 300 patients visiting Ogbete Hospital (Jan–Jun 2020). Using Python (NumPy, Pandas, Random), it creates realistic records with demographics, income, visit dates, vaccination, and BMI, offering a safe, ethical tool for research, learning, and data practice..

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
pip install pandas
```

## Why this exists

Real patient data is protected for good reason, so analysts in training often have nothing realistic to practise on. DataForge creates records that look and behave like hospital data but belong to no one. Ogbete Hospital is fictional.

## Run it

Open dataforge_generator.ipynb in Google Colab and run all cells. The output is healthcare_dataset.xlsx.

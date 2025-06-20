# Hospital Readmission & Billing Insights

A data analysis project that explores healthcare patient records to uncover patterns in hospital admissions, billing behavior, length of stay, and chronic conditions using Python.

---

## Project Objective

To analyze patient data and identify:

- What drives high medical bills?
- Which conditions lead to longer hospital stays?
- Are seniors or weekend admissions more costly?
- How do insurance providers and medications influence costs?
- Are there seasonal trends in hospital admissions?

---

## Dataset

The dataset includes anonymized patient records with the following fields:

- Patient demographics (Age, Gender, Blood Type)
- Admission details (Type, Date, Duration, Season)
- Medical condition and test results
- Insurance information
- Billing amount and stay duration
- Medication prescribed

>  **File:** `healthcare_dataset.csv`

---

##  Tools & Technologies

- **Python**
- **pandas** for data manipulation
- **matplotlib & seaborn** for visualizations
- **FPDF / python-docx** for reporting
- **Jupyter Notebook** for development

---

## Key Analysis Performed

### Data Cleaning & Preparation
- Removed invalid entries
- Normalized categorical data
- Derived new features like:
  - `Length of Stay`
  - `billing_per_day`
  - `admission_season`
  - `age_group`
  - `is_senior`, `is_chronic_condition`

### Visual Exploratory Data Analysis
- Age vs Billing
- Medication vs Stay
- Weekend vs Weekday Admissions
- Insurance Provider vs Billing
- Condition-based cost distribution
- Seasonal Admission Trends

### Correlation Analysis
- Billing vs Stay
- Billing per day vs Age
- Multivariate pairplots

---

## Key Insights

- **Chronic conditions** like diabetes and hypertension drive longer stays and higher billing.
- **Seniors (60+)** tend to incur higher average costs and stay longer.
- **Weekend admissions** result in longer hospital stays.
- **Spring & Winter** see the highest admission rates.
- **Certain medications and insurance providers** are strongly associated with higher billing.

---

## Deliverables

-  Cleaned dataset: `healthcare_dataset_cleaned.csv`
-  Visual reports & charts (PNG)
-  Final insights report in PDF & Word
-  Full notebook with step-by-step analysis

---



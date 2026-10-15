# healthcare-data-cleaning-task

# Healthcare Data Cleaning & Understanding

## Internship Task
VirtualWorks-Lab — Data Analytics (Healthcare/Pharmacy), Task 1.

## Objective
Explore a healthcare dataset containing patient ID, age, gender, disease, medication, and dosage. Identify data types, clean missing and duplicate records, standardize inconsistent values, and perform basic descriptive analysis.

## Tools Used
- Python
- Pandas
- CSV datasets

## Project Structure
- `data/healthcare_data_raw.csv` — original synthetic dataset
- `data/healthcare_data_cleaned.csv` — cleaned dataset
- `data/data_quality_report.csv` — data quality summary
- `data/analysis_summary.csv` — key analysis metrics
- `data/disease_counts.csv` — disease frequency summary
- `src/clean_data.py` — data cleaning script
- `src/analyze_data.py` — analysis script

## Data Cleaning Steps
1. Load and inspect the dataset.
2. Standardize whitespace and category labels.
3. Convert age and dosage columns to numeric values.
4. Flag invalid ages and dosages for review.
5. Remove exact duplicate records.
6. Fill missing ages with the median age.
7. Preserve missing medication and dosage values rather than guessing clinical information.
8. Export the cleaned dataset and quality report.

## Analysis Performed
- Total patient records and unique patient IDs
- Average patient age
- Most common diseases
- Gender distribution
- Medication frequency

## How to Run
Install Python, then run:

```bash
pip install -r requirements.txt
python src/clean_data.py
python src/analyze_data.py
```

## Privacy and Limitations
This project uses synthetic practice data only. It does not contain real patient records. The analysis is for educational purposes and is not intended for clinical decision-making.

## Conclusion
This task demonstrates a basic healthcare data analytics workflow, from data inspection and cleaning to descriptive analysis and reporting.
# Project 2: Predicting Hospital Readmission Risk

## BLUF (Bottom Line Up Front)
This project aims to build a machine learning model that predicts the risk of 30-day hospital readmission using clinical and demographic patient data, enabling hospitals to reduce costly readmissions and improve patient outcomes.

---

## Project Overview

Hospital readmissions within 30 days of discharge increase healthcare costs and trigger financial penalties for hospitals under U.S. CMS reimbursement. By identifying patients at high risk of readmission with data science, clinical teams can proactively manage and reduce readmissions, optimize resources, and enhance quality of care.

---

## Business Problem

- **Challenge:** Excessive readmission rates drive up costs and risk penalties; hospitals need to identify and intervene with high-risk patients before discharge.
- **Stakeholders:** Chief Medical Officer, Care Coordination Team, Data Analytics Department, Hospital Administration.
- **Key Goals:**
  - Reduce 30-day readmission rate by at least 10% over six months.
  - Improve patient satisfaction (HCAHPS) scores.
  - Demonstrate measurable cost savings via penalty reduction.

---

## Dataset

- **Source:** Kaggle “Diabetes 130-US hospitals” (1999–2008) and CMS Hospital Compare.
- **Size:** ~100,000 inpatient records across 130 hospitals.
- **Features include:** Patient demographics, length of stay, admission type, diagnoses, comorbidities, lab procedures, medications, discharge disposition.
- **Target variable:** Readmission within 30 days (`0` for no, `1` for yes).
- **Relevance:** This dataset contains all variables needed to estimate patient risk and directly supports the business challenge.

---

## Repository Structure

project-2-readmission-risk/
├── README.md
├── .gitignore
├── data/
│ └── [your-dataset.csv]
├── notebooks/
│ └── eda-and-modeling.ipynb
├── images/
├── pipeline/
│ └── model_pipeline.pkl


---

## Usage

1. Clone this repo:
git clone https://github.com/meneh-ops/project-2-readmission-risk.git
2. Place raw dataset files in the `/data` folder.
3. Open and run analysis in `/notebooks/eda-and-modeling.ipynb`.
4. Results and model artifacts will be stored in `/pipeline`.

---

## How to Run the Notebooks

- Requires Python 3.8+, Jupyter, pandas, scikit-learn, seaborn, matplotlib, and numpy.
- To install dependencies:
pip install -r requirements.txt

(Add `requirements.txt` to list dependencies.)

---

## Data Usage Guide

- All sensitive patient data is anonymized and for academic use only.
- Data processing steps are documented in the main notebook.
- Do not push raw proprietary hospital data to this public repo; use open-access datasets as noted above.

---

## Contact

Maintainer: Mezue Eneh ([mezue.eneh@gmail.com](mailto:mezue.eneh@gmail.com))

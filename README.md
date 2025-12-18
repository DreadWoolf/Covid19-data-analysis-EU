# COVID-19 Data Analysis in EU/EEA Countries

This repository contains the implementation and results of **Assignment 2 – Intelligent Data Analysis (DV1597)** at Blekinge Institute of Technology.

The project performs an explanatory data analysis of the COVID-19 pandemic in EU/EEA countries, focusing on reported cases, deaths, vaccination coverage, and hospital and ICU utilization.

---

## Project Overview

The objective of this assignment was to:
- Perform exploratory and explanatory data analysis on multiple COVID-19 datasets
- Apply data cleaning, transformation, aggregation, and statistical analysis
- Answer a set of mandatory research questions using data-driven methods
- Present results through visualizations, statistical tests, and written interpretation

The analysis is implemented in an interactive **Jupyter Notebook**, accompanied by a written report in PDF format.

---

## Datasets

The analysis is based on three datasets provided via the course page on Canvas, originally collected by the **European Centre for Disease Prevention and Control (ECDC)**:

1. Daily new COVID-19 cases and deaths  
2. COVID-19 vaccination data  
3. COVID-19 hospital and ICU admission and occupancy data  

### Data availability

**The datasets are not included in this repository**, as they were distributed through Canvas and must not be redistributed.

To run the notebook locally, you must obtain the datasets from the course page or similar and place them in the expected directory structure referenced in the notebook.

---

## Research Questions

The analysis addresses mandatory questions covering:

- Quarterly case trends across EU/EEA countries (2020–2022)
- Geographical visualization of cases and deaths
- Vaccine brand usage and target group distribution
- Vaccine skepticism and its relationship to hospitalization and fatality rates
- Vaccination coverage by age group
- Healthcare system impact during different phases of the pandemic

Additional exploratory questions were formulated and answered to meet higher-grade requirements, including statistical hypothesis testing and correlation analysis.

---

## Methods and Techniques

- Data cleaning and preprocessing
- Aggregation by country, time period, and age group
- Logarithmic scaling and rolling averages
- Outlier detection
- Statistical hypothesis testing (e.g. Mann–Whitney U test)
- Correlation analysis (Spearman)
- Visualizations using matplotlib and seaborn
- Map-based and time-series analysis

All methodological choices are motivated and documented in the notebook and report.

---
## Repository Contents

```text
.
├── Assignment2_final.ipynb
├── Assignment_2__Corona_pandemic_in_Europe.pdf
├── Assignment 2 Corona.pptx
├── README.md
└── .gitignore
```


---

## Requirements

- Python 3
- Jupyter Notebook
- Common data analysis libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy

Exact versions are not enforced, but the environment must support standard scientific Python packages.

---

## Academic Context

This project was completed as part of the course **DV1597 – Intelligent Data Analysis** at Blekinge Institute of Technology.

All analysis, interpretations, and conclusions were produced by the authors based on the provided datasets and course guidelines.

---

## Notes

This repository is intended for:
- Documentation of academic work
- Demonstration of data analysis skills
- Personal portfolio use

It is not intended as a standalone, fully reproducible project without access to the original datasets.





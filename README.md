# Module 1: Executive Compensation and Firm Characteristics

## Overview

This project explores executive compensation data from the **ExecuComp** database, with a focus on understanding how executive characteristics such as **gender**, **age**, **tenure**, **CEO status**, and the presence of **golden parachutes** relate to differences in compensation.

The analysis was conducted using Python in a Jupyter Notebook environment and follows a structured approach in line with the course assignment for **Quantitative Methods III**.

---

## Research Question

**What executive and firm characteristics are associated with differences in executive compensation?**

### Hypotheses:

- **H1:** Male executives receive higher compensation than female executives.
- **H2:** CEO status is positively associated with total compensation.
- **H3:** Age and tenure are positively correlated with compensation.
- **H4:** Golden parachute agreements are associated with higher compensation.

---

## Data Source

- **WRDS ExecuComp** database via a secure connection
- Data extracted from the `anncomp` table, covering executive compensation from 2018 onward
- Dataset includes fields for salary, bonus, equity awards, age, gender, CEO status, and golden parachute details

---

## Methods

The project is divided into structured sections:

1. **Data Connection & Extraction** – Access and pull data from WRDS
2. **Initial Exploration** – Shape, columns, types, and missing values
3. **Cleaning & Preparation** – Renaming variables, filtering CEOs, converting data types
4. **Descriptive Statistics** – Summary statistics for numeric and categorical variables
5. **Correlation Analysis** – Pearson correlations between numeric characteristics and compensation
6. **Group Visualizations** – Boxplots for categorical group comparisons
7. **Regression Analysis** – Linear model to evaluate compensation predictors
8. **Export Section** – Save graphs and results for reporting
9. **Close WRDS Session**

---

## Key Results

- **Male executives earn ~34% more** in total compensation than female executives (median comparison)
- **CEOs earn ~132% more** than non-CEOs
- Executives with **golden parachutes** earn **74% more** on average
- **Regression analysis** confirms statistically significant relationships between gender, CEO status, and compensation
- **Age and tenure** show modest positive correlations with compensation

---

## Outputs

- 📊 Summary statistics table (numeric and categorical)
- 📈 Boxplots for gender, CEO status, and golden parachutes
- 📉 Correlation matrix
- 📄 Final regression output

All results are available in:
- `hw_1_turnin.ipynb`
- Summary files in `/module-01_exec-comp/`

---

## How to Reproduce

To run the notebook:

1. Set up your WRDS environment (store your WRDS credentials in a `.env` file)
2. Install dependencies from `requirements.txt` (optional)
3. Run `hw_1_turnin.ipynb` in JupyterLab or Jupyter Notebook
4. Make sure you do **not commit your `.env` file** to version control

---

## License

This repository is intended for academic use only under the University of Denver Quantitative Methods III course.

---

## Contact

**Author**: Jasmine Motupalli  
**Repository**: [quant3](https://github.com/dataloveco/quant3)  
**Email**: jasmine.motupalli@du.edu or jasmine@dataloveco.com

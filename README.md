# FIN 6305 – Applied Quantitative Methods in Finance

This repository contains coursework for **FIN 6305: Applied Quantitative Methods in Finance** at the University of Denver's Daniels College of Business (Summer 2025). The course emphasizes hands-on application of empirical methods using Python, with topics ranging from corporate governance to machine learning in finance.

---

## Repository Structure

```text
quant3/
├── README.md
├── module-01_exec-comp/
│   ├── Homework 1 final.ipynb
│   ├── Homework 1 final with output.pdf
│   ├── correlation_matrix.xlsx
│   ├── execucomp_all_table_descriptions.xlsx
│   ├── summary_stats_numeric.xlsx
│   ├── gender_bonus_boxplot.png
│   ├── gender_option_awards_boxplot.png
│   ├── gender_salary_boxplot.png
│   ├── gender_stock_awards_boxplot.png
│   ├── gender_total_curr_boxplot.png
│   ├── is_ceo_bonus_boxplot.png
│   ├── is_ceo_option_awards_boxplot.png
│   ├── is_ceo_salary_boxplot.png
│   ├── is_ceo_stock_awards_boxplot.png
│   ├── is_ceo_total_curr_boxplot.png
│   ├── golden_parachute_bonus_boxplot.png
│   ├── golden_parachute_option_awards_boxplot.png
│   ├── golden_parachute_salary_boxplot.png
│   ├── golden_parachute_stock_awards_boxplot.png
│   ├── golden_parachute_total_curr_boxplot.png
├── module-02_regression/             # (To Be Posted)
├── module-03_two-stage-ls/          # (To Be Posted)
├── module-04_data-wrangling/        # (To Be Posted)
├── module-05_factor-models/         # (To Be Posted)
├── module-06_llm-research/          # (To Be Posted)
├── module-07_forecasting/           # (To Be Posted)
├── module-08_machine-learning/      # (To Be Posted)
├── module-09_web-apps/              # (To Be Posted)
├── individual-research/             # (To Be Posted)
└── resources/                       # (To Be Posted)
```
---

## Module 1: Executive Compensation Analysis

### Overview

This module investigates executive compensation using the **WRDS ExecuComp** database. It explores how executive characteristics—such as **gender**, **age**, **tenure**, **CEO status**, and **golden parachute agreements**—are associated with compensation differences.

**Contributors**: Jasmine Motupalli, Eddie Castaneda, Coby Teets

---

### Research Question

**How do executive characteristics relate to executive compensation levels in U.S. public companies?**

#### Hypotheses

- **H1**: Male executives receive higher compensation than female executives  
- **H2**: CEO status is positively associated with total compensation  
- **H3**: Age and tenure are positively correlated with compensation  
- **H4**: Golden parachute agreements are associated with higher compensation

---

### Data Source

- **WRDS ExecuComp** database (`comp_execucomp.anncomp`)
- Sample: ~50,000 executive compensation records (2018–2023)
- Key variables: salary, bonus, stock/option awards, age, gender, CEO status, golden parachute indicators

---

### Methods

The analysis was implemented in Python (Jupyter Notebook) and includes:

1. Library imports and environment setup  
2. Secure WRDS connection using `.env` file  
3. Schema exploration of the ExecuComp dataset  
4. SQL-based data extraction  
5. Data preparation and cleaning  
6. Missing data diagnostics  
7. Descriptive statistics and visual summaries  
8. Bivariate correlation analysis  
9. T-tests for categorical group comparisons  
10. Boxplot visualizations by category  
11. Regression analysis using OLS  
12. Export of data tables and graphics  
13. Interpretation of key findings  
14. Session cleanup and security

---

## Key Findings

### Descriptive Insights

- **Sample Composition**: 84.8% male, 15.2% female
- **CEO Representation**: 18.9% of observations
- **Golden Parachutes**: Present in 81.8% of contracts
- **Distributions**: Right-skewed due to equity-based pay

### Statistical Highlights

- **Gender Gap**: Males earn 11.0% more (median total compensation)  
- **CEO Premium**: CEOs earn 90.3% more than non-CEOs  
- **Golden Parachute Effect**: Associated with a 34.0% compensation boost  

### Regression Results (R² = 0.062)

- CEO and golden parachute status are statistically significant predictors  
- Age and tenure show weak but significant associations  
- Gender becomes non-significant once controls are added  
- Model explains ~6% of variance in compensation

---

## Outputs

**Tables and Files:**

- `summary_stats_numeric.xlsx`: Numeric descriptive statistics  
- `correlation_matrix.xlsx`: Pearson correlation coefficients  
- `execucomp_all_table_descriptions.xlsx`: Dataset metadata  
- `Homework 1 final.ipynb`: Full Jupyter Notebook with analysis  

**Visuals:**

- 15+ boxplots for categorical comparisons  
- Correlation heatmaps and distribution plots  

---

## How to Reproduce

1. **Set up WRDS credentials** in a `.env` file:
    ```
    WRDS_USER=your_username
    WRDS_PASSWORD=your_password
    ```

2. **Install dependencies**:
    ```bash
    pip install pandas numpy matplotlib seaborn statsmodels scipy wrds missingno
    ```

3. **Run the notebook**:
    ```bash
    jupyter lab "Homework 1 final.ipynb"
    ```

> ⚠️ Note: Be sure your `.env` file is in `.gitignore` to avoid exposing credentials.

---

## Course Context

This module introduces foundational quantitative techniques for finance, emphasizing descriptive statistics, hypothesis testing, and basic regression modeling. It provides a strong base for more advanced topics in subsequent modules.

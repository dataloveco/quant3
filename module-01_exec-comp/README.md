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

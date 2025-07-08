# Module 02 – Moderating Role of Governance on R&D and Firm Value

This module explores how governance characteristics (such as CEO tenure and board tenure) moderate the relationship between R&D investment and firm value. The analysis uses firm-level data from Compustat and governance data from BoardEx, accessed via the WRDS platform.

## 📊 Research Question

**Does R&D intensity influence firm value, and how do different governance mechanisms (as a proxy for agency costs) moderate this relationship?**

### Variables Used
- **Dependent Variable:** Firm Value (Tobin’s Q)
- **Independent Variable:** R&D Intensity (R&D expenses / Total Sales)
- **Moderators:**  
  - CEO Time in Role  
  - Board Tenure
- **Controls:**  
  - Leverage (Debt-to-Equity)  
  - Profitability (Return on Assets)

### Hypotheses
- **H1:** R&D intensity positively affects firm value.
- **H2:** Longer CEO tenure is negatively associated with R&D intensity and firm value.
- **H3:** Longer board tenure positively moderates the R&D–firm value relationship.

## 📁 Directory Structure

```text
module-02_rnd-governance/
├── anaconda_projects/
│   └── db/
│       └── project_filebrowser.db
├── module_02_hw_final.ipynb
├── notebook_exports/
│   ├── 01_variable_distributions.png
│   ├── 02_correlation_matrix.png
│   ├── 03_regression_diagnostics.png
│   ├── hypothesis_test_results.xlsx
│   ├── regression_coefficients.xlsx
│   └── summary_statistics.xlsx
└── .gitignore
```
## 🧰 Tools Used
- Python (`pandas`, `statsmodels`, `matplotlib`, `seaborn`)
- Jupyter Notebook
- WRDS (Compustat + BoardEx access)
- Excel + PNG exports for reporting
## 🚀 How to Run
Ensure your WRDS access is configured and credentials are available.  
Open `module_02_hw_final.ipynb` in JupyterLab and run all cells sequentially.
## 🔍 Insights
Results provide evidence on how leadership characteristics influence the effectiveness of R&D investments, with implications for both strategic innovation and governance policy.


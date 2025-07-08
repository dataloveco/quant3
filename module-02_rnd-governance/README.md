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
## 📥 How to Copy This Module
To get a local copy of this module, follow these steps:
1. Open a terminal on your computer.
2. Navigate to the directory where you want to store the project.
3. Clone the full repository:

```bash
git clone https://github.com/dataloveco/quant3.git
```
4. Navigate to this module's folder:

```bash
cd quant3/module-02_rnd-governance
```
From here, you can open `module_02_hw_final.ipynb` in JupyterLab or your preferred IDE and run the analysis.

> 💡 **Note:** Git does not support cloning a subdirectory alone. Cloning the full repository ensures you get this module along with the shared resources and structure.
## 🚀 How to Run
Ensure your WRDS access is configured and credentials are available.  
Open `module_02_hw_final.ipynb` in JupyterLab and run all cells sequentially.
## 🔍 Insights
Results provide evidence on how leadership characteristics influence the effectiveness of R&D investments, with implications for both strategic innovation and governance policy.


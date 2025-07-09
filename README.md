# FIN 6305 – Applied Quantitative Methods in Finance

This repository contains coursework for **FIN 6305: Applied Quantitative Methods in Finance** at the University of Denver's Daniels College of Business (Summer 2025). The course emphasizes hands-on application of empirical methods using Python, with topics ranging from corporate governance to machine learning in finance.

Students will use tools such as Jupyter Notebooks, pandas, statsmodels, and APIs like WRDS to work with real-world financial data. This repository is intended as both a record of student work and a resource for future students learning Python for financial analysis.

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
│   └── README.md
├── module-02_rnd-governance/
│   ├── module_02_hw_final.ipynb
│   ├── notebook_exports/
│   │   ├── 01_variable_distributions.png
│   │   ├── 02_correlation_matrix.png
│   │   ├── 03_regression_diagnostics.png
│   │   ├── hypothesis_test_results.xlsx
│   │   ├── regression_coefficients.xlsx
│   │   └── summary_statistics.xlsx
│   └── README.md
├── module-03_two-stage-ls/           # (To Be Posted)
├── module-04_data-wrangling/         # (To Be Posted)
├── module-05_factor-models/          # (To Be Posted)
├── module-06_llm-research/           # (To Be Posted)
├── module-07_forecasting/            # (To Be Posted)
├── module-08_machine-learning/       # (To Be Posted)
├── module-09_web-apps/               # (To Be Posted)
└── resources/
    ├── data/
    │   ├── dummy_executive_compensation.csv
    │   ├── dummy_stock_data.csv
    │   └── dummy_financials.csv
    ├── data_dictionary/
    │   ├── boardex_all_table_descriptions.xlsx
    │   └── compustat_all_table_descriptions.xlsx
    ├── resource-01-setup.ipynb
    ├── resource-02-jupyter.ipynb
    ├── resource-03-python-basics.ipynb
    ├── resource-04-core-libraries.ipynb
    ├── resource-05-wrds-connection.ipynb
    ├── resource-06-financial-analysis-workflow.ipynb
    ├── resource-07-course-applications.ipynb
    ├── resource-08-troubleshooting-best-practices.ipynb
    ├── resource-09-package-management.ipynb
    ├── resource-10-presentation-reporting.ipynb
    └── README.md
```

---

## Resource Notebooks Overview

| Notebook File | Description |
|---------------|-------------|
| `resource-01-setup.ipynb` | Installing Anaconda, navigating terminal (Mac/PC), and launching Jupyter |
| `resource-02-jupyter.ipynb` | Jupyter interface, cell types, markdown formatting, and file organization |
| `resource-03-python-basics.ipynb` | Python syntax: variables, conditionals, loops, functions |
| `resource-04-core-libraries.ipynb` | Intro to pandas, NumPy, and basic visualizations |
| `resource-05-wrds-connection.ipynb` | How to securely connect to WRDS and run SQL queries |
| `resource-06-financial-analysis-workflow.ipynb` | Importing and cleaning data, calculating returns, handling dates |
| `resource-07-course-applications.ipynb` | Analysis of executive compensation and regression setup |
| `resource-08-troubleshooting-best-practices.ipynb` | Debugging errors, common mistakes, and best practices |
| `resource-09-package-management.ipynb` | Installing and managing packages and virtual environments |
| `resource-10-presentation-reporting.ipynb` | Exporting notebooks and presenting results effectively |

---

## About the Data

All datasets in the `resources/data/` folder are **dummy datasets created for educational purposes**, including:

- Executive compensation summaries
- Stock price time series
- Financial statement data

These datasets can be freely modified for learning, experimentation, and coursework.

---

## Course Topics (Modules Overview)

- Module 01: Executive Compensation & Summary Statistics
- Module 02: Linear Regression in Python
- Module 03: Two-Stage Least Squares
- Module 04: Data Wrangling & Feature Engineering
- Module 05: Fama-French Factor Models
- Module 06: Large Language Models (LLMs) in Finance Research
- Module 07: Time Series Forecasting
- Module 08: Machine Learning Applications
- Module 09: Interactive Web Apps with Streamlit

---

## Additional Resources

For students looking to go beyond the course:

- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [pandas Documentation](https://pandas.pydata.org/docs/)
- [JupyterLab User Guide](https://jupyterlab.readthedocs.io/en/stable/)
- [Statsmodels Documentation](https://www.statsmodels.org/stable/user-guide.html)
- [WRDS Support & Tutorials](https://wrds-www.wharton.upenn.edu/pages/support/)

---

If you encounter errors or would like to contribute enhancements, feel free to open an issue or submit a pull request.

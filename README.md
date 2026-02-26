# Supply-Chain-Analysis

**Technical Project: Data Wrangling and Interactive Visualization**

##  Project Summary
This project provides a comprehensive analysis of supply chain metrics, including lead times, shipping costs, and inventory levels. The primary goal was to transform raw logistics data into actionable insights using a modern Python-based stack.

##  Tech Stack
* **Analysis:** Python (Pandas, NumPy)
* **Visualization:** Plotly (Express & Graph Objects)
* **Development:** Google Colab / GitHub
* **Methodology:** Descriptive Statistics, Exception Reporting, and Financial Ratio Analysis.

##  Workflow
1. **Data Audit:** Performed initial exploratory data analysis (EDA) using `.info()` and `.describe()`.
2. **Preprocessing:** Handled missing values via median-imputation and identified outliers in shipping expenditures.
3. **Operational Filtering:** Engineered an "At-Risk" logic to isolate SKUs requiring immediate intervention based on stock-to-lead-time ratios.
4. **Efficiency Modeling:** Developed a scatter analysis to visualize the relationship between revenue generation and logistics overhead.
5. **Automation:** Created a modular reporting function to simulate a production-environment data pipeline.

## Key Insights
* **Lead Time Variance:** Identified specific carriers with high lead-time volatility.
* **Cost Efficiency:** Highlighted product categories with disproportionate shipping costs relative to revenue.

##  Repository Contents
* `Supply_Chain_Analysis.ipynb`: Full commented code and interactive visualizations.
* `supply_chain_data.csv`: The source dataset utilized for the analysis.

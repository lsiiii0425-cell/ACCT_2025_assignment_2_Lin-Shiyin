# Accounting II - Assignment 2: Valuation Multiples Analysis

**Author:** Shiyin Lin  
**Course:** Accounting II: Corporate Decision-Making and Quantitative Analysis  
**Term:** Winter Semester 2025/26  
**Institution:** Humboldt-Universität zu Berlin

##  Project Overview
This repository contains the replication code, data, and final report for Assignment 2. The project investigates the relationship between the **Price-to-Book (P/B) ratio** and **Return on Assets (ROA)** for firms listed in the German Prime Standard for the fiscal year 2023.

##  Repository Structure

The project is organized as follows:

- **`doc/`**: Contains the final written report in PDF format.
  - 📄 `assignment2_report.pdf`: The main submission file.（but i didn't make it perfectly)
- **`code/`**: Python scripts used for data processing and analysis.
  - 🐍 `do_analysis.py`: Main script to generate statistics and figures.
- **`data/`**: Input data files (Compustat Global via WRDS).
  - `generated/`: Processed parquet files used for analysis.
- **`output/`**: Generated results.
  - 🖼️ `figures/`: Contains the scatter plots used in the report.
- **`config/`**: Configuration files for data paths.

## How to Run the Code

To replicate the analysis, please follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Isiiii0425-cell/ACCT_2025_assignment_2_Lin-Shiyin.git](https://github.com/Isiiii0425-cell/ACCT_2025_assignment_2_Lin-Shiyin.git)
2. Install required dependencies: Ensure you have Python installed with the following libraries:

pandas

matplotlib

seaborn

pyyaml

fastparquet
pip install pandas matplotlib seaborn pyyaml fastparquet
3. Run the analysis script: Navigate to the repository folder and run:

## 📊 Key Findings
Full Sample: We document a near-zero correlation (-0.05) between P/B and ROA across the full sample of 207 firms.

Profitable Firms: When restricting the sample to profitable firms (ROA > 0), a significant positive correlation (0.58) is observed, supporting standard valuation theories.

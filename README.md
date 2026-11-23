# Retail Sales Data Visualization and Analysis Using Python

## Project Overview
This MCA mini-project analyzes a simulated retail customer and sales dataset covering 2023–2024. It uses Python to prepare the data, identify sales and profit patterns, understand customer behavior, and communicate findings through charts and a visual report.

The analysis focuses on:
- Monthly sales trends
- Sales across regions and product categories
- Customer age and income distributions
- Sales and profit relationships
- Customer-segment contribution
- Correlations, satisfaction, and product returns

> **Dataset note:** The supplied dataset is simulated for learning and project work. It does not represent actual sales from a real retail company.

## Tools and Technologies
- Python 3.10 or later
- Visual Studio Code (VS Code)
- Jupyter Notebook / Jupyter extension
- Pandas and NumPy
- Matplotlib and Seaborn
- Streamlit (optional interactive dashboard)

## Project Folder Structure
```text
Retail_Sales_Career_Shaper_Project/
├── README.md
├── requirements.txt
├── Retail_Sales_Data_Visualization_Analysis.ipynb
├── data/
│   └── retail_customer_sales_cleaned.csv
├── dashboard/
│   └── app.py
└── reports/
    ├── Retail_Sales_Visual_Analysis_Report.pdf
    └── charts/
        ├── 01_monthly_sales.png
        ├── 02_sales_region.png
        ├── ...
        └── 13_return_rate.png
```

## Open and Run in VS Code

1. Download and extract the project ZIP file.
2. Open **VS Code**.
3. Select **File → Open Folder** and choose `Retail_Sales_Career_Shaper_Project`.
4. Install the **Python** and **Jupyter** extensions if VS Code prompts you.
5. Open the VS Code terminal using **Terminal → New Terminal**.
6. Create a virtual environment:

   **Windows (PowerShell):**
   ```powershell
   py -m venv .venv
   .venv\Scripts\Activate.ps1
   ```

   If PowerShell blocks activation, you can use Command Prompt instead:
   ```bat
   .venv\Scripts\activate.bat
   ```

7. Install the project libraries:
   ```bash
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```
8. Open `Retail_Sales_Data_Visualization_Analysis.ipynb`.
9. When prompted, select the Python interpreter from `.venv` as the notebook kernel.
10. Choose **Run All** to run the notebook cells.

The notebook expects the cleaned CSV at `data/retail_customer_sales_cleaned.csv`. Keep the folder structure unchanged so the relative data path works.

## Run the Optional Streamlit Dashboard
After installing the requirements, run this command from the project root:

```bash
streamlit run dashboard/app.py
```

Streamlit will display a local address in the terminal. Open that address in your browser. The dashboard provides KPI cards and filters for year, region, and product category.

## Project Outputs
- Jupyter Notebook containing the Python analysis
- Cleaned retail dataset in `data/`
- Thirteen chart images in `reports/charts/`
- Compiled visual analysis report in PDF format
- Optional Streamlit dashboard

## Key Performance Indicators
The prepared dataset contains 7,000 records. The following overall values were calculated from the cleaned dataset:

| KPI | Value |
|---|---:|
| Total Sales | 76,731,189.27 |
| Total Profit | 25,127,882.66 |
| Profit Margin | 32.75% |
| Average Order Value | 10,961.60 |

Values are based on the cleaned dataset included in this project. They may differ if the data or cleaning steps are changed.

## Libraries
See `requirements.txt` for the Python packages used by the notebook and optional dashboard.

## Author
MCA Student Project — Retail Sales Data Visualization and Analysis Using Python.

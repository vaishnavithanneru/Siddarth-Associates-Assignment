  ## Project Overview  
This project successfully transforms messy, unstructured international trade data (2017 – Aug 2025) into a clean, structured, and fully interactive analytics solution using **Python → CSV → Power BI** — no complex drivers or account issues.

### Key Deliverables & Achievements  
- Advanced **text parsing** of `Goods Description` using regex → extracted:  
  `model_name`, `model_number`, `capacity_spec`, `material_type`, `unit_price_usd`  
- Unit standardization & feature engineering (Grand Total, Landed Cost per Unit, Duty %)  
- Hierarchical **Category → Sub-Category** logic  
- Cleaned dataset exported as `shipments.csv` (Power BI ready)  
- Fully interactive **Power BI dashboard** satisfying **Task 5** 100%  

## Folder Structure 
International_Trade_Analysis_Assignment/
├── data/
│   ├── raw/                     → Sample Data 2.xlsx (original)
│   └── processed/
│       ├── shipments.csv        → Final clean data (used in Power BI)
│       └── trade_data_cleaned.xlsx
├── notebooks/
│   └── Trade_Data_Pipeline.ipynb → Complete Python pipeline (text parsing + cleaning)
├── trade_analysis.db            → SQLite version (optional)
├── shipments.csv                → Final dataset (same as in processed folder)
├── Trade_Dashboard_Using_shipments_csv.pbix → Complete interactive Power BI dashboard
└── README.md                    → This file


## How to Reproduce  
1. Open `notebooks/Trade_Data_Pipeline.ipynb`  
2. Run all cells → automatically generates:  
   - `shipments.csv`  
   - All parsed columns & categories  
3. Open `Trade_Dashboard_Using_shipments_csv.pbix` in Power BI Desktop  
4. All visuals load instantly — no connection errors  

## Power BI Dashboard – Task 5 (100% Complete)  
| Requirement                        | Implemented? | Visual Type           |
|------------------------------------|--------------|-----------------------|
| Macro Trends (2017–2025)           | Yes          | Line + Column Chart   |
| YoY Growth Heatmap                 | Yes          | Matrix with conditional formatting |
| Category → Sub-Category → Model    | Yes          | Interactive **Sunburst** (drill-down) |
| Top Suppliers by Value             | Yes          | Horizontal Bar Chart  |
| Active vs Churned Suppliers (2025) | Yes          | Donut Chart + Table   |
| Unit Economics (Capacity vs Cost)  | Yes          | Scatter Plot (with tooltips) |

**All visuals are interactive, filtered by year, and professionally formatted.**

## Tech Stack  
- Python (pandas, regex)  
- Jupyter Notebook  
- SQLite → CSV (simple & reliable)  
- Power BI Desktop  


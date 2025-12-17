# Equipment Maintenance & Performance Analysis

## Project Overview
This project analyzes machine maintenance data from the AI4I 2020 Predictive Maintenance dataset to identify trends, failures, and optimization opportunities. Key operational metrics such as tool wear, rotational speed, and torque are explored to calculate Mean Time Between Failures (MTBF) and approximate Overall Equipment Effectiveness (OEE). High-risk product variants are identified with actionable recommendations for preventive maintenance.

---

## Dataset
- **Source:** [AI4I 2020 Predictive Maintenance Dataset](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)
- **Records:** 10,000
- **Features:** Air temperature, Process temperature, Rotational speed, Torque, Tool wear, Product type, Failure type
- **Targets:** Failure (binary), Failure Type (categorical)

---

## Tools & Skills
- Python (Pandas, Matplotlib, Seaborn)
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Key Metrics: MTBF, OEE
- Data Visualization
- Reporting & Insights

---

## Folder Structure
```

Equipment_Maintenance_Analysis/
│
├── data/
│   ├── AI4I_2020_Predictive_Maintenance.csv
│   ├── ToolWear_per_Product.csv
│   ├── OEE_per_Product.csv
│   └── HighRisk_Products.csv
│
├── notebooks/
│   └── EDA_and_Insights.ipynb
│
├── reports/
│   └── Summary_Tables_and_Charts.pdf
└── README.md

````

---

## Key Analysis & Insights
- Identified product variants with the **highest failure rates**  
- Calculated **average tool wear** per product variant  
- Approximated **Overall Equipment Effectiveness (OEE)** for all machines  
- Determined **high-risk products/machines** for preventive maintenance  
- Visualized failure trends, tool wear distribution, and OEE comparisons  

---

## Usage
1. Clone the repository:

git clone https://github.com/vishmi11/Equipment_Maintenance_Analysis.git


2. Open the notebook in Jupyter or Colab
3. Run the notebook step by step to reproduce the analysis.
4. CSV files in `data/` can be used for further analysis or dashboard creation.
5. `reports/Summary_Tables_and_Charts.pdf` contains key tables and visualizations.

---

## License

This project is open-source for educational purposes.

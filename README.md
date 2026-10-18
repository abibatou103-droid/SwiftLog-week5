# SwiftLog Logistics Data Science Project

This repository contains the Week 5 Data Science project for SwiftLog Logistics. The objective is to inspect operational logistics data, clean and transform it, explore business patterns, engineer features, and produce a business-ready dataset for further predictive analytics.

## Project overview

SwiftLog Logistics manages customer orders, shipments, warehouses, inventory, products, suppliers, returns, and delivery performance. The project uses these datasets to answer key operational questions such as:

- Which products drive the most revenue?
- Which warehouses and regions have the highest delivery delays?
- Which customers are the most valuable?
- Which suppliers are the most reliable?
- Which products have the highest return risk?
- What features can be used to predict late deliveries or returns?

## Dataset files

- `SwiftLog_Customers.csv`
- `SwiftLog_Orders.csv`
- `SwiftLog_Order_Items.csv`
- `SwiftLog_Products.csv`
- `SwiftLog_Shipments.csv`
- `SwiftLog_Delivery_Performance.csv`
- `SwiftLog_Inventory.csv`
- `SwiftLog_Warehouses.csv`
- `SwiftLog_Employees.csv`
- `SwiftLog_Returns.csv`
- `SwiftLog_Suppliers.csv`
- `SwiftLog_Data_Dictionary.csv`

## Folder structure

```text
swiftlog-week5/
├── README.md
├── notebooks/
│   └── SwiftLog_DataScience_Week5.ipynb
├── outputs/
│   └── swiftlog_feature_dataset.csv
├── SwiftLog_Customers.csv
├── SwiftLog_Orders.csv
├── SwiftLog_Order_Items.csv
├── SwiftLog_Products.csv
├── SwiftLog_Shipments.csv
├── SwiftLog_Delivery_Performance.csv
├── SwiftLog_Inventory.csv
├── SwiftLog_Warehouses.csv
├── SwiftLog_Employees.csv
├── SwiftLog_Returns.csv
├── SwiftLog_Suppliers.csv
├── SwiftLog_Data_Dictionary.csv
└── requirements.txt
```

## Workflow included

The notebook covers the requested end-to-end Data Science workflow:

1. Dataset loading and basic inspection
2. Data quality profiling
3. Missing values and duplicate checks
4. Data cleaning and standardisation
5. Dataset merging and feature construction
6. Exploratory Data Analysis (EDA)
7. KPI and descriptive statistics
8. Feature engineering for predictive tasks
9. Business insight extraction and operational recommendations

## Key business questions answered

- Which regions and warehouses experience the highest delays?
- Which product categories create the most revenue?
- Which return reasons are most common?
- Which customer groups create the most value?
- What features can be used for late-delivery or return prediction?

## Environment setup

To run the notebook locally, create a virtual environment and install the requirements:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Requirements

The project uses the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- jupyter
- notebook

## Project output

The cleaned and feature-enriched dataset is saved as:

- `outputs/swiftlog_feature_dataset.csv`

This output is suitable for:

- warehouse performance analysis,
- late delivery prediction,
- return-risk analysis,
- customer value segmentation,
- operational forecasting.

## Recommended next steps

- build a classification model for late delivery risk,
- build a return-risk model for high-risk products,
- add a dashboard for warehouse and supplier performance,
- combine the generated feature dataset with business KPIs for executive reporting.

## License

This project is for educational and portfolio use.

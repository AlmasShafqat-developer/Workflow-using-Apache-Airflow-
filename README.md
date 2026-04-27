#  Airflow ETL Project

##  Project Overview
This project is an **ETL (Extract, Transform, Load) pipeline** built using **Apache Airflow**.  
It automates data extraction from CSV files, performs data cleaning and transformation using Python, and loads the processed data for further analysis.

---

## ⚙️ Technologies Used
- Python 
- Apache Airflow 
- Pandas 
- NumPy 
- SQL (if used)
- CSV files for data source

---

## Project Structure
airflow-etl-project/
│
├── dags/ # Airflow DAG files
├── data/ # CSV datasets
├── scripts/ # Python ETL scripts
├── requirements.txt # Project dependencies
└── README.md # Project documentation


---

##  ETL Workflow

### 1. Extract
- Data is extracted from CSV files stored in the `data/` folder.

### 2. Transform
- Data cleaning (handling missing values, duplicates)
- Data formatting and preprocessing using Pandas

### 3. Load
- Processed data is saved or prepared for analysis/reporting

---

##  How to Run the Project

### Step 1: Install dependencies
```bash
pip install -r requirements.txt
Step 2: Start Airflow
airflow db init
airflow webserver
airflow scheduler
Run DAG
Open Airflow UI at http://localhost:8080
Trigger the DAG manually or wait for schedule

Features
Automated ETL pipeline using Airflow
Modular Python scripts
CSV-based data processing
Easy to extend for databases or APIs

Future Improvements
Add database integration (MySQL/PostgreSQL)
Add API-based data extraction
Deploy Airflow on cloud (AWS/GCP)



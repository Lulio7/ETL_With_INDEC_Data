# ETL Project - National Consumer Price Index (IPC) - Argentina

This project builds a simple ETL pipeline using open data from Argentina's national statistics office (INDEC). It focuses on the **monthly evolution of the Consumer Price Index (IPC)**, a key macroeconomic indicator that reflects inflation trends across the country.

## 📌 Data Source

Dataset Name: Índice de Precios al Consumidor (IPC) - Nacional Promedio Mensual
Organization: INDEC (Instituto Nacional de Estadística y Censos), Ministerio de Economía de Argentina
Format: CSV (Comma-separated values)
Update Frequency: Monthly
Data Portal: https://datos.gob.ar
Dataset URL: INDEC - IPC Nacional
Direct CSV Link: Download CSV

## 🛠️ Tools & Technologies

- **Python**: Main language for scripting and data manipulation
- **pandas**: Data cleaning and transformation
- **requests**: Extracting data from an open CSV URL
- **SQLAlchemy**: Loading structured data into a SQLite database
- **SQLite**: Lightweight, file-based relational database for storing transformed data

## 🔁 ETL Process

- **Extract**: Download raw data from the INDEC public dataset URL (datos.gob.ar)
- **Transform**: Normalize column names, convert dates, remove null values, and standardize formats
- **Load**: Save the cleaned data into a local SQLite database (`ipc_data.db`) for future analysis

## 📊 Potential Insights

- Identify **monthly and annual inflation trends**
- Compare **price index growth over time**
- Analyze inflation behavior during specific **economic or political events**
- Use cleaned data for **dashboard creation** or **machine learning models**

## 🚀 How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt

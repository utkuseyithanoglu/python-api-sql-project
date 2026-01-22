
# API to SQL Data Pipeline
## Overview
This project focuses on building a simple end-to-end data pipeline using a public API.  
The data is fetched from an external API, processed with Python and Pandas, stored in a SQLite database, and queried using SQL.

The goal of this project is to demonstrate **API integration, data transformation, and basic SQL querying**, suitable for junior-level data analyst and data science roles.

---

## Dataset
The dataset is retrieved from a public API and contains character-related information such as:
- Name
- House
- Birthdate
- Age
- Additional attributes (e.g., children information)

The raw JSON data is transformed into a structured tabular format before being stored.

---

## Methods & Techniques
- API requests using `requests`
- JSON data parsing
- Data cleaning and transformation with Pandas
- Exporting data to CSV format
- Loading data into SQLite database
- SQL querying using `pd.read_sql()`

---

## Model / Data Workflow
1. Fetch data from a public API
2. Convert JSON response into a Pandas DataFrame
3. Clean and organize the dataset
4. Save the processed data as a CSV file
5. Load the CSV into a SQLite database
6. Run SQL queries for data exploration and analysis

---

## Example SQL Queries

```sql
SELECT *
FROM time
WHERE house = 'Gryffindor';

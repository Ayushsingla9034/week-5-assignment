# Week 5 Assignment – Copy Data from Database to CSV, Parquet, and Avro

This project demonstrates how to connect to a PostgreSQL database (using Neon), read data from a table, and export it to multiple file formats. It also simulates pipeline automation with scheduled execution using Python.

---

# Objectives

- Connect to a PostgreSQL database hosted on [Neon](https://neon.tech)
- Read data from a table (e.g., `students`)
- Export the data into:
  - `CSV` format (students.csv)
  - `Parquet` format (students.parquet)
  - `Avro` format (students.avro)
- Simulate a scheduled pipeline using Python
- Upload all files and code to GitHub

---

# Tools & Technologies

- **Python**
- **Pandas**
- **SQLAlchemy**
- **Psycopg2**
- **PyArrow**
- **Fastavro**
- **Google Colab** (to run code)
- **GitHub** (for version control)

---

# Files Included

| File Name           | Description                            |
|---------------------|----------------------------------------|
| `students.csv`      | Data exported in CSV format            |
| `students.parquet`  | Data exported in Parquet format        |
| `students.avro`     | Data exported in Avro format           |
| `export_script.py`  | Python script to connect and export    |
| `README.md`         | This explanation file                  |

---

# How to Run (Steps Followed)

1. Connected to NeonDB using SQLAlchemy and Psycopg2.
2. Read the data using Pandas from the `students` table.
3. Exported data to:
   - CSV: using `df.to_csv()`
   - Parquet: using `df.to_parquet()`
   - Avro: using `fastavro`
4. Automated the export using a Python function with `time.sleep()` to simulate scheduling.
5. Uploaded the output files and script to GitHub.

---

# Author

**Ayush singla**  
Student, B.Tech CSE – Chandigarh University  
[GitHub Profile](https://github.com/Ayushsingla9034)

---

# Notes

- This is a sample internship assignment to practice data integration and automation.
- For actual pipelines, tools like Apache Airflow or cloud functions can be used.


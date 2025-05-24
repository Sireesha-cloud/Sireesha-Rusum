
# 📊 ETL Pipeline Development using Python, SQLite, and Jupyter Notebook

## 📖 Project Overview
This project demonstrates the development of an **ETL (Extract, Transform, Load) pipeline** using **Python**, **Pandas**, and **SQLite** for processing and analyzing structured sales transaction data. The pipeline automates the workflow of extracting data from a CSV file, transforming it by cleaning and enhancing it, and loading it into a relational database for efficient querying and analysis.

## 📦 Dataset
The dataset used is a sample sales transactions CSV file containing the following fields:

- TransactionID
- Date
- Customer
- Product
- Quantity
- Price

A sample of 10 records is provided, and the pipeline is scalable for larger datasets.

## 🛠️ Technologies Used
- Python 3.11
- Pandas
- SQLite3
- Jupyter Notebook
- Git / GitHub

## 📂 Project Structure

etl_pipeline_sqlite/
├── data/
│   └── sales_data.csv
├── etl_pipeline.ipynb
├── sales_data.db
└── README.md

## 🚀 Features
- **Extract:** Reads structured sales data from a CSV file.
- **Transform:** Converts date strings, calculates total sales, renames and reorganizes columns.
- **Load:** Inserts cleaned and enhanced data into a SQLite database.
- **Data Verification:** Queries the database to verify data integrity post-load.

## 📈 How to Run
1. Clone the repository
2. Install required packages (`pip install pandas`)
3. Open `etl_pipeline.ipynb` in Jupyter Notebook
4. Run all cells sequentially
5. Verify database records via SQL queries

## 📊 Sample Output

| TransactionID | Date       | CustomerName  | Product  | Quantity | Price | TotalSale |
|:--------------|:------------|:---------------|:----------|:-----------|:--------|:------------|
| 1001             | 2024-05-01 | John Doe         | Keyboard | 2             | 45.99  | 91.98        |

## 📄 License
This project is open-source and available under the MIT License.

## 🙌 Acknowledgements
Inspired by real-world ETL workflows and database management practices.

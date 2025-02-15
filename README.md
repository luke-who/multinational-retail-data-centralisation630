# Project Title
**Multinational Retail Data Centralisation**

---

## Table of Contents
- [Project Title](#project-title)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
    - [Objectives](#objectives)
  - [Installation](#installation)
  - [Usage](#usage)
  - [File Structure](#file-structure)
  - [License](#license)

---

## Description
This project is a data cleaning and extraction pipeline designed to process and clean data from multiple sources (e.g., CSV files, APIs, databases) and upload the cleaned data to a local PostgreSQL database. The aim of the project is to demonstrate proficiency in data cleaning, extraction, and database management using Python, pandas, and SQLAlchemy.

### Objectives
- How to extract data from various sources (CSV, API, database).
- Techniques for cleaning and transforming data using pandas.
- How to upload cleaned data to a PostgreSQL database.
- Best practices for version control and documentation using GitHub.

---

## Installation
To run this project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. **Set Up a Virtual Environment (conda)**:
3. **Install Dependencies**:
4. **Set Up PostgreSQL Database**:

## Usage

1. **Run the Main Script:**
   ```
   python main.py
   ```
2. **View Cleaned Data**:
   Connect to your PostgreSQL database and query the tables (e.g., dim_users, dim_products, orders_table).

## File Structure
```
your-repo-name/
├── data_cleaning.py          # Contains data cleaning methods
├── data_extraction.py        # Contains data extraction methods
├── database_utils.py         # Contains database connection and upload methods
├── main.py                   # Main script to run the pipeline
├── requirements.txt          # List of dependencies
├── README.md                 # Project documentation
├── aws_db_creds.yaml         # AWS RDS database credentials
└── local_db_creds.yaml       # Local PostgreSQL database credentials
```

## License

# Data Pipeline with Python, MongoDB and MySQL

This project was developed by Nowa Analytics as a data engineering solution for an e-commerce company.
Our task was to design and implement a **data pipeline** that ingests product sales data from an API, stores it in both **NoSQL** and **relational** databases, and makes it available for different internal teams.



## Project Overview

The company’s product sales data is available through an API.
Our mission was to:

1. **Extract** the raw product data from the API.
2. **Load** this raw data into **MongoDB** so the Data Science team could access it in its unprocessed form.
3. **Transform** the data to match the requirements of the Business Intelligence (BI) team.
4. **Load** the transformed data into **MySQL** tables for easy querying and reporting.

This pipeline allows both **Data Science** and **BI** teams to work with the same dataset in the format that best suits their needs.



## Technologies Used

* **Python 3**
* **MongoDB Atlas** (NoSQL database)
* **MySQL** (Relational database)
* **PyMongo** (MongoDB Python driver)
* **mysql-connector-python** (MySQL Python driver)
* **WSL** (Windows Subsystem for Linux, for MySQL setup)



## Pipeline Steps

1. **Data Extraction**

   * Connect to the API endpoint
   * Fetch raw product sales data in JSON format

2. **Raw Data Storage** (MongoDB)

   * Configure MongoDB Atlas
   * Store API data in collections for direct access by the Data Science team

3. **Data Transformation**

   * Apply cleaning and structuring logic in Python
   * Prepare tabular datasets for BI use cases

4. **Structured Data Storage** (MySQL)

   * Install and configure MySQL in WSL
   * Create database schema and tables
   * Insert processed data into MySQL for reporting and dashboard integration



## Folder Structure

```
📂 data-pipeline
├── 📁 src               # Python scripts for ETL pipeline
├── 📁 config            # Database and API configuration files
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
└── .env.example         # Environment variable template
```



## Key Learning Points

* Building a full **ETL pipeline** in Python
* Configuring and connecting to **MongoDB Atlas**
* Using **PyMongo** to handle NoSQL operations
* Setting up **MySQL** in WSL
* Connecting Python to MySQL for relational storage
* Structuring Python code into reusable **functions**



## Contribution

This project is part of the Nowa Analytics Data Engineering portfolio. Contributions and suggestions are welcome via pull requests or issues.


## Contact

**Nowa Analytics**
Delivering data-driven solutions for business impact.
🌍 Offices in London | Madrid | São Paulo
📧 [contact@nowaanalytics.com](mailto:contact@nowaanalytics.com)

---


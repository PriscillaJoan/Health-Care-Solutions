**Project Title:** _(Health Care Analysis)_

## Project Overview

The Health Care Solutions project leverages data science techniques to analyze and visualize healthcare data. The goal is to identify patterns, trends, and areas for improvement within healthcare facilities. The project includes an analysis of healthcare facilities, population data, and health-related metrics.

## Data Sources

The data used in this project comes from various sources:

- **ehealth-kenya.xls**: Contains detailed information about healthcare facilities in Kenya.
- **population.csv**: Contains population data used to provide context and insights into healthcare needs.

## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the repository**:

   ```
   git clone https://github.com/PriscillaJoan/Health-Care-Facilities.git
   ```

2. **Navigate to the project directory**:

   ```
   cd Health-Care-Solutions
   ```

## Usage

To run the project and see the analysis:

1. **Open the Jupyter Notebook**:

   ```
   jupyter notebook
   ```

2. **Navigate to the `merging data sets and data cleaning and database conversion.ipynb` notebook** in the Jupyter interface and run the cells to execute the analysis and create an sql script that will help in creating the database.

---

### Key Features:
- **SQL Database**: Contains health facility data in a structured format, with several tables for querying.
- **Jupyter Notebooks**: They include the data cleaning and merging of datasets.
- **Tableau Workbook**: Provides a detailed analysis of the different insights captured from the data.
- **Data Base Design Image**: Visualizes the different relationships between tables.

---
## Project Structure

This repository contains the following files:

1. **datacleaning and database conversion.ipynb**: jupyter notebook containing the data cleaning process and conversion of health facilities data into an SQL script.
2. **combining datasets.ipynb** jupyter notebook for combining population data and health facilities data.
3. **database.sql`**: SQL file with the database schema and initial data setup.
4. **data_distribution.png**:image visualizing relationships between the tables.
5. **table_story.txt**: link to the tableau story showcasing insights from the data.
6. **Tableau Workbook**: workbook containing data insights generated from tableau.
7. **Nairobi_data**: CSV file with data on health facilities in nairobi.
8. **Population** : CSV with population data for nairobi.
9. **Facilities_data**: combined CSV file of nairobi health facilities data and population data.
10. **ehealth-kenya.xls**: excel file with health facilities data for the entire country.
---

## Requirements

Before running the project, ensure you have the following installed:

- **Jupyter Notebook** (or any IDE that supports `.ipynb` files)
- **SQLite/MySQL/PostgreSQL** (depending on the database system you're using)
- **Pandas**, **Seaborn**, **Matplotlib** (for data visualization)
- **Tableau** To interact with the tableau workbook containing the data insights

---

## Data Base Design Image

Here is a brief description of the tables in the database:

- **Table 1 (Health Facilities)**: Contains information about health facilities, including their names, types, and locations.
- **Table 2 (Services info)**: Lists the services provided by each facility, such as IPD, ART, and maternity services.
- **Table 3 (Staff Info)**: Has information about the staff.
- **Table 4 (Operations Info)**: Has information about the time of operations for the facilities

---

## Usage

To interact with the project, follow these steps:

- **SQL Queries**: Use the SQL queries in the Jupyter Notebook or directly query the database using your SQL tool (MySQL Workbench, SQLite Browser, etc.).
- **Database Insights**: Read the `data base design.png` image to understand the structure and purpose of each table in the database.

---

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request. We welcome any improvements or suggestions!

---

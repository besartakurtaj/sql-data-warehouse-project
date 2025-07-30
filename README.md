
## Data Warehouse ETL Pipeline: Bronze → Silver → Gold

This project implements a **data warehouse pipeline** using the **Bronze–Silver–Gold architecture**. The pipeline extracts raw data from CRM and ERP sources, transforms and cleans it through ETL processes, and loads business-ready data into dimensional tables for analysis and reporting.

---

### Data Architecture

<img width="993" height="467" alt="image" src="https://github.com/user-attachments/assets/3c09502f-e23c-4a35-b430-4a0991d5a97a" />

### Data Flow

<img width="1050" height="512" alt="image" src="https://github.com/user-attachments/assets/b945cb7f-17f7-4564-bb60-f0c25312eb3e" />

### Data Integration

<img width="1245" height="491" alt="image" src="https://github.com/user-attachments/assets/2fcadd44-a428-4252-b92c-ca04d7f18eca" />

### Data Model

<img width="1011" height="582" alt="image" src="https://github.com/user-attachments/assets/d78832ae-2f2d-46cc-aed2-3c82766e05e5" />

---

### Technologies Used

* **SQL Server** (staging, transformations, views)
* **Draw\.io** (for diagrams)
* **Git/GitHub** (version control)

---

### Getting Started

1. Clone the repo:

   ```bash
   git clone https://github.com/besartakurtaj/sql-data-warehouse-project
   cd sql-data-warehouse-project
   ```

2. Review the ETL scripts.

3. Use the diagrams to understand the data flow.

4. Set up the database layers using the schema provided.

5. Load the CSV files into the Bronze layer.

### To Do / Future Improvements

* Add Python ETL scripts for automation
* Connect with Power BI for visualization
* Add test cases for data validation

---

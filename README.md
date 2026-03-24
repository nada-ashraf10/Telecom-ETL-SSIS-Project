# Telecom-ETL-SSIS-Project

## 📌 Project Overview
This project demonstrates a complete **ETL (Extract, Transform, Load) Pipeline** designed for Telecom data. Using **SQL Server Integration Services (SSIS)**, the system processes raw call and device data from CSV files, applies complex business logic and data quality rules, and loads the cleaned data into a **Data Mart** for analysis.

<img width="1652" height="852" alt="image" src="https://github.com/user-attachments/assets/09fae675-1bdd-46f0-a14e-8f07acf17de9" />


## 🛠️ Tech Stack
* **ETL Tool**: Microsoft SQL Server Integration Services (SSIS).
* **Database**: Microsoft SQL Server.
* **Data Source**: Flat Files (CSV).
* **Version Control**: Git & GitHub.

<img width="1658" height="791" alt="image" src="https://github.com/user-attachments/assets/8bb25f1d-8592-45c9-8f97-3b53f9a1101d" />


## ⚙️ ETL Architecture & Features
The pipeline includes several advanced transformation steps:
* **Data Cleaning**: Handled null values and standardized timestamps.
* **IMSI & IMEI Parsing**: Implemented logic to parse IMEI into TAC/SNR for device identification.
* **Data Quality Rules**: Built-in validation to ensure data integrity before loading.
* **Error Handling**: Integrated rejected record handling to manage data that fails validation.
* **Batch Processing**: Automated processing of multiple data batches (Batch 01, Batch 02).

## 📂 Repository Structure
* **`ETL_DWH2/`**: Contains the Visual Studio Solution and SSIS Packages (`.dtsx` files).
* **`Source Files/`**: Original raw CSV data.
* **`pros files/`**: Cleaned and processed CSV files ready for loading.
* **`Docs/`**: Project documentation, including Case Studies and Lab instructions.

## 🚀 How to Run
1.  Clone the repository:
    `git clone https://github.com/nada-ashraf10/Telecom-ETL-SSIS-Project.git`.
2.  Open the solution file in **Visual Studio** with SQL Server Integration Services installed.
3.  Update the **Connection Managers** to point to your local file paths and SQL Server instance.
4.  Execute the SSIS packages.

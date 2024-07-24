Here’s a polished and engaging README for your GitHub repository:

---

# Snowflake ELT Pipeline with dbt and Airflow

Welcome to the Snowflake ELT Pipeline project! 🚀 This repository showcases a complete end-to-end data pipeline built using cutting-edge technologies, including Snowflake, dbt (Data Build Tool), and Apache Airflow. Dive into the details to see how modern data engineering practices can transform and orchestrate data efficiently.


## Architecture Diagram

![Architecture Diagram](images/architecture-diagram.png)

## Project Overview

This project demonstrates the process of extracting data from the TPCH orders table in Snowflake's sample database, loading it into a Snowflake data warehouse, and transforming it using dbt. The pipeline is orchestrated with Apache Airflow, ensuring robust and automated workflow management.

### Key Components

1. **Data Source**:
   - **TPCH Orders Table**: The raw data source located in the Snowflake sample database.

2. **Data Storage**:
   - **Snowflake**: Utilized as the data warehouse for storing the raw and transformed data.

3. **Data Transformation**:
   - **dbt (Data Build Tool)**:
     - **Source Tables**: Definition and management of source tables.
     - **Staging Tables**: Intermediate tables for raw data processing.
     - **Transformed Models**: Creation of fact tables and data marts.
     - **Macro Functions**: Implementation of functions, including discount price calculations.
     - **Testing**: Generic and singular tests to ensure data integrity.

4. **Data Orchestration**:
   - **Apache Airflow**: Used to orchestrate and automate the data pipeline workflows.



Happy data engineering! 🌟
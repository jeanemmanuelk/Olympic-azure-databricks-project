# 🚀 Azure Data Engineering/Analysis Pipeline: (2021 Olympic_data-azure-databricks)

This project demonstrates an end-to-end data engineering pipeline built using Azure services. It ingests data from an HTTP source using Azure Data Factory, stores and processes it using Azure Data Lake and Databricks, and visualizes the results in Power BI.

---
## About Dataset

**Details**  
This contains the details of over 11,000 athletes, with 47 disciplines, along with 743 Teams taking part in the 2021 (2020) Tokyo Olympics.  
This dataset contains the details of the Athletes, Coaches, Teams participating as well as the Entries by gender. It contains their names, countries represented, discipline, gender of competitors, and name of the coaches.

Will update the dataset with medals (gold, silver, bronze), and more details about the athletes after a few weeks.

**Credits**  
Source: Tokyo Olympics 2020 Website

## 📌 Project Overview

- **Ingestion**: Azure Data Factory fetches data from a public HTTP endpoint.
- **Storage**: Raw data is stored in Azure Data Lake Storage Gen2.
- **Processing**: Azure Databricks transforms the raw data into a clean, analytics-ready format.
- **Analytics**: Transformed data is stored back in ADLS Gen2 and visualized using Power BI.

---

## 📊 Power BI Dashboard

You can view a sample report generated from the transformed data in the file below:

📄 [Power BI Dashboard (PDF)](./2021_tokyo_olympic_dashboard.pdf)

This report highlights key insights derived from the processed dataset and demonstrates how the pipeline supports analytical decision-making.

---

## 🧭 Architecture Diagram

The architecture of the pipeline is visualized below:

![Architecture Diagram](./Olympic%20flowchart.png)

---

## ⚙️ Technologies Used

- **Azure Data Factory** – Data ingestion from HTTP endpoint  
- **Azure Data Lake Storage Gen2** – Raw and transformed data storage  
- **Azure Databricks** – Data cleaning and transformation  
- **Power BI** – Interactive dashboard creation and reporting  

---

## 📁 Project Structure

├── notebooks/Tokyo Olympic data transformation # Databricks notebook (PySpark and SQL) for transformation and loading steps
├── pipeline/ # ADF pipeline JSON export
├── data/ # Sample data used for development/testing
├── 2021_tokyo_olympic_dashboard.pdf # Final Power BI report (exported as PDF)
├── Olympic%20flowchart.png # Visual representation of the pipeline
├── README.md # Project documentation (this file)

---

## 📬 Contact

Feel free to reach out if you have questions or want to connect.

**Jean-Emmanuel Kouadio**  
[LinkedIn](https://www.linkedin.com/in/j-emmanuel-k)  
Email: emmanuelkj5@gmail.com
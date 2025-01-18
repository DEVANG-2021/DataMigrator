# **DataMigrator - Automated ETL Pipeline for Data Migration**

## **Overview**
This project is an automated and deployable ETL (Extract, Transform, Load) pipeline designed to seamlessly migrate data from SSMS/SQL databases to **Snowflake** and **Amazon Redshift**, while preserving the integrity of relational data structures. The pipeline is tailored for handling large datasets and ensures end-to-end automation of the data migration process.

---

## **Features**
- **Data Ingestion:** Transfers data efficiently from **SSMS/SQL databases** to **Amazon S3** and subsequently to **Snowflake** and **Amazon Redshift**.
- **Automation:** Achieves full automation of the ETL process to optimize performance and maintain data integrity.
- **Scalability:** Designed to handle **large datasets** and ensure reliable data migration across multiple platforms.
- **Real-Time Data Transfer:** Incorporates **Apache Kafka** for streaming data in real-time.
- **Cloud Integration:** Utilizes **AWS** services for secure and efficient data storage and processing.

---

## **Technology Stack**
- **Programming Language:** Python
- **Data Streaming:** Apache Kafka
- **Cloud Platform:** AWS (Amazon Web Services)
- **Databases:** SSMS/SQL, Snowflake, Amazon Redshift
- **Storage:** Amazon S3

---

## **Pipeline Workflow**
1. **Extract:**
   - Connect to **SSMS/SQL databases** to extract raw data, ensuring relational structures are preserved.
2. **Transform:**
   - Process and prepare the data for migration while maintaining data consistency and integrity.
3. **Load:**
   - Upload the transformed data to **Amazon S3**, and then migrate it to **Snowflake** and **Amazon Redshift**.
4. **Automation:**
   - Use Python scripts, **AWS Lambda**, and **Apache Kafka** to automate and streamline the process.

---

## **Setup and Installation**

### **Prerequisites**
- Python 3.8 or higher
- Access to:
  - SSMS/SQL database
  - Snowflake and Amazon Redshift
  - AWS account with S3 and IAM configurations
- Apache Kafka setup for real-time streaming
- Required Python libraries (see `requirements.txt`)

### **Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/DEVANG-2021/DataMigrator.git
   cd DataMigrator
   ```
2. Install dependencies:
```bash


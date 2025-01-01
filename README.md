
# Global Weather Analytics Pipeline – Azure Data Engineering  

---

### Goal of the Project:  
Develop an end-to-end data pipeline to analyze and store global weather data, including temperature, humidity, precipitation, wind speed, and atmospheric pressure. The solution provides insights into weather patterns and trends for forecasting and decision-making.  

---

### Task of the Project:  

1. Data Ingestion:  
   - Fetch real-time and historical weather data from APIs like OpenWeatherMap.  
   - Store raw data in Azure Blob Storage.
   - Use Azure Data Factory to create pipelines for data ingestion.   

2. Data Processing:   
   - Apply transformations using PySpark in Azure Databricks to clean and normalize data.  
   - Enrich data by combining external datasets (e.g., geographical and population data).  

3. Data Storage:  
   - Store raw, processed, and lookup data in Azure Data Lake Storage Gen2.  
   - Load transformed data into Azure SQL Database for structured analysis.  

4. Data Modeling:  
   - Design a star schema for the weather data warehouse in Azure SQL DB.  
   - Build tables for dimensions (location, time, weather conditions) and facts (daily metrics).  

5. Reporting and Visualization:  
   - Connect Power BI to Azure SQL DB to create interactive dashboards for weather insights.  


---

### Services Used:  

1. Azure Data Factory - For pipeline orchestration, ETL, and automation.  
2. Azure Blob Storage - To store raw weather data.  
3. Azure Data Lake Storage Gen2 - To organize raw, processed, and lookup data.  
4. Azure Databricks - For data transformation using PySpark.  
5. Azure SQL Database - To build a data warehouse and store structured data.  
6. Azure Key Vault - To securely store API keys and connection strings.  
7. Power BI - For visualizing weather insights.  



![My Diagram](./image.png)



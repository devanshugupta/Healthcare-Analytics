# healthcare_analytics

HealthCare Analytics Pipeline that takes data from the SQL Server and Puts in into the Data Lake Gen 2, Then performs ETL transformations using Spark and uses Data Warehousing techniques to create data marts. Then Synapse Analytics transfers the data into Power BI to create analytics reports. Databricks also uses Machine Learning models to predict the new User's data which is done by CDC (change data capture) for both training and testing data.

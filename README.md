
# Data Engineering Project for CIS 4400
#### Building a Pipeline for CME Data Processing

## Overview
### Description

##### This repository encompasses Python code snippets designed to create a robust data processing pipeline for a Data Engineering project associated with CIS 4400. The primary tasks include reading a JSON data from the CME website, converting it into a pandas dataframe and downloading it as a csv, and subsequently uploading it to Azure Blob Storage. The data undergoes a cleaning process, specifically targeting columns with null values. The cleaned dataset is then transferred to a data warehouse, with Google BigQuery being the chosen platform for this project. Additionally, Pandas, NumPy, and Matplotlib are employed for data visualization.

### Key Components
#### Data Retrieval:
##### Fetches JSON data from the CME website.
#### Data Conversion:
##### Converts the acquired JSON data into a CSV format.
#### Azure Blob Storage:
##### Uploads the CSV data to Azure Blob Storage for efficient and scalable storage.
#### Data Cleaning:
##### Removes columns with null values to ensure data integrity.
#### Data Warehouse Integration:
##### Utilizes Google BigQuery as the data warehouse for persistent storage and streamlined retrieval.
#### Visualization:
##### Leverages Pandas, NumPy, and Matplotlib for data visualization to derive meaningful insights.
### Technologies Used
#### -Python
#### -Pandas
#### -NumPy
#### -Matplotlib
#### -Azure Blob Storage
#### -Google BigQuery

**Data Dictionary**: Sheet 1 (Cleaned), Sheet 2 (Uncleaned)
 https://docs.google.com/spreadsheets/d/1IdQ7iA6eHaSGUW5JOBv3bBK6NkYCvbhffg5YaxwN5Bs/edit?usp=sharing

![Screenshot 2023-12-10 at 12 51 52 AM](https://github.com/TENPEL08/cmeDataEngineeringPipeline/assets/74534392/3caf55b5-940d-4112-80c8-22ed7ee97736)

![Screenshot 2023-12-10 at 12 52 38 AM](https://github.com/TENPEL08/cmeDataEngineeringPipeline/assets/74534392/5ad7596e-ab90-455d-986d-ba8a31204860)


## Conclusion
##### This project aims to establish a comprehensive data processing pipeline, ensuring seamless data retrieval, conversion, storage, and visualization. The combination of Azure Blob Storage and Google BigQuery facilitates a scalable and efficient workflow. The visualization tools enhance the project's analytical capabilities, allowing for a deeper understanding of the processed data.

###### Note: Additional details on the project's purpose and specific visualizations could further enhance the comprehensibility of the overview.

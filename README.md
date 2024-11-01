
# Data Science Job Market Analysis

## Description
This project leverages Databricks and MongoDB to analyze data science job postings, identifying key trends in job skills, postings, and summaries. Insights gained aim to provide an overview of the current demand in the tech industry.

## Prerequisites
Before you begin, ensure you have the following:
- Databricks account
- MongoDB account with data
- PySpark setup in Databricks
- MongoDB Spark Connector installed

## Setup Instructions

### Step 1: Create and Configure Databricks Cluster
1. Log in to your Databricks account.
2. Navigate to the ‘Clusters’ section and click ‘Create Cluster’.
3. Choose the Databricks Runtime Version that includes Apache Spark and is compatible with the MongoDB Spark Connector.
4. Set the cluster mode to ‘Standard’ or ‘High Concurrency’.
5. Adjust the Worker and Driver type based on computational needs.
6. Start the cluster.

### Step 2: Install MongoDB Spark Connector
1. Go to ‘Libraries’ under your cluster’s options.
2. Click ‘Install New’ then select ‘Maven’.
3. Search for and select the MongoDB Spark Connector using Maven coordinates:
   ```plaintext
   org.mongodb.spark:mongo-spark-connector_2.12:3.0.1
   ```
4. Install the library and ensure it attaches to your cluster.

### Additional Information on Notebooks
1. **AIT614_FinalProject_Team7 notebook**: Contains some data analysis of the dataset and machine learning models.
2. **EDA Notebook**: Contains detailed exploratory data analysis of the project.

### Step 3: Import and Run the Project Notebook
1. Download the project notebook ZIP file to your local system.
2. Navigate to the ‘Workspace’ area in Databricks.
3. Right-click the workspace folder, select ‘Import’, and choose the ZIP file.
4. Confirm the upload to import your project notebook.
5. Open the notebook titled ‘AIT614_FinalProject_Team7’ or ‘EDA’.
6. Attach the notebook to the cluster where the MongoDB Spark Connector is installed.
7. Execute the code cell by cell, following any additional instructions within the notebook.

### Step 5: Access the Tableau Dashboard
To view the visualizations created for this project, follow the link to the Tableau Public dashboard:

### View Tableau Dashboard
1. This dashboard provides a graphical representation of key findings from the data analysis using this [link](https://public.tableau.com/views/Book1_17137080069020/Dashboard1?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link).

## Usage
Execute the notebooks in the Databricks workspace, which contain scripts for loading data from MongoDB, processing, and analyzing it. Documentation within each notebook guides through data ingestion, cleaning, analysis, and visualization tasks.

## Authors
1. Nithish Bilasunur Manjunatha Reddy
2. Rakesh Somukalahalli
3. Pritham Mahajan
4. Sai Sriram Dubasi

## References
1. The ambiguity of data science team roles and the need for a data science workforce framework. (2017, December 1). IEEE Conference Publication | IEEE Xplore. [https://ieeexplore.ieee.org/document/8258190](https://ieeexplore.ieee.org/document/8258190)
2. GlassDoor Job Description Analytics – Analyzing Data science Professional roles and skills. (2021, April 21). IEEE Conference Publication | IEEE Xplore. [https://ieeexplore.ieee.org/document/9453931](https://ieeexplore.ieee.org/document/9453931)
   Shapiro, J. (2023, September 8). 4 Skills the next generation of data scientists needs to develop. Harvard Business Review. [https://hbr.org/2023/09/4-skills-the-next-generation-of-data-scientists-needs-to-develop](https://hbr.org/2023/09/4-skills-the-next-generation-of-data-scientists-needs-to-develop)
3. Van Loon, R. (2024, January 16). Top 20+ Data Scientist skills You need in 2024. [Simplilearn.com](https://www.simplilearn.com/what-skills-do-i-need-to-become-a-data-scientist-article)
4. The Global AI, ML, Data Science Salary Index for 2024. (n.d.). [ai-jobs.net](https://ai-jobs.net/salaries/2024/)

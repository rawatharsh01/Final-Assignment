# Final-Assignment -
This is Assignment 5 generating a storage document by including a Python document utilized from the preceding task and elaborating on the Python document in a readme.md comprehensively.

**Data Selection** - In this project, data selection was an important step to ensure that we were working with data of high quality and suitable for analysis/modeling. I took the data from Kaggle.com. I validate a selected subset of data to ensure that it meets our goals and maintains the integrity of the overall data set. 

**Data Extraction** - In this project, data extraction was the first step to collecting raw data from different sources and preparing it for further analysis or processing. I use appropriate methods and tools to retrieve data from identified sources. This may involve running SQL queries and creating API queries. The extracted data is stored in its raw form, often in a structured format like CSV, JSON, or a database table. This allows us to maintain a record of the original data and perform data processing steps without modifying the source. 
**Example** - 
import pandas as pd
# Read the CSV file into a pandas DataFrame
file_path = 'Salary_Data_Based_country_and_race.csv'
data = pd.read_csv(file_path)

# Display basic information about the dataset
print(data.info()) 

**Data Transformation** - In this project, data transformation plays a central role in preparing raw data for analysis, modeling, and visualization.

Code like # Plot the average salary for top 10 job titles
plt.figure(figsize=(10, 6))
sns.barplot(x=top_10_jobs.index, y=top_10_jobs.values, palette="viridis")
plt.title('Top 10 Job Titles with Highest Average Salary')
plt.xlabel('Job Title')
plt.ylabel('Average Salary')
plt.xticks(rotation=90)
plt.show()
where the data is transformed into a graph and get a clear visual which is more helpful and informative. 
**Data Loading** - Data loading is a critical step in the data processing pipeline where you bring external data into your application or project for further analysis, manipulation, and utilization. This process involves accessing data from various sources and formats, such as files, databases, APIs, and more. 
**example** - 
#Load Data
df = pd.read_csv('./Salary_Data_Based_country_and_race.csv')
df.head()

# Hotels_reviews_analysis-Power-BI
Welcome to one of my projects towards Training Data Analyst/Data Engineer at the Techionista Academy in Amsterdam, The Netherlands.Below, you can find snippets of my journey.

**Overview**  
The goal of this project is to analyze a large dataset of that contains hotels in Europe, that would help the respective hotels to improve hotel's preformance and inturn increase the cutomer satisfaction.

**Data Overview**  
The holiday dataset contains more than 500K rows in 17 columns for luxury hotels across Europe. Data is saved in csv format.
The dataset is hosted in Azure Blob Storage. Thus, we import the data in Power BI using the Azure Blob gateway.
Using power BI, we need to present the data in a readable format to the business teams to imporve their hotel's performance.

**Explotary Data analysis**  
As previously mentioned our dataset contains many rows and columns. We need to know if all the columns are helpful for getting insights or if it is possible to transform data from the columns to adjust report requirements.
Change the data type in specific columns from text to whole number and so on.
Delete trailing spaces and standardize names.
Standardize column names.
Fix errors in the dataset. We use data profile tools and filters in Power Query to detect that and fix it.
Check duplicates. Removing duplicates from the data is an essential step as these may skew the data.
Check data inconsistency and work on null values. In some cases they are helpful so we do not delete them.
Transform one column into two or more columns. For instance Hotel_Adress column contains the entire address of the hotel including city and country. We split that column and we create additional features like City and Country.
The column tags describe properties about travel type, group type, or room type in one row. In order to improve readability and clarity we use tools from Power BI (split columns, replace or conditional columns) to clean up the column tags and create new features.
We use Python in Power BI for clean Positive_Review and Negative_Review. Those columns contain reviews from hotel customers. Which is also useful information but before building a bag of words it is better to clean text from buzzwords and non-characters.
After cleaning data it is time to create reports in Power BI.

**Data Visualization**    
Using Power BI we can reports/dashboards that can be easily read by a layman.
In this case we created a report for the business teams to quickly understand the what's working and what things they need to improve on.


**Home page**  
This gives a clear overview of the diffrent parts of the report.
![image](https://github.com/user-attachments/assets/1c5ed90a-a855-4b95-98fe-2f886c5d151f)


**Overview**  
Using this page the users can get an of the data. They can filter the data based on the year and city to understand the performance in paticular city at given year.
![image](https://github.com/user-attachments/assets/a4f8a858-1065-4d93-a2c0-48accfd807af)


**Hotels Details**  
This page gives the details of top and bottom 10 hotels based on the review scores as wells as the reviews given for a hotel
![image](https://github.com/user-attachments/assets/eb42f72c-e8b6-4e89-b115-1cd954fd33ad)


**Travelers Details**  
Here you see the profile of the travelers(reviewers)
![image](https://github.com/user-attachments/assets/3411d701-3e84-46bf-a21b-316d63e1e4c4)


**Review Details**  
Here the business users can can understand about the most common positive and negative reviews given.
![image](https://github.com/user-attachments/assets/501518dc-f295-4b81-b890-78a4b8546776)


**Report**  
Here is the link to the report https://app.powerbi.com/links/HzROjvTNt2?ctid=23828106-3f61-47d7-9e8d-c03d006b795f&pbi_source=linkShare








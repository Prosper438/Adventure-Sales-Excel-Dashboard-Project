# **Adventure Sales Analysis Project**
### Project Overview
The data analysis prompt to give a clearer understanding on the customers and products performance of the dataset.
After a well structured analysis,we were able to dig out useful and beneficial informations that will improves sales,revenue and other goals of the company.
# TABLE OF CONTENT
- [Data Source and Data Overview](#data-source-Data-overview)
- [Tools Used](#tools-used)
- [Data ETL](#data-etl)
- [Added Column](#added-column)
- [Analysis of Data](#analysis-of-data)
- [INSIGHTS FROM ANALYSIS](#insights-from-analysis)
- [TAKEOFF FROM ANALYSIS](#takeoff-from-analysis)
## Data Source and Data Overview
The data was extracted from the popular Kaggle website. [Click here to preview](https://www.bing.com/ck/a?!&&p=43272f9d6465a85f18d8a9a52c0d60ee0f30168977ae88cbceaeac02d35d97b8JmltdHM9MTczMzAxMTIwMA&ptn=3&ver=2&hsh=4&fclid=22962217-8ea9-6cfb-0918-36338fee6d32&psq=kaggle&u=a1aHR0cHM6Ly93d3cua2FnZ2xlLmNvbS8&ntb=1)
<br>The Dataset consist of Six sheets namely 
1. Fact Internet Sales
2. Dim Sales Territory
3. Dim Product
4. Dim Geography
5. Dim Date
6. Dim Customers

# Tools Used   
* Microsoft Excel - For data cleaning and data modelling with the aid of Power Query and Power pivot respectively. DAX also played a vital role in custom column creation.

 # Data ETL
 Microsoft Power Query came very much handy in the extraction,loading and transformation of this dataset.
 1. Removal and Addition of old and new columns respectively: Firstly,old columns which are irrelevant was removed from each sheets of the workbook,the new columns weren added to make the analysis more feasible. Columns like Total Revenue( Order quantity * Unit Price), Cost of goods sold(Order quantity * cost), Profit( Total revenue - Cost of goods sold),other added columns include Age( which was derived with the aid of the DAX language)
 2. Modification of data types: The datatypes of some columns were changed inorder for new custom columns to be derived from them. This action was possible with the aid of Power Query
 3. Data Modelling: Prior to the results from power query, power pivot helped in creating relationship between all six sheet in the workbook inorder to have a data model for pivot tables.
![Screenshot (104)](https://github.com/user-attachments/assets/094db99a-f719-470a-90cc-e9b93f35d719)
![Screenshot (105)](https://github.com/user-attachments/assets/a8662202-7837-4508-bf19-96465460ceb2)


# ADDED COLUMNS 
- Total Revenue( Order quantity * Unit Price)
- Cost of goods sold(Order quantity * cost)
- Profit( Total revenue - Cost of goods sold)
- Age group = Age <= 30 ( Junior citizen), Age >= 45 (Senior citizen) and 31-44 (Labor force)
- Quartile = Division of the year into four equal parts (Quartile 1,2,3&4)
- Price range = Expensive (Unit price > $150) and less expensive ( Unit price is <= $150)

# ANALYSIS OF DATA
The analysis of this data was broken down into two parts, the Products and customer analysis.<br>
For both analysis, we looked into intriguing questions like
- Top 5 Profitable Product
- Profitbility of Product by colour
- Profit by Pricing type
- Profit by Age group
- Profit by gender
- Top 5 profitable customers
- Profit by weekdays
- Quartely profit analysis
- Monthly profit trends
- Yearly performance Metrics (Above average)
- Profit by weektype
- KPIs comparision of current year to previous year

# INSIGHTS FROM ANALYSIS
From the analysis of the dataset, I was able to draw some key insights as follows
* Weekdays has the highest purchasing power and it also generate the highest profit across all years.
* The year 2007 and 2006 generated the highest profit and revenue respectively.
* Senior citizens tends to have the highest purchasing power.
* By country, USA and Australia generates the highest profit.
* Black deems to be the colour generating the highest profit,only Canada was an exemption where Red generates the most profit.
* The expensive products on the other hand appears to generate the highest profit also.

# TAKEOFF FROM ANALYSIS
* The use of Excel macro features for automation of clearing all slicers and switching between both dashboards.\
* Extraction of Icon,stickers and GIFs from a the flaticon site. [Click here..](flaticon.com)
* I also employed the use of Adobe colour wheel to assist in selecting matching colours and also for importing colours with their HEX codes. [Link..](https://color.adobe.com/)

Feel free to go through this project and drop your suggestions,correction and opinions on this.<br>
I included the raw datasets for those interested. Thanks  :blue_heart: :blue_heart: :blue_heart:

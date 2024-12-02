# **Adventure Sales Analysis Project**
### Project Overview
The data analysis prompt to give a clearer understanding on the customers and products performance of the dataset.
After a well structured analysis,we were able to dig out useful and beneficial informations that will improves sales,revenue and other goals of the company.

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

# ADDED COLUMNS 


# ANALYSIS OF DATA
The analysis of this data was broken down into two parts, the Products and customer analysis.<br>
For the product analysis,

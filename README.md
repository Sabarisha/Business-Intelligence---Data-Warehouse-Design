# Business Intelligence-Data Warehouse Design

***Note - This is a sample project and does not contain any real business data

## Company Background
Project data belongs to a manufacturing company. Company sells its products to make money. Products are grouped into product categories and types. Comapny is selling its products via different channel categories such as Direct and Indirect. Direct channels include Boutiques, Online and Outlet transactions. Indirect channels include Branded Franchise and Department Stores. Each product has Price (retail price when sold to customers), a WholeSalePrice (discounted prie when selling to Resellers) and Cost (money spent by company in manufacturing the product)

## Business Scenario 
I need to analyze the sales history of the company and make recommendations to improve company profits from sales by building an end to end BI system that can help the business answer any questions and make valuable decisons

## Tools Used
* MS Visio - To create the star schema and complete dimensional modeling 
* SSDT - To develop packages for staging loads from source database into datawarehouse, staging dimensional loads and fact loads into data warehouse
* SSMS - To run individual queries and analyze the database
* Tableau - To create dashboard for the company to get useful information relevant to the questions that needs to be answered

## Files Included
* SourceSystem ERD.vsd - ERD of source data from original database using which dimension data is modeled
* Dimensional Data Model_Star Schema.vsdx - has 3 fact tables and 6 dimension tables
* Dimensional Data Model ERD details.docx - More information about table naming conventions and granularity of each dimension and fact table 
* Staging Loads.docx - an overview of how to stage loads in SSIS from source to target database
* Dimension table creation and loading - Sample code explaining how to create and load data into a dimension table
* Fact table creation and loading - Sample code explaining how to create and load data into a fact table
* Additional Views for Sales and Product Analysis - Views to perform additional sales and product analysis for the data given. Views generally inssulate the datawarehouse data from BI tools like Tableau/ Power BI so that original data is not affected 
* Final Presentation- Product Analytics.twbx- Customized Tableau dashboard used for answering business questions by performing sales and product analysis

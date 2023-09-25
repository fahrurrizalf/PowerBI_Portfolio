# Power BI Portfolio

![PowerBI Portfolio](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/84ed965c-edfc-4dc5-bab7-137cc564728e)

<h2 align="center"><a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=25&pause=1000&color=000000&center=true&vCenter=true&width=700&lines=Welcome+to+Fahrurrizal's+Power BI+Portfolio+%F0%9F%91%8B%F0%9F%8F%BB" alt="Typing SVG" /></a></h2>

This repository houses a collection of data visualization projects created using Microsoft Power BI. Explore interactive dashboards, insightful reports, and data-driven stories that demonstrate my expertise in transforming raw data into actionable insights


## Table of Content :
- [**Project 1 : Enhancing Foodstory's Business Insights**](#project-1--enhancing-foodstorys-business-insights)

- [**Project 2 : Car Analysis Dashboard**](#project-2--car-analysis-dashboard)

- [**Project 3 : Supermarket Sales Analysis**](#project-3--supermarket-sales-analysis)


## Project 1 : Enhancing Foodstory's Business Insights

### Introduction
In the fast-paced and dynamic food industry of Indonesia, Foodstory stands out as a prominent cloud kitchen platform with a wide-reaching presence, boasting multiple branches across the archipelago, particularly in Jakarta. In the quest for growth and excellence, data-driven decision-making has become indispensable. To this end, we embark on a significant data analysis project aimed at providing Foodstory with comprehensive insights, precise analytics, and actionable recommendations to foster the enhancement of their business.

### Project Structure

    ├── LICENSE
    ├── README.md          <- README
    ├── data               <- Datasets used for this project (Excel files).
    │   ├── Branch Sales.xlsx
    │   ├── Customers.xlsx
    │   ├── Customer Sales.xlsx
    │   ├── Days Category.xlsx
    │   └── Detailed Sales.xlsx
    ├── Data_cleaning      <- Folder for data cleansing scripts and queries.
    │   └── Power Query
    │       ├── Cleansing Step 1      <- Step 1: Use First Row as Header
    │       ├── Cleansing Step 2      <- Step 2: Remove Blank Rows
    │       ├── Cleansing Step 3      <- Step 3: Format "Full Name" column in "Customers" table to Capitalize Each Word
    │       ├── Cleansing Step 4      <- Step 4: Format "Branch Name" column in "Branch Sales" table to Capitalize Each Word
    │       ├── Cleansing Step 5      <- Step 5: Outlier Detection for "Grand Total" column in "Branch Sales" table
    │       ├── Cleansing Step 6      <- Step 6: Create "Average" and "Standard Deviation" columns in "Branch Sales" table
    │       ├── Cleansing Step 7      <- Step 7: Calculate Z-score for outlier detection in "Branch Sales" table
    │       └── Cleansing Final       <- Final data cleansing and transformation steps.
    │
    ├── visualizations      <- Folder for Power BI visualizations and reports.
    │   ├── Dashboards
    │      ├── figma             <- Figma files for dashboard design.
    ├── Power_bi_project   <- Power BI project files.
    │   └── Foodstory_Business_Insights.pbix  <- Power BI project file.
    
--------

### Dataset
Data was normalised that is, the information was categorically seperated into differnt sheets or tables resulting into 5 tables:

- Branch Sales
- Customers
- Customer Sales
- Days Category
- Detailed Sales

Data was then locally extracted from Excel Workbook into Power BI for transformation, analysis and visualization.

### Data Processing 
Data cleaning was performed per table. The table appeared to be clean. The quality of each column is 100% with no error or nulls.

Below is a preview of the tabels:


Customers              |           Sales Branch
:--------------------------:|:------------------------:
![Customers Query](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/afb6ee1c-1709-42e2-a107-246954d60e74)          |         ![Branch Sales Query](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/c9e0518e-ea10-409a-9606-b2f181cc4c96)

Sales Menu              |        Sales Customer
:---------------------------:|:----------------------
![Detailed Sales Query](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/03643bb7-bae3-4f68-beba-00bc42d4d489)         |     ![Customer Sales Query](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/71756d35-e2ba-4e45-a85f-36c661f7c100)

### Data Visualization

Below is a preview of the visuals:

Customers              |           Sales Branch
:--------------------------:|:------------------------:
![Foodstory Customer](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/03e4d1e5-d3ab-4114-a220-01ef02bda55f)          |         ![Foodstory Sales Branch](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/6b224c80-4bcc-445f-9135-4cfc8d4f8821)

Sales Menu              |        Customer Sales
:---------------------------:|:----------------------
![Foodstory Sales Menu](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/43c0985d-2b08-4e9c-add7-d441554e3c34)         |     ![Foodstory Sales Customer](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/9b3edaed-cba0-4a9d-a0fe-6b31700b3799)

## Project 2 : Car Analysis Dashboard
### Introduction
In the dynamic landscape of the automotive industry, companies constantly seek innovative approaches to stay competitive and adapt to evolving market demands. At the heart of this pursuit lies the exploration of new business models, such as the resale of used cars, which offers a promising avenue for growth and profitability. This project revolves around a mid-sized company that is embarking on a journey to explore and develop a business model for the resale of pre-owned vehicles. Leveraging the power of data analysis and visualization, we have employed Power BI to create a comprehensive solution that empowers the company in its endeavor to understand, strategize, and optimize the used car business. In this report, we will delve into the intricacies of our Power BI project, shedding light on how this powerful tool has been harnessed to drive informed decision-making, enhance operational efficiency, and unlock new opportunities in the realm of used car sales.

### Project Structure

    ├── LICENSE
    ├── README.md          <- README .
    ├── query              <- Code for DB creation and queries.
    │   │
    │   └── Car_sales_tables_db.sql       <- DB creation.
    │   └── analysis.sql                     <- Final queries.
    │   └── query_data                       <- Final query data.
    ├── reports            <- Folder containing the final project reports/results.
    │   │
    │   └── Car_Analysis_Report.docx        <- Final analysis report document.
    │   └── Car_Analysis_Report.pdf         <- Final query report in PDF format for data verification.
    │   
    ├── src                <- Source for this project.
    │
    ├── data           <- Datasets used and collected for this project.
    │   │
    │   └── final_cars_dataset.csv      <- Final car dataset.
    │
    ├── scripts        <- Additional scripts if needed.
    │
    ├── power_query    <- Power Query code for data cleaning.
    │   │
    │   └── data_cleaning    <- Power Query script for data cleaning.
    │
    ├── power_bi       <- Power BI project files.
       │
       └── Car_Analysis.pbix  <- Power BI project file.

--------
### Data Processing

Below is a preview of the tables:


Data Table             |           Power Query
:--------------------------:|:------------------------:
![Data Table](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/a530b08d-2933-427f-8f5e-137a094f058c)           |     ![Data Cleaning](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/25e00f31-bae6-4f54-9caf-2e42d583bee9)
    

### Data Visualization

Below is a preview of the visuals:

Price Analysis             |           Correlation Analysis
:--------------------------:|:------------------------:
![Car Price Analysis](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/783a1d2f-1285-4018-a3db-8f5fe2a0a3db)          |         ![Correlation Car Analysis](https://github.com/fahrurrizalf/PowerBI_Portfolio/assets/109564854/89046130-d502-489f-96b8-94fe28d16234)

## Project 3 : Supermarket Sales Analysis

### Introduction

### Project Structure

    ├── LICENSE
    ├── README.md          <- README .
    ├── query              <- Code of the DB creation and queries.
    │   │
    │   └── retail_sales_tables_db.sql       <- DB creation.
    │   └── analysis.sql                     <- Final queries.
    │   └── query_data                       <- Final queries data.
    ├── reports            <- Folder containing the final reports/results of this project.
    │   │
    │   └── query_report.docx        <- Final analysis report Document.
    │   └── query_report.pdf         <- Final query report in PDF for verifying data.
    │   
    ├── src                <- Source for this project.
        │
        ├── data           <- Datasets used and collected for this project.

--------

### Dataset

### Data Processing

Below is a preview of the tables:

Customers Table             |           Location Table
:--------------------------:|:------------------------:
![](customerQ.PNG)          |         ![](locationQ.PNG)

Products Table              |        Salesrep Table
:---------------------------:|:----------------------
![](productQ.PNG)             |     ![](salesrepQ.PNG)

### Data Visualization

Below is a preview of the tables:

Customers Table             |           Location Table
:--------------------------:|:------------------------:
![](customerQ.PNG)          |         ![](locationQ.PNG)






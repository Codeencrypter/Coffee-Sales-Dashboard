# Coffee-Sales-Dashboard - Data Analysis Project

![CoffeeSalesDashboard-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/64a84c43-b31b-4ddb-8ee4-2e0649ea56c9)


## Introduction:

As a Data Geek and an aspiring Data Analyst, I have analyzed the dataset related to an Coffee business and presented my findings.

### Questions to Analyze:
To understand the Coffee Business better, I asked the following:
1. Country Wise Coffee Sales of the business?
2. Top 5 Customers of the Business?
3. Total Coffee Sales Over Time?

## Excel Skills Used
The following Excel skills were utilized for analysis:

- 🧮 Excel Formulas & Functions
- 📊 Pivot Tables
- 📈 Pivot Charts
- 💪 Data Validation

## Coffee Sales Dataset
The dataset used for this project contains data extracted from Kaggle.com. The dataset is available on Kaggle.com, providing a foundation for me to analyze the data using Excel.
It includes detailed information on:
- 👨‍💼 Customers
- 💰 Products
- 📍 Orders
- 🛠️ Sales

## My Final Dashboard File is in [Download Excel File](relative/path/to/https://github.com/Codeencrypter/Coffee-Sales-Dashboard/blob/main/Coffee%20Sales%20Dashboard%20.xlsx

  
 ## Data Cleaning 

## 🔍 Skills: Excel Formulas & Functions

- I used XLOOKUP Function for the purpose of extraction of the data from secondary worksheet to main worksheet of the workbook.
- =XLOOKUP(Orders!C2,Customers!$A$1:$A$1001,Customers!$B$1:$B$1001,,0)
- =IF(XLOOKUP(C2,Customers!$A$1:$A$1001,Customers!$C$1:$C$1001,,0)=0,"",XLOOKUP(C2,Customers!$A$1:$A$1001,Customers!$C$1:$C$1001,,0))
📊 Dynamic Array Formula: Utilizes XLOOKUP function with nested IF() statement to analyze an array.
🎯 Tailored Insights: Provides specific information for Customer Name, Customer Email and Country.
🔢 Formula Purpose: This formula populates the columns below, returning the values based on Customer Data and specified Country.

![SS XLOOKUP (COFFEE)](https://github.com/user-attachments/assets/e470a77e-bb88-4fbb-94ab-59fa7ccb7ee3)

- Used INDEX Match function to directly populate the data from one work sheet to another.
- =INDEX(Products!$A$1:$G$49,MATCH(Orders!$D2,Products!$A$1:$A$49,0),MATCH(Orders!I$1,Products!$A$1:$G$1,0))
- =INDEX(Products!$A$1:$G$49,MATCH(Orders!$D2,Products!$A$1:$A$49,0),MATCH(Orders!J$1,Products!$A$1:$G$1,0))

 🔢 Determine Sales by multiplication of Unit Price ✖️ Quantity Sold =L2*E2
 🔢 Used IF Function in order to change the abbrevations for the Coffee Types and Roast Type =IF(I2="Rob","Robusta",IF(I2="Exc","Excelsa",IF(I2="Lib","Liberica",IF(I2="Ara","Arabica",""))))
 =IF(J2="M","Medium",IF(J2="L","Lite",IF(J2="D","Dark","")))
 




## 1️⃣ Country Wise Coffee Sales of the Business?

## 🧮 Skills: PivotTables & PivotCharts

 📈Pivot Table
🔢 I created a PivotTable using the data table which I created in Orders Worksheet.
📊 I moved the Years & Months to the rows area, sum of sales into the values area & Coffee Type name in columns area.
   

## 📊 Analysis

### 💡 Insights
- 💰 Arabica & Liberica are the top grossers  along with huge demand in months of January,Feburary and September followed by Excelsa & Robusta.

  ![SS Country Wise (Coffee)](https://github.com/user-attachments/assets/66f57f36-43e5-4219-9aaf-a90f4d4f3300)





### 🤔 So What
- This trend shows demand for Arabica & Liberica Coffee types are constantly good and the business should focus on boosting the marketing & increase supply more in the months of January.
- The business could do better in aspect of Robusta by understanding the demand better.

---

### 2️⃣ Top 5 Customers of the Business?

🧮 Skills: PivotTables  
📈 **Pivot Table**
- 🔢 I created a PivotTable using the Data Model I created with Power Pivot.
- 📊 I moved the Customer Name to the rows area and the Sum of Sales into the values area.

### 📊 Analysis

💡 **Insights**
- 💼 The Bar Chart depicts the top 4 buyers are from United States and 1 from United Kingdom
- 🔎 Demand for Coffee is the highest in United States & United Kingdom.

 ![SS Top Customers (Coffee)](https://github.com/user-attachments/assets/b3900dc9-d1ae-4691-8090-92601b7ab522)







### 🤔 So What
- These insights holds great importance for business and provides a strong base for decision making and understanding that the markets of United States is very fruitful in terms of growth along with sales & profit.
---

### 3️⃣ Total Coffee Sales Over Time?

🧮 Skills: PivotTables  
📈 **Pivot Table**
- 🔢 I created a PivotTable using the Data Model I created with Power Pivot.
- 📊 I moved the (States) column to the rows area and the (Sum of Sales) column into the values area.

### 📊 Analysis

💡 **Insights**
- 💼 Analysis depicts California, New York & Texas are the Top 3 States by Sales.
- 💰 The Sales are lowest in West Virginia, Maine & South Dakota, which are only contributing only 3.8K out of total sales of 2297.20K.

  ![SS COFFEE SALES OVER TIME](https://github.com/user-attachments/assets/683e889d-5469-470c-834f-b0d8da93c643)




### 🤔 So What
- The Company should focus more on increasing the supply of products and do more heavy marketing in the states of California, New York & Texas in order to drive more sales and profit.
- Understanding the market better in the states with the lowest sales will help the company be more competitive in the market and optimize the sales.

---


## Conclusion
As a data enthusiast and an aspiring data analyst, I embarked on this Excel-based project to uncover valuable insights about an E-Commerce Business. Using a dataset I’ve undertaken this project from Kaggle and you can find the dataset for this project on [Kaggle's website](https://www.kaggle.com).
, I analyzed the Sales, Profit, Key Performance Indicators & Year on Year Growth of the Business. By leveraging Excel features like Power Query, PivotTables, and Pivot Charts, I discovered key correlations between Sales and Profits, particularly in States and Categories in which the business sells the products.

I hope this project serves as a practical guide for data professionals and provides an overview of the Excel skills used in analyzing this dataset.

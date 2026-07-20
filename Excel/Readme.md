# 📊 Excel Projects

---

# Project 1: Retail Sales Analysis
## Overview

Using Microsoft Excel, I analysed a retail sales dataset to explore sales trends, customer purchasing behaviour, and product performance. I cleaned and organised the data, created PivotTables and PivotCharts, and built an interactive dashboard to present key insights that support data-driven decision-making.

## Data Preparation

I imported the retail sales dataset into Microsoft Excel and converted it into an Excel Table using Ctrl + T. This organised the data into a structured format, making it easier to work with in the following stages of the analysis.

<p align="center">
  <img src="https://github.com/user-attachments/assets/26ef6890-bcb0-4dea-953b-2121c29e5646" alt="Imported dataset" width="1000">
</p>
I used the Sort & Filter feature in Microsoft Excel to sort the Age column from Largest to Smallest. Sorting the data made it easier to view customer records by age and prepare the dataset for further analysis.
<img width="2300" height="645" alt="image" src="https://github.com/user-attachments/assets/52fde880-dca6-49e7-be7b-474b9a7237cd" />
I used the SUM function to calculate the total sales by adding all the sales values in the Sales column. This provided the overall sales total, which was then used as part of the summary calculations.
I used the IFS function to categorise customers into three age groups: Senior, Adult, and Young Adult, based on their age. This made it easier to analyse and compare sales patterns across different customer age groups. 
Customer Category:
=IFS(E2>=50,"Senior",E2>=30,"Adult",E2<30,"Young Adult")
  <p align="center">
<img width="2687" height="595" alt="image" src="https://github.com/user-attachments/assets/eec70824-1eee-4ae7-b66e-ef425c042427" />
</p>
I created a Commission Amount column by multiplying each customer's Total Sales by the fixed 1.5% commission rate stored in cell P8. I used an absolute cell reference ($P$8) so that the commission rate remained fixed when copying the formula down the column.
   <p align="center">
<img width="3727" height="912" alt="image" src="https://github.com/user-attachments/assets/870ecc73-563d-49a5-9bb6-8ff8de18b37f" />
</p>
The summary box displays the commission rate, total commission, and average commission. These calculations provide a quick overview of commission costs and help compare the average commission earned per sale for the selected group of customers.

### PivotTable: Total Sales by Product Category and Gender

I created a PivotTable to summarise Total Sales by Product Category and Gender. This allowed me to compare sales performance across different product categories while identifying spending patterns between male and female customers. The PivotTable provides a clear summary of the data and highlights which categories generated the highest revenue. . I paired this with a clustered column chart to make the comparison clearer. Showing the data as percentages makes it easier to compare group behaviour fairly.
 <p align="center">
<img width="2220" height="785" alt="image" src="https://github.com/user-attachments/assets/3e76108a-4ac8-4396-84a5-b6ffec8b91e5" />
</p>


---

# Project 2: Student Performance Analysis

## Overview

This project involved analysing student performance by calculating average marks, identifying the highest scores, and highlighting key results using Excel formulas and data analysis tools.
Used analyse student performance using formulas, sorting, filtering and conditional formatting.
The dataset contains student names and marks in English, Mathematics and Science. It was used to calculate averages, identify the highest scores and compare student performance.


## What I Did

- Converted the data into an Excel Table.
- Calculated each student's average mark using the AVERAGE function.
- Identified each student's highest mark using the MAX function.
- Applied sorting and filtering to identify the best-performing students.
- Used conditional formatting to highlight the highest and lowest average scores.
- Reviewed the results to compare student performance.

## Evidence

### Original Dataset
  <p align="center">
<img width="1505" height="525" alt="student_dataset" src="https://github.com/user-attachments/assets/187dd777-3f62-48be-977a-efd8ba1b27dc" />

### Student Performance After Sorting and Filtering
<img width="1234" height="557" alt="Sorted and filtered Data set" src="https://github.com/user-attachments/assets/9f894c9b-b132-434c-b542-6a3456e22752" />


### Average Marks

<img width="1609" height="608" alt="Average Marks Calculated" src="https://github.com/user-attachments/assets/668a3e6c-0080-44ff-81ed-5b73c95ab51e" />


### Highest Score Using MAX Function

<img width="1606" height="460" alt="highest_score" src="https://github.com/user-attachments/assets/45a6e361-e3a6-4cc4-ad9e-5add457d1fed" />


### Best Students by Average


<img width="1500" height="479" alt="best_average" src="https://github.com/user-attachments/assets/2e592de0-f4da-46f8-bd60-f3b0e6ac2c42" />

### Best Student by Highest Score
<img width="1540" height="516" alt="best_highest_score" src="https://github.com/user-attachments/assets/574bace6-930c-42a8-b59e-b8bd34834d03" />


### Conditional Formatting

<img width="1487" height="707" alt="conditional_formatting" src="https://github.com/user-attachments/assets/366804e6-79b8-4161-9556-e88afcfc4d8c" />


## Key Findings

- Average marks provided a clear comparison of overall student performance.
- The MAX function identified each student's strongest subject.
- Sorting and filtering quickly identified the highest-performing students.
- Conditional formatting made key results easier to identify.

## Skills Demonstrated

- MAX Function
-  Microsoft Excel
- AVERAGE Function
- Data organisation
- Data cleaning and preparation
- Excel Tables
- PivotTables
- Formulas and Functions
- SWITCH Function
- Data analysis
- Sorting and filtering
- Conditional formatting


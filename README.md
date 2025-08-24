# -CafeNova-Sales-Performance-by-Progress
## Project Overview
When I first opened the CafeNova dataset, it looked overwhelming. There were blanks, duplicates, inconsistent formats, and scattered entries that made it difficult to understand what the data was really saying. My task was to transform this raw data into a clean, structured dataset and then build a dashboard that would help a restaurant manager quickly spot trends in sales performance.

## Dataset
The dataset used in this project can be found here:  
[Download Dataset](https://github.com/progressuchenwa/-CafeNova-Sales-Performance-by-Progress/blob/main/CafeNova%20dataset%20.xlsx)
 

## Cleaning and Organizing the Data
Before touching anything, I made a copy of the raw dataset to ensure the original stayed intact. The copy was renamed **Clean Data**, and this became the foundation for all further work.  
I began by scrolling through the dataset to get a sense of its structure and challenges. From there, I tackled the issues step by step:  
- Removed blanks and duplicate rows that made the dataset inconsistent.  
- Standardized date formats using **Text to Columns** and ensured all dates followed a single, consistent structure.  
- Fixed inconsistent payment methods (e.g., different spellings and blanks in the same column).  
- Cleaned inconsistent product entries, where spacing and typing errors caused duplicates.  

By the end of this process, the dataset was structured and much easier to work with.

## Creating Useful Metrics
The cleaned data by itself was just numbers. To extract meaningful insights, I built new calculated metrics to answer key business questions:  

- **Total Revenue** = sum of all sales after discounts.  
- **Number of Orders** = total count of transactions.  
- **Number of Unique Customers** = 100 distinct customers identified through the DISTINCT function in PivotTable.  
- **Best-Selling Item** = Grilled Chicken, followed closely by Pasta Alfredo.  
- **Best-Selling Day** = Friday, consistently generating the highest sales.  

These KPIs provided the backbone of the performance analysis.

## Building the Dashboard
Using Excel PivotTables and charts, I built an interactive dashboard where managers could instantly filter sales by category, date, or payment method using slicers.  

The dashboard highlighted:  
- Overall revenue trends over time.  
- Top-selling items (Grilled Chicken and Pasta Alfredo).  
- Customer activity patterns, showing **100 unique customers**.  
- Sales distribution by payment method.  
- Key KPIs (Revenue, Orders, Customers, Best Day, Best Item) displayed with professional icons for clarity.  

 **Dashboard Preview**  
![CafeNova Sales Performance Dashboard](https://github.com/progressuchenwa/-CafeNova-Sales-Performance-by-Progress/blob/main/Cafenova%20Sales%20Performance%20Dashboard.png)


## What I Found
A few key patterns emerged from the analysis:  
- Friday consistently emerged as the strongest sales day.  
- Grilled Chicken was the top-performing product, with Pasta Alfredo coming second.  
- The café served **100 unique customers**, indicating a stable base with potential for growth.  
- Cash and card payments dominated, though inconsistencies highlighted the need for stricter recording practices.  

## Why This Project Matters
This project was about more than just cleaning data,  it was about telling the story behind CafeNova’s sales.  

Starting with a messy sheet, I was able to:  
- Clean and standardize it,  
- Create business-ready metrics, and  
- Build a dashboard that reveals real insights into customer behavior and sales performance.  

It demonstrates how Excel skills can transform raw restaurant transactions into a powerful decision-making tool.

## 👩About Me
I’m **Ukamaka Uchenwa (Progress)**, a data analyst who specializes in Excel dashboards, data cleaning, and storytelling with data. I enjoy taking messy, real-world datasets and turning them into insights that help businesses grow.

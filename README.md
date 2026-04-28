Bike Sales Data Analysis — Excel Project

<img width="1361" height="767" alt="excel screenshot" src="https://github.com/user-attachments/assets/733fc31d-9f55-43cb-8124-578fefacad97" />

Project Overview

This project is an end-to-end Excel data analysis exploring what demographic and lifestyle factors influence whether a customer purchases a bike. The analysis covers data cleaning, pivot table creation, and an interactive dashboard all built in Microsoft Excel.

This is part of my data analytics learning journey, where I focus on asking real business questions and using data to answer them.

Business Questions Answered

Question
  1  Which age group is most likely to purchase a bike?
  
  2  How does commute distance affect bike purchase decisions? 
  
  3  Does income level influence whether a customer buys a bike? 
  
  4  Is there a gender difference in bike purchasing behaviour? 
  
  5  Which region has the highest bike sales? 

Dataset Description

The dataset contains 1,000+ customer records with the following columns:

  `ID` Unique customer identifier
  
  `Marital Status` Married or Single
  
  `Gender` Male or Female
  
  `Income` Annual income in USD
  
  `Children` Number of children
  
  `Education` Highest education level
  
  `Occupation` Job category
  
  `Home Owner` Whether the customer owns a home
  
  `Cars` Number of cars owned
  
  `Commute Distance` Daily commute distance range
  
  `Region` Geographic region (Europe, Pacific, North America)
  
  `Age` Customer age
  
  `Age Bracket` Adolescent / Middle Age / Old
  
  `Purchased Bike` Target variable — Yes or No
  
Tools & Features Used:
Microsoft Excel
  - Data Cleaning & Formatting
  - Pivot Tables
  - Charts & Visualizations
  - Interactive Dashboard

Project Structure:
bike-sales-excel-analysis/

  Excel_Project_Dataset.xlsx   # Main workbook containing:
  
    bike_buyers              # Raw & cleaned dataset
    
    pivot table              # Analysis pivot tables
    
    Dashboard                # Interactive sales dashboard
    
README.md                    # Project documentation

Key Findings
Age Group
- Middle Age customers were significantly more likely to purchase a bike 12 out of 16 middle-aged customers bought one
- Older customers were less likely to buy only 1 out of 4 made a purchase

Commute Distance
- Customers with a 0–1 mile commute had the highest bike purchase rate 11 out of 14 bought a bike
- As commute distance increased, purchase likelihood dropped significantly
- Customers commuting more than 10 miles purchased no bikes at all

Income
- The average income of bike buyers was $33,846
- Non-buyers had a higher average income of $41,429
- This suggests bikes are more popular among middle-income customers

Gender
- Female non-buyers had a higher average income ($66,667) than female buyers ($35,000)
- Male buyers had a slightly higher average income ($33,333) than male non-buyers ($22,500)

Region
- Data spans Europe, Pacific, and North America
- Regional breakdown is visualised in the dashboard

Dashboard Preview

<img width="1361" height="767" alt="excel screenshot" src="https://github.com/user-attachments/assets/f43cd633-0ab0-4811-9ada-2554a4c5a239" />

What I Learned

- How to clean and prepare a real-world dataset in Excel
- How to build Pivot Tables to summarise and compare data
- How to create an interactive dashboard with charts and slicers
- How to translate raw numbers into business insights
- The importance of asking the right questions before touching the data

 How to Use This Project

1. Download or clone this repository
2. Open `Excel_Project_Dataset.xlsx` in Microsoft Excel
3. Navigate between the three sheets:
   - bike_buyers — explore the raw data
   - pivot table — review the analysis
   - Dashboard — interact with the visual summary

About the Author

Nakanjako Tendo Jackline
Data Analytics Learner | Excel | SQL | Storytelling with Data

(https://www.linkedin.com/in/nakanjako-tendo-jackline-3979452b0/)
(https://medium.com/@ntendo4343)

Let's Connect

If you are also learning data analytics or have feedback on this project, feel free to connect with me on LinkedIn or leave a comment on my Medium blog. I am always happy to learn and grow together!

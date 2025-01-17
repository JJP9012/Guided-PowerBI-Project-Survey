#  Guided PowerBI Project - Survey 

Welcome to the **Guided PowerBI Project - Survey**! This project explores survey taker's job title, job happiness, job salary and more in a survey taken by Alex Freiburg, "Alex The Analyst" on Youtube. 📊

![Survey Visual](https://github.com/user-attachments/assets/75a53ca8-d145-47f4-85c7-be137c3a268f)

---

## 🚀 Project Overview

In this project, I utilised a unclean dataset of survey answers. These included, "Q1 - Which Title Best Fits your Current Role?", "Q2 - Did you switch careers into Data?", "Q3 - Current Yearly Salary (in USD)" and many more. The goal was to use as much data as I could to uncover insights about the survey takers, however this was difficult due to the unclean nature of the dataset. The analysis was performed using **Power Query Editor** for data cleaning and calculations, and **Power BI** for interactive data visualizations.

---

## 🔧 Tools and Techniques

- **Power Query Editor**:  
  - 🧹 *Data Cleaning*: Imported data from Excel and tranformed it in Power Query Editor. Removed null columns and simplified other columns by using 'Split Column by Delimeter', this allowed me to remove all the variations of 'Other' survey answers, in order to make 'Other' one answer type.

![Split Column by Delimeter](https://github.com/user-attachments/assets/e4ad44dc-034a-4ae6-8680-74ed9da92fd2)


  - 📊 *Calculations*: In order to use the "Q3 - Current Yearly Salary (in USD)", I took an average of the salary range in the original dataset. This meant duplicating the column and using 'Find and Replace' (removing '-' and 'k') to create a column with the minimum value and a column with the maximum value. Now a 'Custom Column' was made to find the average of the previous two columns, using the formula shown in the image below.

![Custom Column](https://github.com/user-attachments/assets/f441dc81-7834-4e45-b79e-7fea1032b78a)


- **Power BI**:
  - 🖼️ *Data Visualization*: Based on the clean data available to me I created interactive charts to visualize trends, performance, and global comparisons. This included the use of a treemap, a stacked column and bar chart, a donut chart, two gauges and two cards. 

![My Dashboard](https://github.com/user-attachments/assets/84dfca9b-5e0a-4263-94f1-68398ea45ca4)


---

## 💡 Key Insights

1. **Favourite Programming Language**: Python was the most popular language, selected by 255 of the 630 voters.
2. **Average Salary By Job Title**: Data Scientists had the highest average salary of '93.78k (USD)' across the survey takers.
3. **Global Votes**: 261 of the voters were from the 'United States'.
4. **Happiness Rating**: Survey takers rated their happiness with their salary at 4.27/10 and their happiness with work/life balance at 5.74/10.

---

## 🌟 How to Explore the Project

Clone this repository:  
   ```bash
   git clone https://github.com/JJP9012/Guided-PowerBI-Project-Survey.git

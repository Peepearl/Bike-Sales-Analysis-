## BIKE SALES ANALYSIS

### PROJECT OVERVIEW
This Project aims to analyze bike sales data to identify trends and patterns that can inform marketing and sales strategies for Bike sales. The dataset used include information on bike model, Sales dates,Prices,Customers age,Product- category,Sub-category,States,Country,Profit,Unit-cost,Product,Customer gender and Revenue.The analysis is conducted using Python programming language and various data analysis libraries.

### OBJECTIVE
The objective of this analysis is to uncover insights into customer preferences,purchasing behavior, sales purchase to optimize inventory management and marketting campaigns,specifically aim to identify the most popular bike model(Product), peaks sales period, target customer demographics,Profit,sales by category,sales according to age group,revenue by state and country, and potential area for improvement in Europe to derive actionable insights that can inform business strategies.
### Key Questions:
- What are the sales trends over the years and months?
- Which age group purchases the most bikes?
- What are the top-selling product categories and sub-categories?
- How does revenue vary across different countries and states?
### Data Understanding
Data Collection: The dataset, Bike Sales in Europe.csv, contains information on bike sales across Europe, including variables such as Date, Profit, Year, Month, Age Group, Product Category, Sub-Category, Revenue, Country, and State.

### Exploratory Data Analysis (EDA):

- Head and Tail: Initial inspection of the dataset using head() and tail() to view the first and last 5 rows.


 ![bike 1](https://github.com/user-attachments/assets/a2f3e60d-9d0d-45ab-a636-a34bffb14c3d)

 ![tail](https://github.com/user-attachments/assets/2cfa35db-43c4-4447-b580-ae4d426ef606)

- Descriptive Statistics: Summary of data using describe() to understand the distribution of numeric values.

 ![describe](https://github.com/user-attachments/assets/375bfdb3-f067-4e3a-a4dc-e476ad150bc0)


- Duplicates: Checked for duplicate records using duplicated().

 ![duplicate1](https://github.com/user-attachments/assets/42491909-4282-41c3-8ec1-9d8656cde1b6)

- Missing Values: Assessed missing data using isnull().sum().

 ![sum](https://github.com/user-attachments/assets/ae669792-a50a-432e-88e3-a6c54f2fb23c)

- Datetime Conversion: Converted the 'Date' column to datetime format.

 ![date](https://github.com/user-attachments/assets/bb484229-dc85-46d3-9f7f-eac0f3f88451)

### Data Preparation
Data Cleaning:
Duplicates and null values were identified, but specific actions taken (like removal or imputation) were not detailed. You might want to describe any additional steps taken if applicable.
Feature Engineering:
- Converted 'Date' to datetime format and extracted relevant features like 'Year' and 'Month' for trend analysis.
### Modeling
Data Visualization:
- Yearly Sales: Analyzed sales trends over the years using line plots.

 ![sale according](https://github.com/user-attachments/assets/b007db75-f26e-403d-a0d9-47663690d1b9)

- Monthly Sales: Visualized sales trends over months using line plots.

![month1](https://github.com/user-attachments/assets/881fefee-ea59-4ca2-a63e-f8ffd3007231)

![month2](https://github.com/user-attachments/assets/fcd8d1b8-a452-42de-88b4-3e3a2573c5c7)

- Age Group Sales: Represented sales distribution across different age groups using a pie chart.

  ![age1](https://github.com/user-attachments/assets/11082a6c-589e-421c-9164-8a9619c71adb)

  ![age2](https://github.com/user-attachments/assets/616a9e59-20b1-4c9e-9342-b37c18cfee99)


- Product Category Sales: Used bar plots to analyze sales by product categories and sub-categories.
  ![prod1](https://github.com/user-attachments/assets/6f4a943d-c809-45f2-8f54-f3b93138b49d)

  ![prod2](https://github.com/user-attachments/assets/9ac66989-b217-48fa-8b75-7aeecccc5a1d)


- Revenue Analysis: Grouped revenue by country and state to identify high-performing regions.

 ![rev](https://github.com/user-attachments/assets/2b7713f5-2960-4b33-a4cd-b4e7f8d162ee)

### Evaluation
Key Findings:
- Sales trends varied across different years and months.
- Specific age groups had higher purchase rates.
- Certain product categories and sub-categories showed higher sales volumes.
- Revenue differences across countries and states highlighted potential markets to focus on.
- Business Impact: The insights gained from this analysis can help in targeting marketing efforts, optimizing inventory, and focusing on high-revenue regions.





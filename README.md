# Bike-Sales-Analysis 
## Project Overview
The objective of this project was to create an Excel dashboard to analyze and visualize bike sales data. The dashboard provides insights into various demographic and behavioral aspects of the customers, enhancing decision-making processes.

### Data Sources
Bike Sale Data: The primary dataset used for this analysis is the " Bike sale Dataset "  file ,containing detailed infromation about each sale made by the company.

### Tools
- Excel - data preparation , data cleaning , data analysis
- pivot chart
- dashboard - creating a report.
  
### Data Preparation ###
 1. *Raw Data Cleansing:*
   - *Duplicate Values:* All duplicate entries in the raw data were identified and removed to ensure data integrity.
   - *Empty Spaces:* All blank spaces in the data were cleared to avoid any disruptions in data processing and analysis.
 2. *Data Standardization:*
   - *Marital Status:* The marital status was originally denoted by 'M' and 'S'. These were converted to 'Married' and 'Single', respectively, to avoid any confusion.
   - *Gender:* Gender was initially represented as 'F' for female and 'M' for male. These abbreviations were expanded to 'Female' and 'Male' for clarity.

 3. *Age Group Categorization:*
   - The age data ranged from 20 to 100 years, making it challenging to visualize effectively. Using nested IF functions, the ages were categorized into three groups: 'Adolescent', 'Middle Age', and 'Older'.
 4. *Salary Data Formatting:*
   - Salary figures included large numbers of decimal places. These were standardized by formatting the salaries as currency and truncating the decimal points to improve readability.

 ### Data Analysis and Visualization ###
 1. *Pivot Tables:*
   - *Average Income per Purchase:* This table analyzed the average income of customers segmented by gender (Female and Male).
   - *Customer Commute:* This visualization compared the distances between customers' homes and workplaces.
   - *Age Group Purchase Analysis:* This table determined which age group (Adolescent, Middle Age, Older) purchased the most bicycles.

### Dashboard Creation ###
The final dashboard integrated various visualization techniques to present a comprehensive view of the data:
- *Marital Status and Purchases:* The dashboard shows the distribution of bike purchases between Single and Married customers.
- *Geographical Purchase Distribution:* Analysis of bike sales across different regions (Europe, North America, Pacific).
- *Educational Background of Customers:* The dashboard includes the educational levels of customers, such as Bachelors, Graduate Degrees, High School, and Partial College.
- *Gender-based Income Analysis:* Visual representation of average income per purchase for Female and Male customers.
- *Commute Analysis:* Visualization of the relationship between commute distance and bike purchases.
- *Age Group Analysis:* Insight into which age groups (Adolescent, Middle Age, Older) are the most active in purchasing bikes.

### Conclusion ###
This Bike Sales Dashboard project demonstrates a robust application of data analysis skills, from data cleaning and standardization to advanced categorization and visualization. The final dashboard offers valuable insights into customer demographics and purchasing behaviors, aiding in strategic decision-making.

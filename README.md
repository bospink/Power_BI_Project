# Power BI Project

## Data Professional Survey Breakdown

### The main goal of this project is to showcase proficiency in utilizing Power BI to analyze and visualize dataset. 
----
This project comprises three components:

**1. Import Data from Excel**

**2. Transform Data**

In Power Query Editor I did some Data Cleaning:

   - Delete unnecessary columns
     
   - Standardize columns to have only few options by using Split Column > by Delimiter, Split at: Left-most delimiter.
     I did that for the columns: Which Title Best Fits your Current Role?  Favorite Programming Language, Which Country do you live in? and What Industry do you work in? after which I removed redundant columns.
     
   - Make a copy of the column Current Yearly Salary (in USD) and then Split Column > By Digit to Non-Digit, to only have numeric values. I got two new columns and changed their data type to Whole number. Then I went to Add Column > Custom Column and named it Average Salary. In Custom Column Formula I did the sum of these two columns divided by 2 to get the average. I created this Average Salery column because it will be more usable for the data visualizatuon later (data type: Decimal number).
     

**3. Build visualization**

- Adding Dashboard Title
  
- Putting cards for Count of Survey Takers and Average Age of Survey Takers
  
- Making charts:

  - stacked bar chart for Average Salary by Job Title
  - stacked column chart for Favourite Programming Language
  - treemap for Country of Survey Takers
  - gauge for Happiness with salary and Happy with Work/Life Balance
  - donut chart for Difficulty to Break Into Data
 
 I customized a visualization title, legend, background, label, and added a theme Dashboard View > Themes so that the colors and style were uniform for all elements.

 My Dashboard in Power BI is ready now!

![Survey_Breakdown_PowerBI](https://github.com/bospink/Power_BI_Project/assets/126882792/6a6e0983-f1de-4a72-ae02-58a89cb540bd)

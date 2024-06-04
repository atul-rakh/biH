
# COVID-19 Data Analysis Visualization

## Introduction
This README file provides a step-by-step guide on how to perform data analysis and create visualizations for COVID-19 data using Power BI. The dataset used contains information about various countries, including total cases, new cases, deaths, and other relevant details.
## Step 1: Data Preparation
1.	Connect the Excel dataset to Power BI using the data source option.
2.	The dataset contains COVID-19 information for different countries, including total cases, new cases, deaths, and more. We will be analyzing this data in our project.
3.	Select the appropriate sheet and click "Transform Data" to clean and prepare the data using the Power Query Editor.
4.	In the Power Query Editor:
    *  Select the necessary columns and remove unnecessary ones.
    *	Choose columns such as Location (renamed to Country), Continents, Date, Total Cases, New Cases, Total Deaths, Median Ages, and any other relevant columns.
    *	Remove null values by applying filters.
    *	Sort the data in descending order of date, select the most recent date, and then sort it back in ascending order.
    *	Rename columns for clarity, such as renaming Location to Country.
    *	Finally, click "Close & Apply" to import the cleaned data into Power BI Desktop.
## Step 2: Creating a Clustered Column Chart
1.	In Power BI Desktop, access the data section to view the COVID-19 dataset.
2.	Create a Clustered Column Chart to visualize the top 10 countries by total COVID-19 cases:
    *	Select the Clustered Column Chart.
    *	Place Country on the Axis and Total Cases in the Values field.
3.	Apply a filter to display only the top 10 countries.
4.	Format the chart for better clarity:
    *	Set the chart title to "Top 10 Countries by Total Cases."
    *	Align the title to the center.
    *	Bolden the title, axis labels, and data labels.
    *	Format the X and Y-axis values.
    *	Make data labels visible for more detailed information.
    *	Customize the chart color and adjust its size.
## Step 3: Creating a Pie Chart
1.	Create a Pie Chart to visualize the distribution of total deaths by continent.
2.	In the Pie Chart:
    *	Place Continents in the Legend and Total Deaths in the Values field.
3.	Format the chart for clarity and aesthetics:
    *	Align the title to the center.
    *	Bolden the title, axis labels, and data labels.
    *	Format the X and Y-axis values.
    *	Make data labels visible for more detailed information.
    *	Customize the chart color and adjust its size.
## Step 4: Creating an Area Chart
1.	Create an Area Chart to visualize the top 10 continents by total COVID-19 cases.
2.	In the Area Chart:
    *	Place Continents on the Axis and Total Cases in the Values field.
3.	Apply a filter to display only the top 10 continents.
4.	Format the chart for better clarity:
    *	Set the chart title to "Top 10 Continents by Total Cases."
    *	Align the title to the center.
    *	Bolden the title, axis labels, and data labels.
    *	Format the X and Y-axis values.
    *	Make data labels visible for more detailed information.
    *	Customize the chart color and adjust its size.
## Step 5: Creating a Line Chart
1.	Create a Line Chart to analyze the relationship between median age and COVID-19 cases by continent and country.
2.	In the Line Chart:
    *	Place Continents on the Axis, Median Ages in the Values field, and Country in the Legend.
3.	Apply filters as needed to analyze specific countries or top N countries.
4.	Format the chart for clarity:
    *	Set the chart title to "Median Age by Continent and Country."
    *	Align the title to the center.
    *	Bolden the title, axis labels, and data labels.
    *	Format the X and Y-axis values.
    *	Make series labels visible for more detailed information.
    *	Customize the chart color and adjust its size.
## Step 6: Adding Card Visualizations
Include card visualizations to display total cases, new cases, and total deaths for a concise summary.
## Step 7: Combining Visualizations
Arrange all visualizations on a single sheet to create a comprehensive COVID-19 data analysis report.
## Conclusion
By following these steps, you can effectively analyze and visualize COVID-19 data using Power BI, providing valuable insights into the pandemic's impact on different countries and continents.


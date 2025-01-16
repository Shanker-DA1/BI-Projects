# Mobile Sales Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiMzBjMTAwNDMtNWJiYi00MTllLWEwOTYtNzg3NGYwNmNmNmJhIiwidCI6IjZiNjNlMjhhLWE4ZjktNDdiNS1hYTQwLTk3ZTIzMTIxNTE2NCIsImMiOjF9

## Problem Statement

This dashboard helps to gain actionable insights into mobile sales performance, this dashboard analyzes key metrics such as top-selling brands, year-over-year sales comparisons, and key performance indicators like Month-to-Date (MTD) and Year-to-Date (YTD) sales. This analysis aims to identify sales trends, pinpoint areas for improvement, and inform data-driven decisions to optimize mobile sales strategies.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors except for locale change which was fixed.
- Step 5 : In Power Query Editor, created calculated columns and new measures (Total Sales, Total Qty, Avg Price etc) 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the date contains mobiles sales data from 2021 onwards, a filter for years was created. 
- Step 8 : Visual filters (Slicers) were added for 12 months.
- Step 9 : Line chart was created for month basis sales along with an option to choose year, model and brand.
- Step 10 : MTD and Same Period Last Year pages were created along with an option to go back to the main dashboard.


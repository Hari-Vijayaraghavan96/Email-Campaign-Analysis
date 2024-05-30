# Email Campaign Analysis

## Project Overview
Developed a Power BI project focused on analyzing email campaign data for a company facing challenges in understanding their email marketing performance to extract valuable insights. The project aims to construct a comprehensive dashboard that provides actionable metrics and trends.

## Problem Statement
The company is struggling to comprehend the performance of their email campaigns, leading to suboptimal engagement and ineffective strategies. The goal is to analyze key metrics such as CTR, Bounce Rate, Open Rate, and Delivery Rate to identify areas for improvement and optimize future campaigns.

## Tools Used
<li><b>Excel:</b> For initial data cleaning and preparation.</li>
<li><b>Power BI:</b> For data visualization and exploratory data analysis (EDA).</li>

## Data Cleaning
<li>Replaced missing values in key columns to ensure accurate analysis, using appropriate fill methods or default values.</li>
<li>Converted date columns to a consistent format (e.g., YYYY-MM-DD) for time-based analysis, ensuring uniformity across all date fields.</li>
<li>Ensured consistent labeling for email statuses (e.g., 'Sent', 'Rejected') to maintain data integrity and accurate categorization.</li>
<li>Ensured that numeric columns (e.g., click counts, bounce counts) were set to appropriate numeric data types.</li>
<li>Converted date columns to date data types for time-series analysis.</li>
<li>To accurately analyze the email campaign performance, new columns and DAX measures were created.</li>

## Data Sources
Excel File: Contains email campaign data with columns including campaign code, email status, sent date, open date, click date, bounce status, etc.

## Visualization Used
<li><b>Total Rate Analysis:</b> Card used to visualize CTR, Bounce Rate, Open Rate, and Delivery Rate.</li>
<li><b>Monthly Email Sent:</b> Column chart to display the volume of emails sent on a monthly basis.</li>
<li><b>Campaign KPI:</b> Table to evaluate key performance indicators for each campaign.</li>
<li><b>Email Send Status:</b> Pie chart to display sent and rejected count.</li>
<li><b>Member Campaign Analysis:</b> Cards to identify members who engaged with the emails (opened or clicked).</li>
<li><b>Slicers:</b> Filters to dynamically analyze data by campaign code, year, month, and day of email sent.</li>

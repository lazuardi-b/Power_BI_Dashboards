# Data Jobs Dashboard Analysis (Version 1 - Exploratory)

## Project Overview

This dashboard provides an overview of the data job market using Power BI, focusing on job distribution, salary trends, and hiring activity. It is designed to help users explore key aspects of the market through an interactive and multi-page report.

The dashboard highlights key metrics such as total job count, median salaries, and job trends over time. It also enables users to compare salary ranges across roles, analyze hiring patterns, and explore detailed information through drill-through functionality.

This version focuses on broad exploration, using multiple report pages and a variety of visualizations to examine the dataset from different perspectives.

## Dashboard Overview

The dashboard is organized into two main sections: a primary overview page and a drill-through page for deeper analysis.

### Main Dashboard

![Main Dashboard](/images/Project1_Page1.png)

The main page provides a high-level view of the data job market, combining key metrics with trend and distribution analysis.

- **Key Metrics:** Displays total job count, salary rating, and median salary (yearly and hourly) to provide a quick snapshot of the market.
- **Trend Analysis:** A time-series visualization shows how job postings change over time.
- **Salary Comparison:** A scatter plot compares yearly and hourly salaries across different roles.
- **Role Distribution:** A bar chart highlights the most common job titles based on job volume.
- **Detailed Table:** A supporting table presents job-level details, including counts, salary information, and trends.
- **Interactive Filters:** Users can filter by job title and navigate deeper into the data using drill-through functionality.

### Drill-Through Page

![Drill Through Dashboard](/images/Project1_Page2.png)

The drill-through page provides a more detailed breakdown of selected roles, allowing users to explore additional insights.

- **Salary Overview:** Displays median yearly and hourly salaries for the selected role.
- **Job Attributes:** Visualizes key job characteristics such as remote work availability, degree requirements, and benefits.
- **Geographic Distribution:** A map shows where job opportunities are concentrated globally.
- **Hiring Platforms:** Highlights the most common platforms where jobs are posted.
- **Employment Type Breakdown:** A treemap shows the distribution of job types, such as full-time and contract roles.

## Key Features

- **Multi-page dashboard structure:** Designed a two-page report to separate high-level insights from detailed analysis using drill-through functionality.

- **Interactive exploration:** Enabled dynamic filtering and navigation through slicers and drill-through, allowing users to explore the data based on specific job roles.

- **Comprehensive market overview:** Combined job volume, salary metrics, and hiring trends into a single dashboard for a broad understanding of the data job market.

- **Diverse visualizations:** Utilized a mix of charts, tables, and maps to present different aspects of the data, supporting both comparison and exploration.

- **Geographic and role-based analysis:** Included global job distribution and role-specific breakdowns to provide multiple perspectives on the market.

## Approach

The dashboard was developed by first preparing the dataset using Power Query, where data was cleaned, formatted, and structured for analysis. This included handling missing values, standardizing data types, and creating derived fields where needed.

Once the data was prepared, a basic data model was established to support relationships between tables and enable accurate aggregation. Measures were then created to calculate key metrics such as job counts and median salaries.

The final step focused on designing the dashboard layout and interactions. Visualizations were selected to represent different aspects of the data, while slicers and drill-through functionality were implemented to support user-driven exploration.

## Tools Used

- **Power BI:** Dashboard development and interactive visualizations  
- **Power Query:** Data cleaning and transformation  
- **DAX:** Basic calculations to support insights and measures  

## Limitations & Improvements

- **Dataset scope:** Analysis is limited to the available dataset of job postings and may not represent all regions or industries.  
- **Salary data availability:** Some postings do not include salary information, which may affect median calculations.  
- **Exploratory focus:** V1 emphasizes exploration rather than focused insights, which can make interpretation less immediate.  
- **Potential improvements:** Future iterations could include more advanced DAX calculations, enhanced visualization techniques, and a more refined single-page layout to improve clarity and usability, as demonstrated in *Version 2*.

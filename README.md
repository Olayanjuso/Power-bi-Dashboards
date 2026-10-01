# Data Jobs Market Analysis Dashboard | Power BI

An interactive **Power BI dashboard analyzing approximately 479K data-related job postings**, with a focus on job demand, salary levels, job-posting trends, geographic distribution, job platforms, work arrangements, education requirements, benefits, and employment types.

This project was developed as part of my hands-on training and portfolio development in **Business Intelligence and Data Analytics**.

The objective was to build an interactive report that allows users to move from a high-level view of the data job market into a more detailed analysis of individual job titles.

---

## Dashboard Preview

### Main Data Jobs Dashboard

![Dashboard Page1](/Images/Jobdashboard_pg1.PNG)

The main dashboard provides an overview of the data jobs market, including job volume, salary levels, job trends, salary comparisons, and job-posting distribution by role.

---

### Job Title Drill-Through Dashboard

![Dashboard Page1](/Images/Jobdashboard_pg2.PNG)

The drill-through page provides a more detailed analysis of a selected job title. The example above shows the analysis for **Data Analyst**.

---

# Project Objective

The purpose of this project was to use Power BI to transform job-posting data into an interactive business intelligence report that could answer practical questions about the data jobs market.

The dashboard was designed to answer questions such as:

- Which data-related roles have the highest number of job postings?
- What are the median yearly and hourly salaries for different job titles?
- How did job postings change throughout 2024?
- How do yearly and hourly salaries compare across different roles?
- Where are data jobs located globally?
- Which job platforms contain the most postings?
- What types of employment arrangements are available?
- How frequently do job postings mention work-from-home opportunities?
- How frequently are degree requirements mentioned?
- How often is health insurance mentioned in job postings?
- How do these characteristics change when a specific job title is selected?

---

# Main Dashboard

The main dashboard provides a high-level view of the data jobs market.

![Dashboard Page1](/Images/Jobdashboard_pg1.PNG)

## Key Performance Indicators

The dashboard includes KPI cards showing:

- **Total Job Count:** approximately 479K
- **Median Yearly Salary:** approximately $113K
- **Median Hourly Salary:** approximately $47.62
- **Salary Rating**

These indicators provide a quick summary of the overall dataset before users explore the individual visualizations.

---

## Job Posting Trend

The **"What is the trend of job in 2024?"** visualization tracks job-posting activity across 2024.

This allows users to observe changes in job-posting volume throughout the year and identify periods where posting activity increased or decreased.

---

## Median Yearly vs Hourly Salary

The **"Median Yearly vs Hourly Salary"** scatter plot compares yearly and hourly compensation across different data-related job titles.

The visualization makes it possible to compare roles such as:

- Data Analyst
- Data Engineer
- Data Scientist
- Senior Data Analyst
- Senior Data Engineer
- Senior Data Scientist
- Cloud Engineer
- Machine Learning Engineer
- Business Analyst

A trend line is included to show the general relationship between the two salary measures.

---

## Job Demand by Role

The **"What is the Highest Posted Jobs in Data?"** bar chart compares the number of job postings across different data-related roles.

This provides a straightforward view of the relative job-posting volume for each role represented in the dataset.

---

## Job Posting Matrix

The **Job Posting Matrix** combines several important measures into a single interactive view:

- Job Title
- Job Count
- Median Yearly Salary
- Median Hourly Salary
- Job Posting Trend

This provides a more detailed way to compare individual job categories while still keeping the information within the dashboard.

---

# Job Title Drill-Through

A key feature of the report is the **Job Title Drill-Through** page.

Instead of stopping at the overall market view, users can select a specific job title and move into a detailed analysis of that role.

For example, selecting **Data Analyst** provides additional information about that particular job category.

![Dashboard Page1](/Images/Jobdashboard_pg2.PNG)

---

## Salary Analysis

The drill-through page includes yearly and hourly salary analysis.

For the selected job title, the dashboard displays:

- Minimum yearly salary
- Median yearly salary
- Maximum yearly salary
- Median hourly salary

This allows users to explore the salary distribution associated with an individual job category.

---

## Work From Home Analysis

The **WFH%** visual examines the proportion of postings associated with work-from-home opportunities for the selected job title.

This adds a work-arrangement dimension to the salary and job-volume analysis.

---

##  Degree Requirement Analysis

The **No Degree Mention%** visual examines whether job postings mention a degree requirement.

This provides an additional perspective on the educational requirements appearing within job postings for the selected role.

---

##  Health Insurance

The **Health Insurance %** visual examines the proportion of job postings that mention health insurance.

This provides another dimension for analyzing job-posting characteristics beyond salary and job volume.

---

#  Global Job Distribution

The **"Where are the Jobs Globally?"** treemap visualizes the geographic distribution of job postings.

It allows users to explore the countries represented in the dataset and identify locations with larger concentrations of data-related job postings.

---

#  Job Platforms

The **"What Platform has Most Jobs?"** visualization compares job postings across different platforms represented in the dataset.

Platforms shown include examples such as:

- LinkedIn
- Indeed
- ZipRecruiter
- Jobot
- Google Jobs
- Glassdoor
- BeBee
- Jobs2Careers

This provides an overview of where the job postings in the dataset were sourced.

---

#  Employment / Schedule Types

The **"What are the types of data Jobs?"** visualization examines the different schedule or employment types represented in the dataset.

Categories include:

- Full-time
- Contractor
- Internship
- Part-time
- Temporary
- Volunteer

This helps provide context around the nature of the opportunities represented in the dataset.

---

# Interactivity

A major objective of the report was to create an **interactive analytical experience rather than a static collection of charts**.

The dashboard incorporates:

- Job title selection
- Interactive filtering
- Cross-filtering between visuals
- Drill-through analysis
- Dynamic job-title analysis
- Interactive matrix reporting
- KPI cards
- Trend analysis
- Comparative salary analysis

Users can select a job title and explore how the associated salary, location, work arrangement, education requirement, benefits, and employment characteristics change.

---

# Tools & Power BI Features

### Primary Tool

**Microsoft Power BI Desktop**

### Power BI techniques demonstrated

- Data visualization
- Interactive dashboard design
- KPI reporting
- Measures and calculations
- Slicers and filters
- Drill-through functionality
- Matrix reporting
- Trend analysis
- Salary analysis
- Scatter plot analysis
- Geographic visualization
- Treemap visualization
- Gauge visualizations
- Donut charts
- Bar charts
- Line charts
- Conditional/interactive reporting
- Dashboard layout and formatting

---

#  Analytical Areas Covered

| Analytical Area | What the Dashboard Examines |
|---|---|
| Job Demand | Job-posting volume by role |
| Salary | Median yearly and hourly salary |
| Salary Comparison | Yearly vs hourly salary across roles |
| Job Trends | Job-posting activity throughout 2024 |
| Geography | Global distribution of job postings |
| Job Platforms | Distribution of postings by platform |
| Work Arrangement | Work-from-home opportunities |
| Education | Degree requirements mentioned in postings |
| Benefits | Health insurance mentions |
| Employment Type | Full-time, contract, internship, part-time, etc. |
| Job-Level Analysis | Detailed analysis through drill-through |

---

#  Business Intelligence Perspective

Rather than viewing the dataset as a collection of individual job records, this dashboard organizes the information into several business questions and analytical dimensions.

The report allows a user to move through three levels of analysis:

**1. Market Overview**  
Understand the overall volume and salary characteristics of the data jobs market.

**2. Role Comparison**  
Compare job titles based on demand and compensation.

**3. Job Title Deep Dive**  
Use drill-through functionality to investigate the characteristics of a specific role.

This structure was intended to make the dashboard useful for both **high-level exploration and detailed analysis**.
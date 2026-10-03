# Data Jobs Dashboard 2.0 | Power BI

## Data Preparation, Data Modeling & DAX

An enhanced version of my **Data Jobs Market Analysis Dashboard**, developed to go deeper into the data preparation, modeling, and analytical capabilities of Microsoft Power BI.

While the first version focused primarily on dashboard design, visualization, and interactive reporting, **Data Jobs Dashboard 2.0** was developed to strengthen and demonstrate additional Power BI concepts, including **Power Query transformations, data appending, relational data modeling, explicit DAX measures, filter context, and the use of measures in report visuals.**

The dashboard analyzes approximately **479K data-related job postings**, focusing on job demand, required skills, salary levels, and other characteristics of the data job market.

---

# Dashboard Preview

![ DATE JOB 2.0 DASHBOARD](/Images/Jobdashboard_Project_2.0.PNG)

**Data Jobs Dashboard 2.0**

The dashboard provides an interactive overview of job volume, required skills, and salary levels while allowing users to filter the analysis by **Job Title** and **Country**.

---

# Project Objective

The objective of this project was to move beyond basic Power BI visualization and develop a stronger understanding of the complete analytical workflow:

**Raw Data → Data Preparation → Data Modeling → DAX Measures → Interactive Report → Business Insights**

The project was designed to strengthen practical skills in:

- Data preparation
- Data transformation
- Data integration
- Relational data modeling
- DAX calculations
- Filter context
- Explicit measures
- Interactive dashboard development
- Analytical storytelling

---

# What Changed from Dashboard 1.0?

This project builds upon my previous Data Jobs Dashboard and introduces deeper Power BI concepts.

### Dashboard 1.0

The first version focused primarily on:

- Dashboard design
- Visualizations
- KPI reporting
- Interactive filtering
- Drill-through analysis
- Salary analysis
- Job-market trends

### Dashboard 2.0

The second version goes deeper into the underlying Power BI development process by incorporating:

- Power Query transformations
- Append operations
- Merge operations
- Data modeling
- ERD / relationship design
- Explicit DAX measures
- Filter and evaluation context
- Measure-based calculations
- Dynamic filtering
- More deliberate separation between data preparation, modeling, and reporting

This allowed me to focus not only on **what the dashboard looks like**, but also on **how the data and calculations behind the dashboard are structured.**

---

# Power Query & Data Preparation

Power Query was used as part of the data preparation process before the data was loaded into the Power BI model.

The project provided practical experience with:

- Data transformation
- Data cleaning
- Combining data sources/tables
- **Append Queries**
- Preparing tables for modeling
- Structuring data before creating report calculations

### Append

The **Append** operation was used to combine compatible datasets/tables vertically where the underlying structures allowed the records to be consolidated.

This provided practical experience in understanding when multiple datasets should be combined by adding rows.

---

# Data Modeling & ERD

A relational data model was developed to structure the dataset before creating the final report.

The modeling process included consideration of:

- Tables
- Relationships
- Primary/unique fields
- Related fields
- Filtering behavior
- Table roles within the model
- How the model would support DAX calculations and report visuals

An **Entity Relationship Diagram (ERD)** was used as part of the modeling process to understand how the tables relate to one another.

This helped reinforce the principle that a good Power BI report depends not only on the visuals but also on the structure of the underlying data model.

---

# DAX & Explicit Measures

One of the major learning objectives of Dashboard 2.0 was to move away from relying primarily on automatically generated **implicit measures** and instead create **explicit DAX measures**.

Measures were created intentionally for the calculations required by the report.

Examples of analytical measures used in the project include calculations relating to:

- Job Count
- Job Percentage
- Average Skills Required per Job Posting
- Median Yearly Salary
- Median Hourly Salary

Using explicit measures provides greater control over how calculations are defined, reused, and evaluated throughout the report.

---

# Filter Context & DAX Evaluation

A major concept explored in this project was **filter context**.

The dashboard contains interactive slicers for:

- **Job Title**
- **Country**

When a user changes these selections, the report calculations and visualizations respond to the active filter context.

This provided practical experience in understanding how DAX measures are evaluated within the context created by:

- Slicers
- Visuals
- Rows and columns
- Filters
- User selections

The goal was to understand not only how to write a DAX measure, but also **why the same measure can produce different results depending on the current filter context.**

---

# Dashboard Overview

The final dashboard provides a concise view of the data jobs market.

## KPI Cards

The dashboard displays four major indicators:

### Job Count

Approximately **479K** job postings are represented in the dataset.

### Average Skills Required per Job Post

The dashboard calculates an average of approximately **4.8 skills per job posting**.

### Median Yearly Salary

The overall median yearly salary displayed is approximately **$113K**.

### Median Hourly Salary

The overall median hourly salary displayed is approximately **$48**.

These KPIs provide a quick summary before users explore the detailed visualizations.

---

# Interactive Slicers

The dashboard contains interactive slicers for:

- **Select Job Title**
- **Select Country**

These slicers allow users to narrow the analysis and examine the job market from different perspectives.

A **Clear Slicers** control is also provided to allow users to quickly return to the overall dataset view.

---

# Top Skills in Data

The **"What are the Top Skills in Data?"** visualization analyzes the skills associated with the job postings.

The dashboard highlights skills including:

- Python
- SQL
- AWS
- Azure
- Tableau
- Spark
- R
- Excel
- Power BI
- Java

The visualization displays the percentage of job postings associated with each skill.

This provides a practical view of the technical skills appearing most frequently within the dataset.

---

# Top-Paying Data Jobs

The **"What are the top paying Jobs in Data?"** visualization compares median yearly salary across different data-related roles.

Roles represented include:

- Senior Data Scientist
- Machine Learning Engineer
- Senior Data Engineer
- Software Engineer
- Data Engineer
- Data Scientist
- Cloud Engineer
- Senior Data Analyst
- Business Analyst
- Data Analyst

This visualization allows users to compare compensation levels across different roles represented in the dataset.

---

# Interactive Analytical Experience

The dashboard was designed so that users can interact with the report rather than simply read static charts.

Users can:

1. Select a job title.
2. Select a country.
3. Observe how the dashboard responds to the selections.
4. Examine the corresponding job count.
5. Analyze the average skills associated with the filtered data.
6. Explore salary measures.
7. Compare the skills and job roles represented within the selected context.
8. Use **Clear Slicers** to return to the overall view.

---

# Power BI Concepts Demonstrated

This project demonstrates practical application of the following Power BI concepts:

### Power Query

- Data transformation
- Data preparation
- Append Queries
- Merge Queries
- Data integration

### Data Modeling

- Relational data modeling
- Table relationships
- ERD concepts
- Model structure
- Filter propagation

### DAX

- Explicit measures
- Aggregations
- Percentage calculations
- Average calculations
- Median calculations
- Measure reuse
- Filter context

### Reporting

- KPI cards
- Bar charts
- Slicers
- Interactive filtering
- Dashboard layout
- Data storytelling

---

# 📚 Key Skills Practiced

Through this project, I strengthened my practical understanding of:

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Data Modeling**
- **ERD / Relationships**
- **Data Transformation**
- **Data Integration**
- **Explicit Measures**
- **Filter Context**
- **Interactive Reporting**
- **Data Visualization**
- **Business Intelligence**
- **Analytical Storytelling**


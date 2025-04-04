# Data Professionals Survey Breakdown

## Table of Contents

- Project Overview#project-overview
- Dataset Used#dataset-used
- Data Source#data-source
- Tools#tools
- Data Cleaning/Preparation#data-cleaningpreparation
- Explorative Data Analysis
- Data Analytics
- Data Visualization
- Results of Findings
- Recomendations
- Limitations
- References
  
### Project Overview
---

This project analyzes a dataset collected from a real-life survey of data professionals. The goal is to uncover trends in salaries, tools, happiness with salaries and work and provide data driven recommendations.

### Dataset Used
---

Power BI - Project dataset: The dataset used for this analysis is the ‘Survey Dataset.xlsx’ file containing detailed information of the survey that was carried out by a data analyst.
- [Dataset](https://github.com/RuthOgholi/Power-BI-Project/blob/main/Survey%20Dataset.xlsx)

### Data Source
---
The '‘Survey Dataset.xlsx’ was provided by the Data Analyst that carried out the survey.

### Data Cleaning/Preparation
---
In the initial data preparation phase, I performed the following task:
- Imported and loaded data to Power Query Editor in Power BI, and inspected it.
To ensure accurate and easy analysis I did the following:
- Removed null values in unwanted columns,
- Cleaned ‘Role’ and ‘Programming Language’ columns to simplify the options,
- Created a duplicate of ‘Current Yearly Salary’ column, and split the figures of the ranges to make two columns,
- Extracted the non-digit characters from the duplicated columns,
- Created an ‘Average Salary’ column by adding the two duplicated columns and dividing  the answer by two i.e ‘([Income Copy 1 + Income Copy 2])/2’,
- Removed the duplicated columns since I did not need them anymore and reordered the ‘Average Salary’ column bringing it beside the ‘Current Yearly Salary’ column,
- Extracted unnecessary texts from ‘Industry Worked in’ and ‘Country Live in’ columns.

### Exploratory Data Analysis
---
EDA involved exploring the survey data to answer the following key questions:
- What is the average age of each participant?
- What is the average salary of the participants? 
- What is the favorite programming language of the participants?
- Do Data Professionals earn the same amount in all the countries?
- How happy are the participants with their work-life balance?
- How happy are they with their salary?
- How difficult or easy was it for them to break into data roles?

### Data Analytics
To answer the questions above I did the following:
- Loaded the transformed dataset into Power BI,
- Inserted a card to show the distinct count of the participants using the ‘Unique ID’ column,
- Inserted a card to show average age of participants using the ‘Current Age’ column,
- Used a stacked bar chart to show job titles and average salary,
- Inserted a clustered column chart to show the favorite programming language of the participants,
- Inserted a treemap to show the average salary earned by the participants in each country,
- Inserted a gauge to rate the happiness of the participants with their work/life balance,
- Inserted another gauge to rate the happiness of the participants with their salaries,
- Inserted a donut chart to determine how difficult or easy it was for the participants to break into data roles.
[Power BI Interactive Dashbord](




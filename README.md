# Data Professionals Survey

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Used](#dataset-used)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analytics](#data-analytics)
- [Data Visualization](#data-visualization)
- [Results of Findings](#results-of-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)
  
### Project Overview
---
This project analyzes a dataset collected from a real-life survey of data professionals. The goal is to uncover trends in salaries, tools, happiness with salaries and work and provide data driven recommendations.

### Dataset Used
---
Power BI - Project dataset: The dataset used for this analysis is the ‘Survey Dataset.xlsx’ file containing detailed information of the survey that was carried out by a Data Analyst.
- [Dataset](https://github.com/RuthOgholi/Power-BI-Project/blob/main/Survey%20Dataset.xlsx)

### Data Source
---
The '‘Survey Dataset.xlsx’ was provided by the Data Analyst that carried out the survey.

### Tools
---
Power BI: Data cleaning, manipulation, analysis and visualization.

### Data Cleaning/Preparation
---
In the initial data preparation phase, I performed the following task:
- Imported and loaded the dataset to Power Query Editor in Power BI, and inspected it.
To ensure accurate and easy analysis I did the following:
- Removed unwanted columns,
- Cleaned ‘Role’ and ‘Programming Language’ columns to simplify the options,
- Created a duplicate of ‘Current Yearly Salary’ column, and split the figures of the ranges to make two columns,
- Extracted the non-digit characters from the duplicated columns,
- Created an ‘Average Salary’ column by adding the two duplicated columns and dividing  the answer by two i.e ‘([Income Copy 1 + Income Copy 2])/2’,
- Removed the duplicated columns since I did not need them anymore and reordered the ‘Average Salary’ column, bringing it beside the ‘Current Yearly Salary’ column,
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
---
To answer the questions above I transformed the dataset as follows:
- Created an ‘Average Salary’ column in Power Query Editor of Power BI,
- Simplified some columns,
- Loaded the transformed dataset into Power BI for more exploration.

### Data Visualization
---
To visualize my findings I used:
- A card to show the distinct count of the participants using the ‘Unique ID’ column,
- A card to show average age of participants using the ‘Current Age’ column,
- A stacked bar chart to show job titles and average salary,
- A clustered column chart to show the favorite programming language of the participants,
- A treemap to show the average salary earned by the participants in each country,
- A gauge to rate the happiness of the participants with their work/life balance,
- Another gauge to rate the happiness of the participants with their salaries,
- A donut chart to determine how difficult or easy it was for the participants to break into data roles.
-   
- - [Power BI Interactive Dashbord](https://github.com/RuthOgholi/Power-BI-Project/blob/main/Power%20BI%20Project.pbix)

### Results of Findings
---
The analysis results are summarized as follows:
1.	The average age of the participants is 30 years.
2.	The average salary earned by the participants is: Data Scientists $93.78, Data Engineers $65.09, Data Architects $63.67, Others $63.67, Data Analysts $55.30, Database Developer $33.20, Students $26,58. Obviously, the top three highest paid Data Professionals are Data Scientists, Data Engineers and Data Architects.
3.	Python is the favorite programming language among data professionals_ 40.5%, followed by R_ 9.7%.
4.	From the analysis, it is clear that Data Professionals’ earning is dependent on the cost of living of each country, Data Professionals in countries like US and Canada earn more because the cost of living in such countries is high.
5.	The participants are moderately happy with their work/life balance.
6.	Though they are happy with their work, on the average, the participants are not happy with their salaries.
7.	A lot of the participants (42.7%) found it difficult breaking into data roles, quite a few found it neither easy nor difficult (24.8%), while some (21.3%) found it easy and a few (6%) found it very difficult.


### Recommendations
---
Based on the analysis, I recommend the following:
1.	Seeing that many Data Professionals find it difficult to break into Data, companies can provide internship programs (paid or unpaid), to help students, recent graduates, or career changers gain real-world work experience which will make it easier for them to transition into data roles.
2.	Since the several many participants are not happy with their salaries, employers can increase the salaries of these workers so as to make them happy and in turn boost their work output.

### Limitations
---
- I had to remove several columns that were irrelevant to my analysis.
- I extracted some texts from ‘Industry Worked in’ and ‘Country Live in’ columns that could make my analysis process cumbersome.
- I cleaned ‘Role’ and ‘Favorite Programming Language’ columns to simplify my analysis process.
- I created calculated column for ‘Average Salary’, to make my analysis easier.

### References
---
Chat GPT https://chatgpt.com/?ref=dotcom

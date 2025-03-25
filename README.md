# DataCampJobMarketData
Power BI based data visualization case study on job postings data

Introduction

Here, I have followed through the steps in the DataCamp course "Case Study - Analyzing Job Market Data".
The course involved performing data cleaning on a mock dataset containing job postings relating to data analytics and creating a set of visualizations.
The visualizations are intended to be used by a recruitment firm (called "Data Search" for the purpose of the course) that specializes on data analytics job roles.

Data Preparation & Data Modelling

There was only one input data involved, which contained job posting attributes such as posting ID, date posted, company name, industry, company employee base size (catgories), minimum salary, maximum salary, job title, job position level and job skills.

The dataset was imported into Power BI and some data cleansing tasks were performed using Power Query Editor. Examples of data preparation tasks done

[1] Created a custom column for average pay as the average of minimum pay and maximum pay field

[2] Duplicated the table and only considered columns ID and job skills, splitting the job skills column after cleaning it up helps burst the job skill values into multiple rows for each job ID.

[3] Power BI automatically detected a relationship between the two tables.

[4] Some other minor data cleaning tasks (for example replace inconsistent skill values , "power_bi" and "power bi" are supposed to mean the same.

[5] Some measures were also created (for example, average pay, number of job postings and % skills count to % postings count for use in a matrix visual)

Data Visualization

I followed the course instructor and the exercises to create different visualizations to analyze job postings by time, by title, job skills sought by job title, and average pay versus experience, identifying companies with large number of job postings.

A significant part of the exercise also involved cleaning up and formatting the visuals appropriately, using images provided as background and creating a "Home" tab with icons serving as bookmarks. 
This provided a consistent look and feel for the visuals and also made navigation between the home tab and the respective tabs easier.
The report pages were filtered to consider key job titles of data analyst, data scientist, data science manager, data engineer, research engineer and business analyst, data architect and machine learning engineer

Here are screenshots from the dashboard.

![image](https://github.com/user-attachments/assets/1a64461e-0190-4b7e-ba58-3b7618a6a5cc)

![image](https://github.com/user-attachments/assets/22f8be34-5b96-425f-94fe-d6c902c04280)

![image](https://github.com/user-attachments/assets/231eb8bc-eb71-4a1c-b212-ad81343fa756)

![image](https://github.com/user-attachments/assets/2de73ace-7df4-456b-a7ee-b14d5b134820)





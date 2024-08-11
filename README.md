# LinkedIn_DataAnalysis

This is a LinkedIn Data Analysis Project, which was completed using Python as the main and only tool.
To extract the data from the LinkedIn, I have used Selenium and ChromeDrivers to extract the data also know as "Web Scraping". 
After Web scraping, all the extracted data was convereted into a csv, to be taken further deeper analysis. 

I targeted 3 Business statements and navigated around the csv data using Python tools such as (Pandas, Matplotlib, counter) to find meaningful insights

## Objective 1 : Find the most sought after Programming languages for Data Analyst role
## Objective 2 : Find the basic Qualification, that is Bachelors/ Master or Both?
## Objective 3 : Finding the skillset required to be a qualified data analyst 

## Data preprocessing: 
Extraction of Data, was the first part to analyse the data, it needs to sourced to a local platform and needs to have directory path. 
With the help chrome drivers and selenium, the data was extracted for these queries (Entry level - Data Analyst roles)
The automation was followed for 23 pages, which consisted up on around 550 jobs. 
The extracted data was formatted into a CSV file with three columns (Job_title, company_title, job description)
Job title being the designated role name, company_title is the  company name and job_description is the whol description about the requirement, qualifications for the job

## Data cleaning
While skimming through the data, I was able to find the inconsistency in the data, that is the company "Turing" had been repeated multiple times with the same descriptions meaning 
there were duplicates of the Turing company, hence original data was kept and the rest were deleted and was convereted into new CSV file.

## Data collection
The Hypothesis / Business Statements such as:
 Objective 1 : Find the most sought after Programming languages for Data Analyst role
 Objective 2 : Find the basic Qualification, that is Bachelors/ Master or Both?
 Objective 3 : Finding the skillset required to be a qualified data analyst 
 all which were grouped into findings, where where for the first objective it known that R, SQL, Excel and GO where the most looked after programming languages, 
 for the second objective, the majority of the companies found Bachelor's Degree was enough.
 and the last objective, is the skills to persue as the data analyst which were (Analytical thinking, Data Analysis,  finding insights, communication and machine learnings)


 ## Data Visualization
 The findings for objective one and three were plotted in a bar graph, because are labeeling varibles (programming langugaes against the accumulated numbers), however
 the objective 2 was different, it was a pie chart present which had only three variables ( Bachelors, Masters, Both) since the variables are low and almost required by 
 all the companies it made sense to convert the findings into a pie chart.

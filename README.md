# Data-Wrangling
Data assessment and cleaning steps applied to an online job posting data set

## Project Overview
In this project, we have explored the 3 key steps in Data Wrangling:
1. Gather data
2. Assess data
3. Clean data 

The dataset has 19001 job postings that are assessed to identify the key issues with the dataset. These have then been converted from the assess step into defined problems, and under cleaning have been translated to sophisticated code to fix these problems.
Finally the dataset is tested using assert statements to make sure the operations worked.

This doesn't demonestrate all the possible data issues, but shows how to approach the most common data cleaning steps.

## Input File
# Data columns (total 24 columns):
jobpost: The original job post.
date: The date it was posted in the group.
Title: Job title.
Company: Employer name. 
AnnouncementCode: Announcement code, which is some internal code and is usually missing.
Term: Full-Time, Part-time, etc.
Eligibility: Eligibility of the candidates.
Audience: Who can apply? 
StartDate: Start date of work.
Duration: Duration of the employment.
Location: Employment location.
JobDescription: Job Description.
JobRequirment: Job requirements.
RequiredQual: Required qualifications.
Salary: Job salary.
ApplicationP: Application procedure.
OpeningDate: Opening date of the job announcement.
Deadline: Deadline for the job announcement. 
Notes: Additional notes.
AboutC: About the company.
Attach: Attachments.
Year: Year of the announcement (derived from the field date). 
Month: Month of the announcement (derived from the field date). 
IT: TRUE if the job is an IT job. This variable is created by a simple search of IT job titles within the "Title" column.


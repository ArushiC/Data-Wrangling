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
### Data columns (total 24 columns):
jobpost: The original job post.  <br>
date: The date it was posted in the group.  <br>
Title: Job title. <br>
Company: Employer name.  <br>
AnnouncementCode: Announcement code, which is some internal code and is usually missing. <br>
Term: Full-Time, Part-time, etc. <br>
Eligibility: Eligibility of the candidates. <br>
Audience: Who can apply?  <br>
StartDate: Start date of work. <br>
Duration: Duration of the employment. <br>
Location: Employment location. <br>
JobDescription: Job Description. <br>
JobRequirment: Job requirements. <br>
RequiredQual: Required qualifications. <br>
Salary: Job salary. <br>
ApplicationP: Application procedure. <br>
OpeningDate: Opening date of the job announcement. <br>
Deadline: Deadline for the job announcement.  <br>
Notes: Additional notes. <br>
AboutC: About the company. <br>
Attach: Attachments. <br>
Year: Year of the announcement (derived from the field date).  <br>
Month: Month of the announcement (derived from the field date).  <br>
IT: TRUE if the job is an IT job. This variable is created by a simple search of IT job titles within the "Title" column. <br>


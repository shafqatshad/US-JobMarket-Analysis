# USJobMarketAnalysis
Project Title: Data Science and Software Engineering US Job Market Analysis
Objectives and Motivation of Analysis
- Job market analysis is always the hot topic that job seekers want to know. Especially,
since the COVID-19 hits the globe, searching for a job is becoming harder and more
challenging for everyone. As the job seeker in data science and software engineering
field, I want to develop a tool to give my target user job seekers a broader view of the
recent job market now and also match their profile with the suitable jobs to save time.
- Questions of interest:
• Top skills to land a job as a data scientist
• Which the popular states that are hiring?
• What’s the inferences about salaries?
• What are the industries with most data science jobs related?

Data
- Job Profile: I scrape the Glassdoor website using beautifulsoup
- H1B sponsors: using REST API to get the number of H1B files of each company on
h1bgrader.com
- Overview:
• For the job profile data, I will try to scrape the below information:
Job_title: The title of job which you are applying to
Company: Company name
State/City: State/City in which the companies job posting is listed.
Min_Salary: Minimum yearly salary in USD.
Max_Salary: Maximum yearly salary in USD.
Job_Desc: The job description which included skills,requirements,etc
Industry: The industry in which the company works.
Date_posted: The date on which the job was posted on glassdoor
Valid_until: The last date of applying to the job.
Job_Type: Type of job full-time ,

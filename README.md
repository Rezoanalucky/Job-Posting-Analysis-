# Job-Posting-Analysis-
📊 Job Posting Analytics Dashboard (Power BI) An interactive Power BI dashboard analyzing job postings from 2017–2021. The project provides insights into job market trends, skill demand, remote vs onsite roles, and location-based hiring patterns.
## 🔎 Project Overview
The main goal of this project is to analyze job postings to understand:
- 📈 How the job market changed over time  
- 🛠 Which skills are most in demand  
- 🌍 The rise of remote vs onsite job opportunities  
- 📍 Which locations had the highest hiring activity  

## 🛠 Tools & Technologies
- *Power BI* – Dashboard & Data Visualization  
- *SQL* – Data extraction & transformation  
- *Excel* – Initial data cleaning  
- *Data Modeling* – Star schema with bridge table for skills  

## 📂 Data Model
The data model is designed using a *star schema* with the following key tables:
- Dim_Date – Calendar table for time-based analysis  
- Dim_Job – Job details (title, type, location, etc.)  
- Dim_Skill – Unique skill list  
- Fact_JobPostings – Main fact table linking jobs & skills  
- Bridge_Skill – Handles many-to-many relationship between jobs and skills  


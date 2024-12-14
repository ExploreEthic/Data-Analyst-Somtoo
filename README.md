# Data-Analyst-Somtoo
Project 1 (CITY OF VANCOUVER)

![CITY OF VANCOUVER EXPLORATORY](https://github.com/user-attachments/assets/38056dd0-de1f-47d6-9659-f131251ca7ca)

Exploratory Data Analysis

Project Description: Exploring Cultural Spaces in the City of Vancouver

Project Title: Exploratory Data Analysis of Cultural Spaces in the City of Vancouver

Objective: Cultural places in the City of Vancouver are being looked at for this project to find out what kinds of spaces they are, who owns them, and where they are located. As it receives, cleans, transforms, and processes the information for useful insights, it uses an AWS-powered data pipeline.

Dataset: The dataset includes records of cultural spaces in Vancouver with attributes such as:

•	Year_ID: Year of record.

•	Cultural Space Name: Name of the cultural space.

•	Type: Classification of the cultural space (e.g., Studio/Rehearsal, Museum/Gallery).

•	Primary Use: Main use of the space (e.g., Artist Studio, Rehearsal Studio).

•	Local Area: Geographical area in Vancouver where space is located.

•	Ownership: Ownership type (e.g., Privately Owned, City of Vancouver).

Methodology:

Data Collection:

•	Raw data was ingested through an S3 bucket (cit-van-raw-som) on the AWS platform.

Data Cleaning and Transformation:

•	AWS DataBrew was used for data preparation, profiling, and cleaning (cit-van-prf-job-som and cit-van-clnstr-job-som).

•	AWS Glue was employed for ETL processes, including data transformation and structuring.

Data Storage and Visualization:
   
•	Cleaned and processed data were stored in transformed S3 buckets (cit-van-trf-som)

•	Results were visualized using draw.io.

Correlation Analysis:

•	Data shows consistent types of cultural spaces over time, reflecting stable urban cultural development.

Tools and Technologies: 

•	AWS S3: Data storage for raw, intermediate, and processed datasets.

•	AWS Glue DataBrew: For interactive data preparation, profiling, and cleaning.

•	AWS Glue: For ETL workflows and automated further data cleaning.

Deliverables:

•	A cleaned and structured dataset highlighting key attributes and trends in Vancouver’s cultural spaces.

•	Insights into relationships between attributes such as ownership, type, and location.

•	A concise report summarizing the distribution of cultural spaces, their types, and their usage across Vancouver.

The study of Vancouver's cultural places taught me a lot about where they are located, who owns them, and how people use them. Using an AWS-based ETL pipeline made sure that the data was processed and cleaned quickly, and Draw.io gave me useful information through graphics. This project shows how important data-driven methods are in cultural and urban growth and provides a way to make future analyses more flexible.

Class Activity 1 (UNIVERSITY CANADA WEST)

![UCW DESCRIPTIVE](https://github.com/user-attachments/assets/691ba7ac-fae9-4d29-a7f0-7521a39b9a1c)

Descriptive Analysis

Project Description: Descriptive Analysis of Candidate’s Faculty Profiles.

Project Title: Awareness of Candidate Faculty Profiles for the MBA Program at University Canada West.

Objective: The main purpose of this project is to look closely at all the adjunct and visiting faculty positions in the MBA program at the University Canada West, paying special attention to changes in qualifications, areas of expertise, pay, and status of the candidates. The findings will help with choices about how to use resources, how to hire people, and how to divide up the work of the faculty.

Dataset: The dataset includes detailed information on faculty appointments from University Canada West and comprises the following features:

1.	Candidate ID: Unique identifier for each faculty member.
	
2.	Name: Faculty member's full name.
	
3.	Position: Type of role, such as Adjunct or Visiting.
	
4.	Department: Academic department (e.g., Finance, Marketing, Economics, Operations).
   
5.	Experience (Years): Number of years of professional or academic experience.
	
6.	Highest Degree: Highest educational qualification (e.g., MBA, PhD).
  
7.	Specialization: Area of expertise (e.g., Corporate Finance, Digital Marketing).
   
8.	Appointment Start Date: Start date of the current appointment.
   
9.	Salary ($): Annual salary in USD.
    
10.	Status: Employment status, such as Active, On Leave, or Retired.

Methodology: 

Data Ingestion and Storage:
   
•	Raw, profiled, and cleaned datasets were stored in Amazon S3 buckets for secure and scalable access.

Data Cleaning and Transformation:
   
•	AWS Glue DataBrew was used to clean and standardize the dataset, by handling missing values, inconsistent formats, and duplicate records.

•	Accurate alignment of specializations, departments, status, and appointment dates were ensured.

Descriptive Statistical Analysis:

•	Calculated the statistical analysis of the variable:

  o	(Number of Active candidates / Total number of candidates) * 100
  
Pipeline Automation:
   
•	AWS Glue visual ETL was used to automate data transformation processes.

Visualization and Reporting:
   
•	A Draw.io design was created to communicate key findings effectively.

Tools and Technologies: 

•	AWS Cloud Services:

•	Amazon S3: Used to secure the storage of raw and processed datasets.

•	AWS Glue DataBrew: Used for data profiling, cleaning, transformation, and preparation.

•	AWS Glue Pipelines: Used to automate the extraction, transformation, and loading (ETL) of the dataset.

Deliverables:

•	A dashboard that shows trends and key results and is easy for everyone to use so that it can be monitored all the time.

This descriptive study of adjunct and visiting appointments for the MBA program at the University Canada West gives important information about the skills, expertise, specializations, and pay trends of faculty members. 

Class Activity 2 (UNIVERSITY CANADA WEST)

![UCW DIAGNOSTIC](https://github.com/user-attachments/assets/3c838ae3-f2c1-4ae1-8fa5-1869ad9fcc8f)

Diagnostic Analysis

Project Description: Diagnostic Analysis of Candidates Page View.

Project Title: Analyzing Candidates Page View Engagement at University Canada West.

Objective: The main goal of this project is to analyze clickstream data collected from prospective candidates visiting University Canada West’s website to:

1.	Understand user behaviors and preferences.
  
2.	Identify trends in device usage, time spent, and actions performed on specific web pages.
   
3.	Provide actionable insights for improving user engagement, website usability, and content placement.
   
Background: University Canada West collects clickstream data as part of its digital engagement strategy. The dataset contains information about user interactions, including page views, time spent, action types, and device usage. Using modern data analytics tools, the project aims to visualize and interpret this data to enhance the university's online presence and user experience.

Dataset: 

•	Key Features:

o	candidate_ID: Unique identifier for users.

o	page_viewed: Pages accessed (e.g., Home, Profile, About).

o	time_spent: Time spent on each page (seconds).

o	action_type: Types of user interactions (e.g., clicks, scrolls).

o	device: Device used for interaction (e.g., Mobile, Desktop, Tablet).

Methodology:  

Data Collection:
   
•	The data was collected and stored in the AWS S3 bucket (op-raw-som).

Data Preparation:
   
•	AWS DataBrew was used for cleaning, normalizing, filtering, and mapping the dataset.

Data Transformation:
   
•	Transformation pipelines, such as op-ava-enr-pip-som, structure the data for further analysis.

Integration and Storage:
   
•	Transformed and processed data is stored back in structured S3 buckets (op-cur-som) for reporting.

Visualization: The outcome was further visualized with draw.io.
   
Tools and Technologies:

•	 Platform: AWS Data Analytics Infrastructure in Virginia-1a Availability Zone

•	Data Storage: AWS S3

•	Data Cleaning and Processing: AWS DataBrew, AWS Glue

•	Visualization: Draw.io

Deliverables: 

•	Detailed clickstream analysis report showcasing user engagement patterns.

•	Recommendations for enhancing the digital strategy based on analysis insights.

Timeline: 

•	The project was scheduled to be completed in 4 weeks’ time from the day it was launched.

The diagnostic analysis of candidate clickstream data for University Canada West revealed key insight into user engagement patterns. Leveraging AWS services, the analysis highlighted the most visited pages. These findings provide actionable recommendations to enhance the university’s digital engagement strategies and improve the user experience. This project demonstrates the power of cloud-based analytics in transforming and mapping raw data into meaningful insights to support data-driven decision-making.

Project 2 (UNIVERSITY CANADA WEST)

![UCW DATA QUALITY AND PRIVACY CONTROL](https://github.com/user-attachments/assets/8a06e99e-eb88-48e0-b0cb-efe967bfc171)

Data Quality and Privacy Control

Project Title: Performing Data Quality and Privacy Control for University Canada West 

Project Description: Data Quality and Privacy Control of the President’s Office at University Canada West

Objective: The main goal of this project is to make sure that the Office of the President at University Canada West (UCW) has good data quality, safety, and protection. While keeping high data standards for analytical reasons, the project uses strong organizing methods and privacy control tools to keep private information safe. By using AWS cloud-based services like Amazon S3, AWS Glue, Athena, and KMS, the project creates a structured way to handle, process, and protect data about candidates and faculty.

Background: Due to the growing importance of data-driven decisions, colleges and universities like UCW need effective ways to store, examine, and safeguard data. As a result of managing academic appointments and private administrative data, the Office of the President needs strong governance to keep data quality high and follow privacy rules. Utilizing AWS cloud technologies, this project guarantees information handling that is flexible, safe, and efficient.

Scope: The project primarily focuses on:

Data Quality Control:
   
•	Using AWS Glue to Automate data cleaning, validation, and transformation processes.

•	Storing and managing raw, profiled, and cleaned data securely in Amazon S3 buckets.

Data Privacy and Security:
   
•	Using AWS KMS to Implement encryption and key management protocols.

•	Monitoring access and activity for compliance using CloudWatch.

•	Observing user activities with CloucTrail.

Analytical Capabilities:
   
•	Utilizing Amazon Athena for querying processed data.

•	Creating dashboards to monitor system health and user access.

Real-Time Monitoring and Reporting:
   
•	Integrating tools for performance monitoring and reporting privacy breaches or inconsistencies.

Methodology: The project procedures followed a systematic approach:

Data Collection and Storage:

•	Transformed datasets stored in Amazon S3 (op-trf-som) were used.

Data Transformation and Integration:
   
•	AWS Glue was used for ETL (Extract, Transform, Load) processes, automating data cleaning, structuring, and cataloging.

Data Querying and Analysis:
   
•	Amazon Athena provided SQL-based querying for analyzing processed datasets.

Security and Privacy Implementation:
   
•	AWS KMS ensured encryption and secure key management.

•	Data access and privacy controls were monitored using AWS CloudWatch.

Monitoring and Visualization:
    
•	System performance dashboards were built to monitor data pipelines and user activity.

•	Access logs and privacy compliance were observed by AWS CloudTrail.

Deliverables: 

•	Data Quality Framework: A fully automated pipeline for cleaning and validating faculty data.

•	Secure Data Storage: Encrypted data storage in Amazon S3 with privacy protection measures.

•	Analytics Platform: An Amazon Athena-based querying system for insights into data trends.

•	Monitoring Dashboards: Real-time CloudWatch dashboards for performance monitoring and compliance reporting.

•	Compliance Reports: Reports ensuring adherence to university data privacy regulations.

Timeline: The expected time to complete this project is 10 weeks including cleaning, monitoring, observing, querying, and control.

To help the University Canada West manage data quality and protection, this project builds a strong and expandable structure. To make sure confidentiality rules are followed, the project uses AWS cloud services to process, store, and protect private data in an efficient way. For increased efficiency in the university's administrative processes, real-time tracking and automatic reports make data pipelines even more reliable and well-managed.

The following projects show my ability to clean and analyze data using advanced techniques which highlight my critical thinking, problem-solving, attention to detail, and communication skills. Below are the scenarios for Projects 1 through 3. 

View the docx files with the python files to see my data validation reports based on each project. Project 1 does not have a python file.

--------------------------------------------

Project One Scenario:
Your organization is in the process of acquiring another firm. Before the start of the acquisition process, your organization obtained data from this firm through a formal data request so that the two companies could begin the process of joining the data. The data request is used to gather information to help in developing requirements, standards, and databases, as well as in conducting analyses. Before the new firm’s data is integrated, your organization wants to develop a data quality plan to ensure that the data maintains quality and integrity during the process of joining and cleaning. Your supervisor has sent you the following email:

From: Smith, Supervisor
Sent: Today
To: Beta, Employee
Subject: Data Quality Plan Project

Good morning, Employee,

Recently, leadership began the process of acquiring the new firm. To support this acquisition, data was obtained from the firm that needs to be assessed for quality and cleaned/transformed to give us the high-quality data that we need to move forward. To accomplish this, I need you to complete a data quality plan using this template [link below]. We want to ensure that the data we are cleaning and transforming is of high quality based on industry standards, and that the process is aligned with our organizational goals.

Let me know if you have any questions,
Supervisor Smith
Data Strategy Program Manager

Directions
Before you begin profiling and joining the data, you want to be sure you are following best practices for assessing data quality and aligning with your organization’s goals. Using the template, document your plan for cleaning and transforming the data using quality standards.

Your data quality plan should address the following:

Purpose Statement: Explain why high-quality data is a vital business requirement.
Why should your organization spend resources to study the data quality of the new firm?
How can high-quality data generate value and reduce costs for your organization?
Refer to the resources in Modules One and Two for additional support on these topics.
Organizational Goals: Identify the organizational goals.
Identify at least three objectives of the organization with respect to high-quality data.
Explain how high-quality data can help achieve each of these objectives.
Refer to the resources in Modules One and Two for additional support on these topics.
Data Quality Characteristics and Procedures: Explain the characteristics that define data quality using industry standards.
What dimensions of data quality are critically important for the data involved in this acquisition?
How do you plan to address these dimensions?
Refer to the resources in Module Two for additional support on these topics.
Security and Personnel Responsibility: Describe how security policies impact data quality.
Why is data risk management important in this acquisition?
Identify critical gaps that leadership should track in mitigating data risk.
Which roles must your organization understand for proper data governance, and why?
Refer to the resources in Modules One and Three for additional support on these topics.

--------------------------------------------

Project Two Scenario: 

You have successfully completed a data quality plan. Now it is time to start reviewing the data. You have received this email from your supervisor:

From: Smith, Supervisor
Sent: Today
To: Beta, Employee
Subject: Data Quality Plan Project

Good morning, Employee,

I hope that you had a good weekend!

Thank you for developing a data quality plan for us to follow. Now that we have established a strong plan, the project of merging the new firm’s data with our data is starting as of today.

You will begin by profiling the data. When profiling the data, please identify any errors or anomalies with specific variables of interest to us.

Specify the data types and transformations that are needed to merge this with our master data.

Include an explanation of your data profiling findings in a summary.

When you’re finished, return your Executive Summary Report to me so I can communicate the plan to our stakeholders.

Let me know if you have any questions,
Supervisor Smith
Data Strategy Program Manager

Directions
You will begin this project in uCertify and perform various data profiling tasks. Navigate to the Hands-on Labs area of uCertify and scroll down to Module Five. There you will find Lab 9.1, which is your lab for Project Two. Follow the instructions provided to assess the quality of the data. Remember to keep the data quality dimensions in mind.

Use the provided template linked in the What to Submit section below to document your responses. In your analysis, be sure to do the following:

Data Types: Evaluate the data types present in the data set based on a data dictionary.
A data dictionary has been provided to you by the firm and is included in your uCertify project lab.
Review this data dictionary and report the data type of the variables of interest in this project.
There are a total of four variables in this project that you will be profiling.
Anomalies: Explain your plan to resolve the errors and anomalies in the data set by data profiling.
Using filters in Python, identify errors and anomalies in the data set.
For each, determine a plan for resolution.
Transforms: Evaluate how you will transform your data to import it into the existing database.
Since you are instructed to merge the new firm’s data with the data in your company’s database, it is important to identify common variables that will be used for joining. This might involve having to do transformations to join the new data.
Suppose your company’s database includes the following columns that you would use for joining:
Variable Name	Data Type	Metadata
First Name	varchar	First name of employee
Last Name	varchar	Last name of employee
DOB	Date	Date of birth of employee
Explain what transformations are needed in the new data to be able to merge it with the database. Note that you do not need to perform these transformations at this stage.
Summary: Effectively communicate data quality issues and the steps toward resolution to stakeholders in a summary. Explain the steps you took to profile and clean data for use in the organizational merge.

--------------------------------------------

Project Three Scenario:

You have successfully identified issues in the new firm’s data and now it is time to start cleaning this data. You have received this email from your supervisor:

From: Smith, Supervisor
Sent: Today
To: Beta, Employee
Subject: Data Quality Plan Project

Good morning, Employee,

I hope that you had a good weekend!

Previously, you profiled the new firm’s data and identified errors and anomalies. You will now perform tasks to clean the firm’s data, use appropriate transformations, and merge it with our data. This will complete the data profiling and merging process. We will use this new data asset to gain new insights and make data-driven decisions.

When you’re finished, return your Executive Summary Report to me so I can communicate the completion of this task to our stakeholders.

Let me know if you have any questions,
Supervisor Smith
Data Strategy Program Manager

Directions
You will begin this project in uCertify and perform various data validation tasks. Navigate to the Hands-on Labs area of uCertify and scroll down to Module Seven. There you will find Lab 12.2.2, which is your lab for Project Three. Follow the instructions provided to complete the data validation tasks.

Use the provided template linked in the What to Submit section below to document your responses.

In your data validation, be sure to do the following:

Use the data profiling results documented in your Executive Summary Report from Project Two to clean and transform your data in uCertify. Follow the instructions in uCertify to perform the following tasks:
Clean data: Clean the data using the errors and anomalies identified in your data profile.
Transform data: Transform the data using the transformations identified in your data profile and merge this data with your company’s data.
Perform the following data validation tasks and document the results in the provided template:
Counts: Analyze the firm’s data that has been cleaned, your company’s data, and the merged data. Provide counts of rows and columns of these data sets to ensure a correct merge.
MIN, MAX, AVERAGE: Determine the distribution of quantitative variables in the firm’s clean data and report the minimum, maximum, and average values.
Distribution data: Describe how the distribution of quantitative variables confirms that the data has been cleaned.
Summary: Summarize the changes made to the data set during cleaning and transformation. Explain how the validation steps ensure the final data is clean and of high quality.

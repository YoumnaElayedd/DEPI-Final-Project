HR Data Analysis Project
This project provides an in-depth analysis of HR data, leveraging Python, SQL, and Power BI to uncover insights related to employee performance, satisfaction, experience, and attrition. It includes interactive dashboards and SQL-driven insights, enabling HR managers to make informed decisions to enhance employee retention, optimize performance evaluations, and improve job satisfaction.

📌 Project Goals
Workforce Demographics and Diversity: Analyze workforce composition by gender, ethnicity, age, and business travel frequency to support diversity initiatives.
Improving Job Satisfaction: Assess satisfaction levels to identify and address areas with lower engagement.
Understanding Performance Trends: Explore discrepancies and trends in self and manager ratings.
Optimizing Training and Development: Evaluate the impact of training opportunities on top performers.
Enhancing Employee Retention: Pinpoint factors influencing attrition to develop targeted strategies.
🛠️ Tools and Technologies
Python:

Data preprocessing and cleaning.
Libraries used: Pandas, NumPy, SQLAlchemy.
Key actions:
Handled missing values and formatted columns.
Calculated metrics like attrition year and filtered out-of-range performance reviews.
Merged datasets and standardized data types.
SQL:

Data storage and advanced analysis.
Key actions:
Connected Python to SQL Server using SQLAlchemy.
Uploaded preprocessed data and ran SQL queries for insights on salaries, performance, and satisfaction.
Power BI:

Interactive dashboards for visualization and analysis.
Key actions:
Designed dashboards for satisfaction, performance, attrition, and salary trends.
Created dynamic slicers and calculated measures for deep analysis.
📋 Project Highlights
Python Data Preprocessing
Removed spaces and inconsistencies in columns.
Calculated attrition year and dropped outdated performance ratings.
Merged datasets for seamless analysis.
SQL Analysis
Extracted insights using advanced SQL queries:
Average salary by department, job role, and demographics.
Satisfaction metrics by age, gender, and ethnicity.
Attrition rates by department and job role.
Power BI Dashboards
Interactive views for:
Employee Overview: Total employee count, average salary, demographics.
Satisfaction Overview: Analysis of satisfaction levels (environment, job, work-life balance).
Ratings Overview: Manager and self-rating trends.
Attrition Overview: Employee turnover by various factors.
Dynamic filters for year, department, and job role.
⚙️ Setup and Usage
Prerequisites
Python (3.x) with necessary libraries.
SQL Server with SQLAlchemy for database connection.
Power BI Desktop for dashboard visualization.
Steps to Run
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/hr-data-analysis.git
Python Preprocessing:

Run the Jupyter notebook for data cleaning and merging.
Export processed data as .csv files.
SQL Server:

Import the processed data into SQL Server tables.
Use provided SQL scripts for analysis.
Power BI Dashboards:

Open the Power BI file.
Refresh the data to connect with SQL Server.
📊 Insights Delivered
Trends in salary distribution and its correlation with performance.
Satisfaction discrepancies across departments and roles.
Identification of high-risk attrition areas.
Impact of training programs on top performers.
🚀 Team Members
Hady Mohamed Kilany
Yomna Elsayed Shehata
Shiamaa Elromh
Mohamed Yassen
Farah Essam

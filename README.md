# SQL_Job_Analysis
# Tools Used :wrench:
1. **PostgreSQL** as database management system
2. **SQL** the backbone programming language for analysis 
3. **Excel PivotChart & PowerBI** for visualization :bar_chart:

# Create and Load Database :open_file_folder:
1. CREATE DATABASE in PostgreSQL
2. CREATE TABLE to load excel data 
3. LOAD CSV file path into respective tables

# Projects : Questions to Answer :question:
1. What are the top-paying jobs for Data Analyst Job?
2. What are the skills required for the top paying roles?
3. What are the most in-demand skills for the roles?
4. What are the top kills based on salary?
5. What are the most optimal skills to learn? \
         a. Optimal : High Demand AND High Paying

# The Analysis :chart_with_upwards_trend:
## 1. Top 10 Paying Data Analyst Jobs

<img width="1404" height="761" alt="image" src="https://github.com/user-attachments/assets/409896b7-8a0b-4848-b61b-a8f4a77bfac1" />

- **Salary Range:** Director & Associate Director roles mostly cluster around 250–330k USD, indicating typical high-end data leadership pay.
- **Job Title:** Diversity of job titles, reflecting varied career path & opportunities within analytics. 
- ❗❗**HOWEVER**, there could be an **outlier** in "Data Analyst" job as it pays higher than all “Director” and “Principal” titles.❗❗ \
           -- Likely due to company type (startup equity-based) **OR** misleading job title
- ⚠️ **Action to Take:** Flag the data as outlier and seek for further investgation.

## 2. Skills Required for Top Paying Data Analyst Jobs



- Programming language like **SQL** (8 counts) is the most in-demand skills and **Python** (7 counts) came in second.
- Visualization tools like **Tableau** (6 counts) and **PowerBI** (2 counts) highlight their importance in a Data Analyst’s skill set.
- ❗❗Based on the dataset, these are key skills required for top-paying data analyst roles, reflecting the tools commonly used in their daily work.❗❗

## 3. In-Demand Skills for Data Analysts

| Skills | Demand_Count |
|SQL	| 7,291    |
|Excel	| 4,611    |
|Python	| 4,330    |
|Tableau	| 3,745    |
|PowerBI	| 2,609    |

- ❗❗**SQL** and **Excel** form the backbone of data analysis, highlighting the need in data handling and analytical workflow.
- **Python**, **Tableau**, and **PowerBI** complement the workflow by enabling automation, visualization, and storytelling that help with strategic decision-making.❗❗



## 4. Skills Based On Salary
Here's a breakdown of the results for top paying skills for Data Analysts:

High Demand for Big Data & ML Skills: Top salaries are commanded by analysts skilled in big data technologies (PySpark, Couchbase), machine learning tools (DataRobot, Jupyter), and Python libraries (Pandas, NumPy), reflecting the industry's high valuation of data processing and predictive modeling capabilities.
Software Development & Deployment Proficiency: Knowledge in development and deployment tools (GitLab, Kubernetes, Airflow) indicates a lucrative crossover between data analysis and engineering, with a premium on skills that facilitate automation and efficient data pipeline management.
Cloud Computing Expertise: Familiarity with cloud and data engineering tools (Elasticsearch, Databricks, GCP) underscores the growing importance of cloud-based analytics environments, suggesting that cloud proficiency significantly boosts earning potential in data analytics.

## 5. Optimal Skills 
Here's a breakdown of the most optimal skills for Data Analysts in 2023:

High-Demand Programming Languages: Python and R stand out for their high demand, with demand counts of 236 and 148 respectively. Despite their high demand, their average salaries are around $101,397 for Python and $100,499 for R, indicating that proficiency in these languages is highly valued but also widely available.
Cloud Tools and Technologies: Skills in specialized technologies such as Snowflake, Azure, AWS, and BigQuery show significant demand with relatively high average salaries, pointing towards the growing importance of cloud platforms and big data technologies in data analysis.
Business Intelligence and Visualization Tools: Tableau and Looker, with demand counts of 230 and 49 respectively, and average salaries around $99,288 and $103,795, highlight the critical role of data visualization and business intelligence in deriving actionable insights from data.
Database Technologies: The demand for skills in traditional and NoSQL databases (Oracle, SQL Server, NoSQL) with average salaries ranging from $97,786 to $104,534, reflects the enduring need for data storage, retrieval, and management expertise.

# SQL_Job_Analysis
# Tools Used :wrench:
1. **PostgreSQL** as database management system
2. **SQL** the backbone programming language for analysis 
3. **Excel PivotChart & PowerBI** for visualization :bar_chart:


# Projects : Questions to Answer :question:
1. What are the top-paying jobs for Data Analyst Job?
2. What are the skills required for the top paying roles?
3. What are the most in-demand skills for the roles?
4. What are the top kills based on salary?
5. What are the most optimal skills to learn? \
         a. Optimal : High Demand AND High Paying


# Create and Load Database :open_file_folder:
1. CREATE DATABASE in PostgreSQL
2. CREATE TABLE to load excel data 
3. LOAD CSV file path into respective tables
   

# The Analysis :chart_with_upwards_trend:
## 1. Top 10 Paying Data Analyst Jobs

<img width="1404" height="761" alt="image" src="https://github.com/user-attachments/assets/409896b7-8a0b-4848-b61b-a8f4a77bfac1" /> <br>

<br>
1️⃣ **Salary Range:** Director & Associate Director roles mostly cluster around 250–330k USD, indicating typical high-end data leadership pay.\
2️⃣ **Job Title:** Diversity of job titles, reflecting varied career path & opportunities within analytics. \
3️⃣❗**HOWEVER**, there could be an **outlier** in "Data Analyst" job as it pays higher than all “Director” and “Principal” titles. \
           -- Likely due to company type (startup equity-based) **OR** misleading job title\
4️⃣ ⚠️ **Action to Take:** Flag the data as outlier and seek for further investgation.

## 2. Skills Required for Top Paying Data Analyst Jobs

<img width="1945" height="1057" alt="image" src="https://github.com/user-attachments/assets/5f38dae4-3c26-4a99-9873-9e76d7a00110" />

1️⃣ Programming language like **SQL** (8 counts) is the most in-demand skills and **Python** (7 counts) came in second.\
2️⃣ Visualization tools like **Tableau** (6 counts) and **PowerBI** (2 counts) highlight their importance in a Data Analyst’s skill set.\
3️⃣ Based on the dataset, these are key skills required for top-paying data analyst roles, reflecting the tools commonly used in their daily work.

## 3. In-Demand Skills for Data Analysts

| Skills | Demand_Count |
| :------| :----------  |
|SQL	| 7,291    |
|Excel	| 4,611    |
|Python	| 4,330    |
|Tableau	| 3,745    |
|PowerBI	| 2,609    |

1️⃣ **SQL** and **Excel** form the backbone of data analysis, highlighting the need in data handling and analytical workflow.\
2️⃣ **Python**, **Tableau**, and **PowerBI** complement the workflow by enabling automation, visualization, and storytelling that help with strategic decision-making.



## 4. Skills Based On Salary

| Skills          | Average_Salary |
| :---------------| :----------  |
|PySpark	         | $208,172    |
|Bitbucket	| $189,155    |
|Watson         	| $160,515    |
|Couchbase	| $160,515    |
|DataRobot	| $155,486    |
|GitLab	         | $154,500    |
|Swift         	| $153,750    |
|Jupyter         	| $152,777    |
|Pandas         	| $151,821    |
|Elasticsearch	| $145,000    |

1️⃣ Top-paying data analyst roles favor professionals with advanced **technical and programming capabilities** — particularly in big data (PySpark), AI-driven tools (Watson, DataRobot), and modern cloud data ecosystems (Couchbase, Elasticsearch).\
2️⃣ Strong Python analytics experience (Pandas, Jupyter) further enhance earning potential, showing that data analysts with **data exploration and predictive modeling development skills** command high salaries.\
3️⃣ Familiarity with collaborative DevOps tools (GitLab, Bitbucket) that **automate the routine steps and provides efficient data pipeline management** also highlights their strong association with higher-paying roles.


## 5. Optimal Skills 

| Skills          | Demand_Count | Average_Salary |
| :---------------| :----------  | :----------  |
|Go	         | 27     | $115,320    |
|Confluence	| 11     | $114,210    |
|Hadoop         	| 22     | $113,193    |
|Snowflake	| 37     | $112,948    |
|Azure         	| 34     | $111,225    |
|BigQuery	| 13     | $109,654    |
|AWS         	| 32     | $108,317    |
|Java         	| 17     | $106,906    |
|SSIS         	| 12     | $106,683    |
|Jira         	| 20     | $104,918    |
|Oracle         	| 37     | $104,534    |
|Looker         	| 49     | $103,795    |
|NoSQL         	| 13     | $101,414    |
|Python         	| 236    | $101,397    |
|R         	| 148    | $100,499    |


Optimal skills for data analyst roles combine high demand and strong salary potential:
- Core analytical skills: Python, R
- Data visualization and reporting: Looker
- Cloud and big data platforms: Snowflake, Azure, AWS, BigQuery, Hadoop
- ETL and database management: SSIS, Oracle, NoSQL
- Collaboration and workflow: Jira, Confluence

:one: **Programming languages** such as Python and R remain in high demand, though their average salaries are comparatively lower. This suggests that while these skills are essential and highly valued, they are also widely available among professionals. \
:two: **Cloud tools and big data technologies** command demand with higher average salaries, reflecting the growing importance of cloud platforms and scalable data solutions in modern analytics. \
:three: **Database technologies**, with average salaries ranging from $97,786 to $104,534, highlight the continued need for expertise in data storage, retrieval, and management across analytical roles.


# Mini-ETL Project (VPC Data Flow)

This is an on-going project for simulating a mini local ETL pipeline for ingesting data collected from web traffic records through AWS CloudWatch. The datasource was sourced from Kaggle. 

The rationale behind kickstarting this mini project is to get a better understanding of how to use Airflow. However, I thought about making it more challenging & learning new concepts at the same time, which is why I dive into looking for datasets related to web traffic or cybersecurity. 

As the pipeline is being built, the proof of concept could be applied to any other kinds of project which involves collecting web traffic data, cleaning & transforming, and loading them into a database ready for BI visualisations and reporting.



## Features of the Project

- Auto ingestion of data via API
- Simplified user-defined functions for cleaning/transforming data
- 3NF Tables


## Tech Stack

**Jupyter Notebooks:** 

- Used for intial data exploration, cleaning & transformation testing.

**Python (Visual Studio Code):**

- Planned to convert the Jupyter Notebooks into Python scripts for better modularity & scalability. Using VS Code as my preferred IDE for debugging. 

**PostgreSQL (PgAdmin4):**

- Will be used as the local relational database for storing the cleaned/transformed datasets, facilitating efficient data storage and for further querying via SQL.

**Microsoft Power BI:**

- To be used for performing data analysis & visualisations of the web traffic data from VPC, providing insights in a visually appealing format.

**Apache Airflow (Planned):**

- Planned to use Airflow to orchestrate & automate the data pipeline once the project/workflow matures, providing better scheduling, monitoring & scalability.


## Roadmap

- Create Python Scripts for ETL notebooks (**current**)
- Incorporate Airflow to automate/schedule the entire pipeline
- Include a "Getting Started" Section in README
## Lessons Learned

-- To be updated --


## FAQ

#### What's The Purpose Of This Project?

To demonstrate an ETL process for ingesting datasets related to cybersecurity or web traffic, which can then be further broke down with data modeling concepts, and finally analysing them using BI tools such as Power BI.

#### How Many Phases Are In This Project?

There are 4 phases planned out currently:

- Phase 1: Create Jupyter Notebooks for testing ETL pipeline (Done)
- Phase 2: Convert notebooks into Python Script (in-progress)
- Phase 3: Power BI Visualisations (not started)
- Phase 4: Airflow (not started)

#### What's The Current Status Of This Project?

As of **Monday, 30th September 2024**, the notebooks for ETL process are done. The next steps are to convert & streamline them into python scripts, and check if everything runs correctly via CLI. And finally, the final stages of the project will be phase 3 & 4, which is to incorporate the BI visualisations and Airflow.


## Acknowledgements

 - [Suspicious Web Threat Interactions Dataset](https://www.kaggle.com/datasets/jancsg/cybersecurity-suspicious-web-threat-interactions)
 - [ipaddress Python Module](https://docs.python.org/3/library/ipaddress.html)



## Other Simlar Projects

⚡️ [Local ETL Pipeline - Netflix Data](https://github.com/splatpugs/jde-interim)

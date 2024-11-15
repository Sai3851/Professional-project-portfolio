# Professional-project-portfolio
This repository features projects completed during my career as a Data Analyst, showcasing skills in data processing, visualization, predictive modeling, data quality, and analysis. Each project includes objectives, methodologies, and outcomes, with links to ongoing work and code repositories for in-depth exploration.
## Introduction
I’m a dedicated Data Analyst with a strong background in delivering impactful, data-driven solutions across industries such as finance, engineering, and construction. With expertise in SQL, Python, Power BI, and data quality frameworks, I excel at extracting insights from complex datasets and crafting visualizations that inform business strategy. My experience spans data governance, predictive modeling, and stakeholder engagement, allowing me to bridge technical analysis with strategic decision-making. Passionate about uncovering trends and enhancing data processes, I continuously seek innovative ways to leverage data to drive value.
## Professional Projects
As a Data Analyst at Datactics, UK, I contributed to a variety of projects focused on data engineering and analysis for leading organizations in the UK's banking and government sectors. Detailed descriptions of each project are provided below.
### 1. Upgrade for Existing Client (Major UK Bank)
#### Objective
The primary objective of this project is to upgrade the licensed proprietary software for an existing client. This involves migrating banking data and data quality rules, with a focus on data cleaning, standardization, visualization, and implementing custom data quality rules tailored to the client's requirements.
#### Tools
Datactics proprietary Software, SQL, Python, Power BI
#### Skills
Data Engineering, SQL Querying, Python scripting, Data Visualization
#### Techniques & Approaches
* This project primarily involved a complete migration of the existing data pipeline, including the transfer of built data quality rules, toolset configurations, predefined sets, and custom data rules designed to process periodic data (monthly data) sourced from the client’s CRM system.
* The initial phase focused on upgrading the client's software to the latest release, ensuring compatibility for a seamless migration of project components. Before the upgrade, data quality rules, toolset configurations, and other custom rules were carefully exported for re-deployment in the new environment.
* Subsequently, the exported data and configurations were uploaded into their respective environments, ensuring all toolsets, rules, and datasets were accurately restored to their original operational states.
* Periodic data from the client’s source undergoes extensive processing through numerous data quality rules. To mitigate storage issues caused by failed iterations, sample rules were executed first to identify configuration errors. These errors were traced to toolset configurations, requiring adjustments to SQL queries and Python scripts to align with the updated software version.
* Once the sample rules executed successfully, the main data quality rules were triggered. Failures were encountered at times due to inconsistencies in data encoding or standardization that conflicted with the rule conditions. In such cases, manual inspection and countermeasures were applied, including data cleaning and standardization using SQL and Datactics’ proprietary software to address discrepancies.
* Significant challenges included instances where 40% of the rules failed due to discrepancies in data quality, storage issues, and other anomalies. These errors were resolved manually to ensure smooth and accurate processing.
* Upon the successful execution of the main data quality rules, results were integrated into Power BI Desktop. An interactive, custom dashboard was developed to allow the client to review data points that failed to meet the established quality standards, facilitating transparent analysis and resolution.
#### Results
The successful completion of this project resulted in several key outcomes:
* Seamless Migration: All data quality rules, toolset configurations, and custom data processing rules were successfully migrated to the upgraded environment, ensuring continuity in the client's data pipeline processes.
* Enhanced Data Quality: Periodic data from the client's CRM was thoroughly validated, cleaned, and standardized, addressing discrepancies in encoding and storage. This significantly improved the overall data accuracy and reliability for downstream processes.
* Error Resolution: Approximately 40% of initial rule failures due to data discrepancies and configuration issues were systematically resolved, ensuring a high success rate in processing data through quality rules.
* Operational Efficiency: SQL queries and Python scripts were updated to align with the latest software version, enabling smoother and faster processing of periodic data.
*Client Insights: An interactive Power BI dashboard was delivered, providing the client with real-time visibility into data quality performance. The dashboard facilitated the identification and resolution of data points failing to meet established standards, empowering the client to make informed decisions.
* Improved System Performance: The pre-validation of sample rules minimized storage issues during full runs, optimizing system resources and ensuring smoother operations for large-scale data processing.
These results collectively enhanced the client's data processing capabilities, bolstered their confidence in data quality, and streamlined their operational workflows.

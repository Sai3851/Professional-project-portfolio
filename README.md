# 📂💼 Professional Project Portfolio
Hi there.. Welcome to my professional project portfolio. This repository features projects completed during my career as a Data Analyst, showcasing skills in data processing, visualization, predictive modeling, data quality, and analysis. Each project includes objectives, methodologies, and outcomes, with links to ongoing work and code repositories for in-depth exploration.
## 📜👋 Introduction
I’m a dedicated Data Analyst with a strong background in delivering impactful, data-driven solutions across industries such as finance, engineering, and construction. With expertise in SQL, Python, Power BI, and data quality frameworks, I excel at extracting insights from complex datasets and crafting visualizations that inform business strategy. My experience spans data governance, predictive modeling, and stakeholder engagement, allowing me to bridge technical analysis with strategic decision-making. Passionate about uncovering trends and enhancing data processes, I continuously seek innovative ways to leverage data to drive value.
## 🚀💼 Professional Projects
As a Data Analyst at Datactics, UK, I contributed to a variety of projects focused on data engineering and analysis for leading organizations in the UK's banking and government sectors. Detailed descriptions of each project are provided below.
### 1. Upgrade for Existing Client (Major UK Bank)🔄💼
#### 🎯📌 Objective
The primary objective of this project is to upgrade the licensed proprietary software for an existing client. This involves migrating banking data and data quality rules, with a focus on data cleaning, standardization, visualization, and implementing custom data quality rules tailored to the client's requirements.
#### 🛠️ Tools
Datactics proprietary Software, SQL, Python, Power BI
#### 🧠 Skills
Data Engineering, SQL Querying, Python scripting, Data Visualization
#### ⏳📅 Project Duration
3 Months
#### 📚 Techniques and Approaches
* This project primarily involved a complete migration of the existing data pipeline, including the transfer of built data quality rules, toolset configurations, predefined sets, and custom data rules designed to process periodic data (monthly data) sourced from the client’s CRM system.
* The initial phase focused on upgrading the client's software to the latest release, ensuring compatibility for a seamless migration of project components. Before the upgrade, data quality rules, toolset configurations, and other custom rules were carefully exported for re-deployment in the new environment.
* Subsequently, the exported data and configurations were uploaded into their respective environments, ensuring all toolsets, rules, and datasets were accurately restored to their original operational states.
* Periodic data from the client’s source undergoes extensive processing through numerous data quality rules. To mitigate storage issues caused by failed iterations, sample rules were executed first to identify configuration errors. These errors were traced to toolset configurations, requiring adjustments to SQL queries and Python scripts to align with the updated software version.
* Once the sample rules executed successfully, the main data quality rules were triggered. Failures were encountered at times due to inconsistencies in data encoding or standardization that conflicted with the rule conditions. In such cases, manual inspection and countermeasures were applied, including data cleaning and standardization using SQL and Datactics’ proprietary software to address discrepancies.
* Significant challenges included instances where 40% of the rules failed due to discrepancies in data quality, storage issues, and other anomalies. These errors were resolved manually to ensure smooth and accurate processing.
* Upon the successful execution of the main data quality rules, results were integrated into Power BI Desktop. An interactive, custom dashboard was developed to allow the client to review data points that failed to meet the established quality standards, facilitating transparent analysis and resolution.
#### 📊✅ Results
The successful completion of this project resulted in several key outcomes:
* Seamless Migration: All data quality rules, toolset configurations, and custom data processing rules were successfully migrated to the upgraded environment, ensuring continuity in the client's data pipeline processes.
* Enhanced Data Quality: Periodic data from the client's CRM was thoroughly validated, cleaned, and standardized, addressing discrepancies in encoding and storage. This significantly improved the overall data accuracy and reliability for downstream processes.
* Error Resolution: Approximately 40% of initial rule failures due to data discrepancies and configuration issues were systematically resolved, ensuring a high success rate in processing data through quality rules.
* Operational Efficiency: SQL queries and Python scripts were updated to align with the latest software version, enabling smoother and faster processing of periodic data.
*Client Insights: An interactive Power BI dashboard was delivered, providing the client with real-time visibility into data quality performance. The dashboard facilitated the identification and resolution of data points failing to meet established standards, empowering the client to make informed decisions.
* Improved System Performance: The pre-validation of sample rules minimized storage issues during full runs, optimizing system resources and ensuring smoother operations for large-scale data processing.
These results collectively enhanced the client's data processing capabilities, bolstered their confidence in data quality, and streamlined their operational workflows.
### 2. Data Quality Enhancement (Renowned Northern-Irish Jewellers)💎✨
#### 🎯📌 Objective
The main objective of this project is to clean and standardize the data followed by establishing data quality rules to provide metrics according to client requirements along with UK address validation.
#### 🛠️ Tools
SQL, Datactics' Proprietary Software
#### 🧠 Skills
Data Analysis, SQL Querying, Regular expressions, address validation, data cleaning and standardization
#### 📚 Techniques and Approaches
* The project began with the secure transfer of a single dataset, which served as the foundation for the work. Using Datactics' proprietary software, an in-depth profiling of the dataset was conducted to identify discrepancies and anomalies, providing a clear understanding of the data's quality and standardization needs.
* A comprehensive profiling report was prepared and submitted to the client's Subject Matter Experts (SMEs) for review and agreement on the project scope. Major anomalies within the dataset were addressed using SQL to perform initial data cleansing, resolving inconsistencies across the dataset.
* The partially cleansed dataset was then loaded into Datactics' software for advanced cleaning and standardization, aligning with the scope outlined. Advanced techniques focused specifically on address columns to validate addresses against the UK PAF (Postcode Address File), ensuring data accuracy and consistency.
* Multiple data cleaning and standardization techniques, including the use of regular expressions, were employed to achieve uniformity across the dataset. Unmatched address records identified during validation were flagged as part of a data quality rule, enabling the client to perform manual verification or corrections.
* Data quality rules were developed alongside flagged records and delivered to the client. A detailed final report was provided, outlining the data cleansing and standardization activities performed, along with a description of each quality rule. Screenshots and supporting documentation were included for clarity and client reference.
#### 📊✅ Results
* Enhanced Data Accuracy: Successfully cleansed and standardized the dataset, significantly reducing discrepancies and ensuring alignment with the client’s data quality standards.
* Validated Address Data: Performed advanced address validation using the UK PAF file, ensuring accurate and consistent address records across the dataset. Unmatched records were flagged for manual review, enhancing the reliability of the client's data.
* Custom Data Quality Rules: Developed and implemented tailored data quality rules to automate the detection of discrepancies and standardize the dataset, reducing manual intervention and improving efficiency.
* Detailed Documentation: Delivered a comprehensive report outlining the cleansing and standardization activities, including descriptions of each data quality rule and supporting screenshots, providing transparency and actionable insights for the client.
* Improved Data Usability: Delivered a standardized, high-quality dataset ready for integration into the client’s workflows, enabling informed decision-making and enhancing operational efficiency.
* Client Satisfaction: The project scope was met on time, and the client acknowledged the detailed reporting and systematic approach, ensuring long-term confidence in their data management processes.
### 3. Data Analysis and Insights Project (UK County Council 🇬🇧)
#### 🎯📌 Objective
The primary objective of this project was to analyze periodic datasets from the client by performing data cleaning, standardization, and address validation. The project also involved establishing a data pipeline with iterative data quality rules, enabling the client’s periodic datasets to be processed seamlessly. Additionally, a Power BI dashboard was developed to visualize rule results and track data quality improvements over time, providing actionable insights to the client.
#### 🛠️ Tools
Datactics' software, PAF, PowerBI
#### 🧠 Skills
Data Analysis, Regular expressions, Address validation, data cleaning and standardization, Dashboarding
#### 📚 Techniques and Approaches
* Upon agreeing to the project scope with stakeholders from both sides, the dataset was securely retrieved from the client's database for analysis.
* An in-depth profiling of the dataset was conducted using advanced data profiling techniques to identify discrepancies, anomalies, and areas requiring cleaning and standardization. This step provided a clear understanding of the data's quality and helped define actionable steps for improvement.
* A comprehensive profiling report was prepared and submitted to the client's Subject Matter Experts (SMEs) for review. Major anomalies within the dataset were resolved using SQL, ensuring initial data cleansing and addressing inconsistencies across the dataset.
* The partially cleansed dataset was then loaded into Datactics' software for advanced cleaning and standardization. Advanced techniques were applied to address-specific columns, particularly focusing on address validation using the UK PAF (Postcode Address File). This ensured the accuracy and consistency of address data.
* Various data cleaning and standardization techniques, including the use of regular expressions, were employed to achieve uniformity across the dataset. Unmatched address records identified during validation were flagged as part of a data quality rule, allowing the client to manually verify or correct these records.
* Data quality rules were developed and iteratively tested, ensuring seamless processing of periodic datasets. A final report was delivered, documenting all cleansing and standardization activities, alongside detailed descriptions of each data quality rule, supported by screenshots and relevant documentation.
* Interactive Dashboarding: To enhance client understanding, an interactive Power BI dashboard was created to visualize the results of the data quality rules. The dashboard highlighted the number of data points passing and failing the rules, offering a clear view of the dataset's overall quality and enabling data-driven decision-making.
#### 📊✅ Results
* Improved Data Accuracy: Successfully cleaned and standardized the dataset, addressing anomalies and inconsistencies to enhance data reliability and usability.
* Validated Address Data: Achieved comprehensive address validation using the UK PAF file, ensuring accurate and consistent address records. Unmatched records were flagged for client review, further strengthening data quality.
* Efficient Data Pipeline: Established an iterative data quality pipeline that seamlessly processed periodic datasets, enabling the client to maintain high data standards over time.
* Enhanced Client Insights: Delivered an interactive Power BI dashboard that provided real-time visualization of data quality rule results. The dashboard allowed the client to monitor the number of data points passing and failing the rules, facilitating actionable insights and better decision-making.
* Stakeholder Satisfaction: Provided detailed documentation of all data cleansing activities, including descriptions of data quality rules and supporting visuals, ensuring transparency and client satisfaction.
* Operational Efficiency: Streamlined data validation and quality processes, significantly reducing manual intervention and saving time for the client's data operations team.
This project not only improved the client’s data quality but also empowered them with tools and insights to monitor and sustain their data accuracy effectively.

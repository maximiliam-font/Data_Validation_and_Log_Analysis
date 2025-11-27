## Taxi App Data Validation & Log Analysis
>”To understand is to honor the truth beneath the surface.”
<br/>
In this project, I executed a full technical analysis, debugging workflow, and data validation process using server logs and SQL queries to ensure the correct operation of the Urban Routes taxi system. The main goal was to identify errors, validate critical information, and provide clear documentation to support developers in resolving incidents and improving backend stability.

## 🎯 Project Objective
Ensure system integrity by investigating server-side failures, validating structured data in the database, analyzing business logic, and documenting insights that enable data-driven decision-making.

## Features
-	🔍 Full investigation of 400 and 500 server errors
-	📁 Professional organization of evidence in functional directories
-	🧭 Request tracing by IP to identify anomalous patterns
-	🗃️ SQL data validation for fleet, trips and companies
-	🌦️ Hour-based weather classification to debug fare coefficient logic
-	🚕 Analysis of real system availability vs. expected taxi capacity
-	💰 Verification of revenue and trip counts per company
-	⚠️ Detection of restrictions, inconsistencies and operational discrepancies
> [!NOTE]
> This project was developed under real QA standards, applying critical analysis, structured test design, and technical documentation to simulate a professional workflow.

## 🛠️ Technical Skills
####  Requirements & Technical Analysis
I worked with system information, expected log behavior, database structures, and business rules. Core activities:
-	Identification of critical events and relevant errors
-	Detection of repetitive patterns across IPs, status codes, and routes
-	Critical reading of SQL table structures and relationships
-	Translating operational rules into queries and clear investigations
This enabled precise, data-driven research aligned with system logic.
---
####  QA Foundation Techniques
-	Positive/negative analysis of server events
-	Error-based test partitioning (200, 400, 500)
-	Logical data validation using SQL
-	Scenario-based testing using real system cases
-	Grey-area evaluation (pricing, weather, availability)
-	Failure reproduction via filtered log extraction
These ensured reliable backend and database validation.
---
#### Documentation
Produced clear, well-structured, engineering-ready documentation:
-	Structured investigation directory (bug1/, events/)
-	Segmented error files (400.txt / 500.txt)
-	Cleanly documented SQL queries with expected results
-	Evidence of inconsistencies, patterns, and risk factors
-	Traceability between log events and database outcomes
Every document was created to accelerate diagnosis and decision-making.
---
#### Tools Used
-	`Terminal / Console` — log analysis, recursive search, filtering, extraction
-	`PostgreSQL` — advanced queries for data validation
-	`Google Sheets` — documentation, comparison tables, structured evidence
-	`QA Methodologies` — comparative analysis, iterative documentation
-	`Debugging Techniques` — failure investigation, segmentation and correlation

## ⚙️ Functionalities Validated
####  Server Log Investigation
 ##### Command Line Interface:
-	Reading and filtering thousands of log lines
-	Classifying requests by IP, date, and error type
-	Isolating critical 400 and 500 events
-	Separating errors for dev-ready analysis
##### Functionality Validation:
-	Tracking affected routes
-	Identifying repeated or atypical requests
-	Detecting inconsistent server behavior
-	Supporting reproducible failure diagnosis
---
#### SQL Validation – Data Integrity
Queries confirmed:
-	Taxi availability vs. expected capacity
-	Fleet per company (flagging companies under 100 vehicles)
-	Weather classification by hour to validate fare coefficients
-	Trip counts per company over time ranges
-	Revenue discrepancies based on trip logic
This enabled reliable validation of operational data and business rules.
---
#### Fare & Weather Logic Analysis
Using CASE WHEN, I validated:
-	Correct hourly filters
-	Consistency of “Good” vs “Bad” conditions
-	Impact on price coefficients
-	Logical accuracy before fare calculation
---

####  Trip & Revenue Review
Through SQL queries:
-	Organized data per company
-	Verified actual trip counts
-	Compared results with expected business values
-	Identified relevant operational inconsistencies

## 📦 Skill Set Demonstrated
-	Critical analysis of backend infrastructure
-	Professional log debugging and filtering
-	Technical documentation with traceability
-	SQL-based validation aligned with business rules
-	Clear communication of technical findings
-	Structured evidence and risk identification
-	Understanding of system dependencies

## 🧩 Key Takeaways
-	Transformed raw server data into actionable evidence
-	Detected unexpected behaviors and relevant patterns
-	Built a clear, replicable investigation workflow
-	Documented findings with technical precision
-	Designed SQL queries aligned with real system needs

> [!IMPORTANT]
>All deliverables were built with a focus on traceability, clarity, and maintainability, reflecting the standards used in real QA and engineering teams.

## Conclusion
This project strengthened my capabilities as a Junior QA Engineer by allowing me to investigate real incidents, validate critical backend data, and document findings professionally. It covered backend analysis, log diagnostics, SQL validation, and structured technical reporting—resulting in a comprehensive set of deliverables that showcase critical thinking, technical rigor, and solid QA practices.
##
Thank you for reviewing this project. I am ready to bring this level of technical depth, structured analysis, and QA discipline to real engineering environments.
If you’d like to discuss how I can contribute to your team or projects, feel free to connect through the links below.

Professional Contacts
<div align="left">
  <a href=https://www.linkedin.com/in/maximiliano-fuentes-morales-qa/><img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="32" height="20" alt="linkedin logo"  /></a>
  <a href=https://discordapp.com/users/maximilian_21./><img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/discord/default.svg" width="32" height="20" alt="discord logo"  /></a>
  <a href=maximiliano.fuentes.mor@gmail.com><img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="32" height="20" alt="gmail logo"  />
</div>
    
---

#### Project Materials
<a href="https://docs.google.com/document/d/1n-ucK0q7gfMya9hCtaVdcx10pq64flMr/edit?usp=sharing&ouid=117329030757686447056&rtpof=true&sd=true"> Data Validation & Log Analysis – QA Technical Investigation (Spanish)</a>

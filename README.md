# Joseph Pham - Professional Portfolio
## 📌 About Me  

Hi, I’m Joseph, a Technical Project Manager and Analyst with 6+ years of experience in enterprise system integration, process improvement, and data-driven decision-making. I’ve led cross-functional initiatives at Tesla, focusing on tooling automation, digital workflow optimization, and scalable system design.

I’m passionate about solving complex problems at the intersection of technology and operations. To drive impact, I utilize tools such as SQL, JIRA, Confluence, Gantt, Splunk, Microsoft Office Suite, and Postman. I also apply lean manufacturing principles to streamline processes and improve operational efficiency.

This GitHub showcases some of my professional and exploratory projects in data analytics, system documentation, and process optimization. Let’s connect!

📄[Resume in (PDF)](https://github.com/Teijyn/Professional-Portfolio/blob/main/Joseph_Pham_Resume.docx.pdf)

## 📑 Table of Contents

### 🔍 Query Language
- 📌 [Tesla Manufacturing SQL Query Collection](#tesla-manufacturing-sql-query-collection)
- 📌 [JIRA Agile Project Tracking](#jira-agile-project-tracking)
- 📌 [Confluence Collaborative Documentation](#confluence-collaborative-documentation)

### 🔗 API
- 📌 [Postman API Support for Production Systems](#postman-api-support-for-production-systems)

### 📊 Excel
- 📌 [Excel Interactive Project Timeline Dashboard](#excel-interactive-project-timeline-dashboard)
- 📌 [Excel Interactive Dashboard](#excel-interactive-dashboard)






## 🗂️ Project Portfolio  
A collection of hands-on projects showcasing my experience in data analytics, systems integration, and process improvement. Each project reflects practical, real-world applications and technical problem-solving.

## 📌***Tesla Manufacturing SQL Query Collection***

**Code:**
[Manufacturing Queries](https://github.com/Teijyn/ProjectPortfolio/blob/main/SQL%20Queries.sql)

**Goal:**  To support real-time production data extraction and decision-making through a robust set of SQL queries tailored for manufacturing operations.

**Description:**  This repository features a structured collection of SQL queries developed to monitor, analyze, and improve manufacturing performance in a live production environment. The queries are designed to extract actionable insights related to production output, tooling errors, shift performance, downtime events, and inventory turnover.

**Skills:**  
- Real-time SQL data extraction and reporting  
- Multi-level JOINs and subquery logic  
- Downtime and defect trend analysis  
- Lean manufacturing data analytics  
- Tooling and shift-based performance tracking

**Technology:**  
- MySQL / SQL  
- Live data source simulation  

**Results:**  Enabled timely insights into key production metrics by delivering scalable, production-ready SQL queries. These queries helped identify high-defect trends, optimize resource planning, and support lean initiatives, reflecting hands-on experience with real-time manufacturing systems.


## 📌***JIRA Agile Project Tracking***

***Code:***  [JIRA Queries Code](https://github.com/Teijyn/ProjectPortfolio/blob/main/JIRA%20Queries.jql)

**Goal:**   To manage and track technical projects with precision using JIRA, enabling Agile delivery and real-time visibility across cross-functional teams.

**Description:**  I’ve used JIRA to lead and support enterprise system integrations, tooling deployments, and process improvement initiatives. This includes managing sprint cycles, user stories, issue tracking, and stakeholder alignment throughout the project lifecycle.

**Skills Demonstrated:**  
- Created and managed custom Scrum and Kanban boards  
- Developed and refined epics, user stories, subtasks, and workflows  
- Used advanced JQL queries to build filtered dashboards and reports  
- Facilitated sprint planning, daily stand-ups, and retrospectives  
- Aligned development and operations through ticket tracking and priority workflows

**Technology:**  
- JIRA Software (Cloud and Server)  
- Agile / Scrum frameworks  
- JQL (JIRA Query Language)  
- Integrated tools (e.g., Slack, Confluence)

**Outcome:**  Improved team coordination, reduced sprint carryover, and increased on-time project delivery through effective Agile planning and real-time status tracking.


## 📌***Confluence Collaborative Documentation***

**Goal:**  To create centralized, accessible, and living documentation for technical projects and team processes using Confluence.

**Description:**  I’ve used Confluence extensively to support engineering programs by developing documentation spaces, SOPs, integration plans, and status pages. This ensured clear communication, easy onboarding, and organizational knowledge retention.

**Skills Demonstrated:**  
- Built structured documentation spaces for systems integration and tooling workflows  
- Linked Confluence pages to JIRA tickets for traceable project artifacts  
- Created knowledge bases for internal tools, best practices, and validation steps  
- Designed templates for sprint summaries, project retrospectives, and decision logs  
- Maintained real-time dashboards and updates for leadership and project teams

**Technology:**  
- Atlassian Confluence  
- Confluence-JIRA integration  
- Visual flowcharts, macros, and page templates

**Outcome:**  Streamlined knowledge sharing across teams and improved execution quality by making documentation accessible, consistent, and continuously updated.

## 📌***Postman API Support for Production Systems***

**Goal:**  To validate and troubleshoot API-driven manufacturing processes using Postman, enabling real-time visibility and quick issue resolution on the production floor.

**Description:**  Postman was used in an active manufacturing environment to test, validate, and manage system-level API integrations for production tracking, tooling steps, VIN assignments, and option code updates. While not a backend developer, I managed API interactions necessary to debug system flows, support engineering teams, and resolve production blockers.

**Skills:**  
- Executed and validated REST API calls across multiple systems  
- Used Postman to verify torque tool configuration APIs, MES communication, and event logging endpoints  
- Managed environments and variable sets for different factories, systems, or shift-based tests  
- Interpreted JSON/XML responses to confirm system behavior or flag discrepancies   
- Used environment files to toggle between dev/staging environments  
- Collaborated with system engineers to report malformed payloads or missing step responses
- Authorization flows (Bearer Token, API Key, OAuth 2.0)  
- Collection runner and automated test sequences  
- Mock servers and API documentation sharing

**Technology:**  
- Postman (Collections, Environment Variables, Test Scripts)  
- Tesla MES API endpoints (SparqEX, Cardjob, TaskGroup, VIN Assignment)  
- JSON payload management  
- Token-based authentication    

**Use Case Highlights**  
- ✅ `Move THING` → Simulates a tooling or material movement through a step  
- ✅ `Complete Task` → Records a process step result (e.g., torque value, error code, pass/fail)  
- ✅ `Undo Last Step` → Used to back out tasks when defects or errors are caught  
- ✅ `Assign VIN` → API support for VIN allocation from a part number or process  
- ✅ `Option Code Update` → Modify manufacturing configuration like wheels, brakes, etc.  
- ✅ `Consume Card / Get CardJob` → For verifying process state in the job queue  
- ✅ `Who Created Task` → Traceback to debug bad data, incomplete flows, or mismatched assignments  

**Results:**  By using Postman as a non-developer, I enabled faster support response during production escalations, improved engineering collaboration, and ensured critical APIs were performing as expected on the line.

## 📌***Excel Interactive Project Timeline Dashboard***

***Excel***: [Gantt Chart](https://github.com/Teijyn/ProjectPortfolio/blame/main/Multispindle_Gantt.xlsx)

**Goal**:  To build an interactive Excel-based Gantt chart that visualizes key milestones and task dependencies for tooling installation and validation.

**Description**:  This Excel dashboard tracks a 7-day installation schedule for multispindle torque tool equipment, including tasks like electrical wiring, cement paving, equipment setup, and final testing. Designed to support real-time planning and cross-team visibility.

**Skills Demonstrated**:
-  Developed Gantt charts using dynamic formatting and timeline bars
-  Applied task categorization (Goals, Milestones, Risks) for project clarity
-  Used formulas (IF, TODAY, NETWORKDAYS, CONCAT, etc.) to automate schedule logic
-  Enabled task tracking with conditional formatting and auto-highlighting
-  Created a professional, readable layout optimized for stakeholder review

**Technology**:
-  Microsoft Excel 365
-  Data Validation & Named Ranges
-  PivotTables & Formulas
-  Project Planning Techniques

**Outcome**:  Delivered a project planning tool used by engineering and production teams to coordinate dependencies, monitor risks, and ensure a timely, efficient equipment launch.

## 📌***Excel Interactive Dashboard***

**Excel**: [Tool Repair Expense Tracker](https://github.com/Teijyn/ProjectPortfolio/blob/main/Tool%20Repair%20Expense.xlsx)

**Goal**: To monitor and manage repair costs for various tooling equipment, categorized by sub-category and vendor, ensuring budget alignment and spend transparency.

**Description**: This Excel workbook is structured to track tool repair expenses across multiple categories, including Makita, ESTIC, and Atlas. It captures key data, including tool name, vendor, limit, amount, and date. The tool supports monthly budget reviews and helps identify high-cost repairs or vendors with frequent service needs.

**Skills Demonstrated**:
-  Utilized SUMIFS, AVERAGEIFS, and FILTER formulas for conditional aggregations
-  Applied data validation for consistent sub-category input
-  Built dynamic lookups for vendor-specific cost reporting
-  Created summaries by sub-category and vendor using formula-based calculations
-  Enabled cross-sheet referencing for centralized budget tracking
-  Implemented clear formatting and structured layout for usability

**Technology**:
-  Microsoft Excel 365
-  Data Validation & Named Ranges
-  Conditional Formatting & Formula Logic
-  Basic Expense Reporting Techniques

**Outcome**: Delivered an efficient financial tracking sheet used by operations and purchasing teams to manage tooling repair expenses, optimize vendor choices, and stay within monthly repair budgets.

## 🎓 Education  

**Southern New Hampshire University**  
*Associate of Science – Data Analytics (In Progress)*  
Currently building a strong foundation in statistical analysis, data visualization, and data-driven decision making.

## 🎓 Certifications  
I’m committed to continuous learning and professional growth. Below are a few certifications I’ve earned to strengthen my data analytics and project management skills.

[Google Data Analytics Professional Certificate](https://www.coursera.org/account/accomplishments/specialization/A8D583BN7YSG) (Dec 2024) (Coursera - Google)

[Project Management Certification](https://badgr.com/public/assertions/hvkduB6NQDO-CDFJqoB1PA) (Apr 2024) (Certification - Louisiana State University)


## 📫 Contact  
I love connecting with fellow technologists, recruiters, and collaborators.  
- **Email:** jpham05@Outlook.com  
- **LinkedIn:** [Joseph Pham](https://www.linkedin.com/in/phamjv)  

Feel free to contact me anytime to discuss a project, share ideas, or explore new opportunities.

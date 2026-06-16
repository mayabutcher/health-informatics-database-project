# health-informatics-database-project
Arizona State University Health Informatics Database course group project. Developed a relational Laboratory Information System (LIS) database to support patient management, laboratory operations, specimen tracking, quality assurance, turnaround-time analytics, and reporting using SQL and Microsoft Access.
Database Functionality and User Support
Overview

This database was designed to support the operational workflows of a clinical laboratory information system (LIS) by integrating patient records, laboratory orders, specimens, test catalog information, cancellations, turnaround-time tracking, and reference laboratory processes into a unified relational database. The resulting structure improves data accessibility, workflow efficiency, quality monitoring, and operational oversight across multiple laboratory roles.

Laboratory Staff Support

Laboratory technicians and phlebotomists benefit from streamlined access to daily workloads and specimen tracking. The Today's Laboratory Worklist view automatically aggregates current-day laboratory orders and displays key information such as order priority, status, and specimen collection details.

This functionality helps staff:

Identify pending and uncollected specimens
Prioritize STAT and urgent orders
Monitor specimen receipt status
Reduce manual filtering and record searches

By centralizing daily laboratory activities, the worklist improves workflow efficiency and visibility across departments.

Test Management and Supervisory Support

Supervisors and test management personnel require timely insight into aging orders and operational bottlenecks. The Pending Orders Over 72 Hours view isolates orders that exceed established processing thresholds and presents relevant details including:

Order age in hours
Priority level
Recollectable status
Patient information
Current order status

This targeted view reduces time spent reviewing active orders and allows management to focus on records requiring immediate attention.

The Cancellation Audit view further supports quality assurance by consolidating cancellation activity across orders, users, departments, and documented cancellation reasons. This enables supervisors to evaluate:

Cancellation trends
User compliance with documentation requirements
Time elapsed between order placement and cancellation
Completion status of cancellation records

These insights support competency assessment, regulatory compliance, and continuous quality improvement initiatives.

STAT Order Monitoring and Performance Analysis

STAT testing requires rapid turnaround and close performance monitoring. The STAT Turnaround Time Summary view centralizes critical performance metrics by combining data from Orders, TurnaroundTimeRecord, PriorityType, TestCatalog, and Patient tables.

The view provides:

Test start and completion timestamps
Calculated turnaround times (TAT)
Target TAT thresholds
Goal attainment indicators
Patient and test context

This standardized reporting structure enables supervisors to generate daily, weekly, and monthly performance reports without relying on manual calculations.

Reference Laboratory Management

Send-out testing workflows are supported through the Reference Lab Turnaround Time view, which tracks:

Specimen dispatch dates
Result receipt dates
Outstanding pending send-outs
Calculated external laboratory turnaround times

This functionality improves visibility into reference laboratory performance, helps identify delays, and provides management with data for vendor evaluation and follow-up activities. Patient and ordering department context further supports communication with providers regarding delayed or pending results.

Data Integrity and Quality Assurance

The database enforces referential integrity through foreign key relationships that ensure all orders, specimens, tests, and cancellations reference valid patients, users, departments, and test catalog entries.

Additional data quality measures include:

Standardized lookup tables for status values, user roles, and departments
Reduced risk of inconsistent data entry
Improved record accuracy and completeness
Enhanced reliability for reporting and analytics

These controls help maintain a consistent and trustworthy dataset suitable for operational reporting and decision-making.

Project Impact

By consolidating multiple laboratory workflows into a single relational database, this project improves operational efficiency, supports quality management initiatives, enhances data integrity, and provides actionable reporting tools for laboratory personnel, supervisors, and administrators. The resulting system reflects real-world laboratory information system requirements and demonstrates practical applications of relational database design, SQL querying, workflow automation, and healthcare data management.

Team Contributions

This project was completed as a group assignment for Arizona State University's Health Informatics Database course. Team members included Andrea Jimenez, Aisha Evering, Nathalie Garcia, and Maya Butcher.

The team collaboratively developed the project background, domain analysis, stakeholder interviews, mission statement, entity list, attribute definitions, and entity relationship diagram (ERD). My primary contributions included developing and implementing the SQL code used to create the database in Microsoft Access, performing database quality review and validation, and assembling the final project report and deliverables.


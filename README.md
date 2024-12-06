# Inventory Management System (IMS)

## Overview
The Inventory Management System (IMS) is a robust and scalable database solution designed for efficient inventory tracking and management. Built on SQL Server 2016, the system leverages modern database tools and technologies to provide seamless integration, data analytics, and reporting capabilities. Whether you're managing a small warehouse or a large supply chain, IMS is tailored to optimize your inventory operations.

<br>

## Features
- Inventory Tracking: Real-time monitoring of inventory levels, incoming shipments, and outgoing orders.
- Automated Data Integration: Efficient ETL (Extract, Transform, Load) processes using SQL Server Integration Services (SSIS).
- Comprehensive Reporting: Customized, visually appealing reports using SQL Server Reporting Services (SSRS).
- Performance Optimization: Advanced queries and stored procedures designed with T-SQL for optimal database performance.
- Security: Implements role-based access control and encryption for sensitive data.

<br>

## Tools & Technologies
- T-SQL (Transact-SQL):
Core scripting language for database development and management tasks. Used for:
  - Writing complex queries, views, and stored procedures.
  - Implementing business logic within the database.
  - Performance tuning through indexing and query optimization.

- SQL Server 2016:
The backbone of IMS, providing:
  - Enhanced security features such as Always Encrypted and Row-Level Security.
  - High availability through features like Always On Availability Groups.
  - Built-in advanced analytics and reporting capabilities.

- SSIS (SQL Server Integration Services):
  - Automates ETL processes for importing and exporting inventory data.
  - Ensures data consistency by integrating data from multiple sources.
  - Scheduled data workflows for real-time data synchronization.

- SSRS (SQL Server Reporting Services):
  - Generates detailed inventory reports, including stock summaries, sales trends, and restock alerts.
  - Exports reports in multiple formats like PDF, Excel, and HTML for stakeholder use.
  - Configurable dashboards for at-a-glance monitoring of inventory metrics.

<br>

## Installation & Setup
1. Prerequisites:
    - Windows Server or compatible OS for SQL Server 2016.
    - SQL Server Management Studio (SSMS) for database management.
    - Optional: Visual Studio with SSIS/SSRS extensions for development.

2. Database Deployment:
    - Restore the provided database backup file (IMS_Backup.bak) to SQL Server 2016.
    - Configure database settings, including permissions and encryption keys.

3. ETL Configuration (SSIS):
    - Import SSIS package files (`IMS_ETL_Package.dtsx`) into SQL Server Data Tools (SSDT).
    - Update connection strings to match your environment.

4. Reporting Setup (SSRS):
    - Deploy the SSRS report files (IMS_Reports.rdl) to the SSRS server.
    - Configure report subscriptions and delivery settings.

5. Testing & Verification:
    - Run the provided test scripts to validate database integrity and functionality.
    - Verify ETL processes and ensure proper data flow between systems.
    - Review sample reports for accuracy and completeness.

<br>

## Usage
- Day-to-Day Operations:
  - Use the IMS dashboard to monitor inventory levels, restocking needs, and sales trends.
  - Schedule daily/weekly reports to keep stakeholders informed.

- Data Integration:
  - Automate data imports from external systems using pre-configured SSIS packages.

- Advanced Reporting:
  - Leverage SSRS to customize and drill down into specific inventory metrics.

<br>

## Contact
For questions, support, or feature requests, please contact:

Database Administrator
Chaanyah Laborde
chaanyahlaborde@gmail.com
[[LinkedIn Profile]](https://www.linkedin.com/in/claborde/)

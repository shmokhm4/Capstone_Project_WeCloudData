# WeCloudData - Capstone Project
As participants in the Data Management & Governance Bootcamp, we undertook the role of data specialists to enhance the efficiency and analytical capabilities of a Learning Management System (LMS).
## STAGE 1
### Project Overview:
This project tackled key challenges such as the lack of automated reporting, unstructured data governance, and heavy reliance on manual processes for student registration and content management.

#### Phase 1: Data Integration & Exploration
We established a structured data framework by configuring a MySQL database to systematically store and manage LMS-related data. This involved importing and validating datasets from CSV and TSV files to ensure data accuracy and consistency. Additionally, we conducted data profiling using SQL to analyze record distributions, detect anomalies, and assess data completeness.

#### Phase 2: Analytics & Reporting
To provide actionable insights, we developed interactive reports and dashboards using Power BI and Excel. These visualizations enabled key stakeholders to monitor student attendance, withdrawal rates, and course completion trends, facilitating data-driven decision-making.

![Screenshot 2025-03-16 130249](https://github.com/user-attachments/assets/20a04b68-4c1f-4114-a794-36f3a9b0fc36)
![Screenshot 2025-03-16 130236](https://github.com/user-attachments/assets/8a99452d-b6fb-4f00-8115-8be9b7af1f20)
![Screenshot 2025-03-16 130221](https://github.com/user-attachments/assets/e40e32ba-5a11-4be1-8491-c706765b1fbb)

## STAGE 2
### Project Overview:
In Stage 2, we transitioned from a local setup to a cloud-native data environment, focusing on integrating diverse data sources and applying best practices in data governance. This phase emphasized data quality, security, privacy, and scalability while aligning with the DAMA Data Management Body of Knowledge (DAMA-DMBOK) standards to generate business-ready insights and ensure operational efficiency.

#### Phase 1: Cloud Integration & Centralized Storage
- **Setup**: Deployed a centralized cloud-based MySQL RDS environment for scalable data storage.  
- **Data Sources Integrated**:  
  - MySQL Local (Stage 1 LMS data)  
  - PostgreSQL (lms_raw schema)  
  - Attendance CSV datasets (bootcamp client records)  
- **Schema Design**: Ensured referential integrity and schema alignment across sources. 

#### Phase 2: Data Optimization, Transformation & Reporting  
- **Data Profiling**:  
  - Assessed raw data for completeness, uniqueness, nulls, and outliers.  
  - Conducted post-cleaning profiling to validate quality improvements.  
- **Data Transformation**:  
  - Applied formatting standards (e.g., dates, emails, casing).  
  - Removed duplicates and enforced consistency rules.  
  - Masked sensitive PII fields (e.g., student emails) to meet compliance.  
- **Optimization**:  
  - Used indexes, views, and query optimization for performance gains.  
  - Created normalized and analytical tables for downstream use.  
- **Data Governance**:  
  - Documented metadata, source-to-target lineage, and master/reference data.  
  - Logged quality issues and showcased “before vs. after” improvements.  
- **Analytics & Visualization**:  
  - Built dashboards using Power BI and Excel for ad-hoc and real-time reporting.  
  - Delivered a CEO-focused report on attendance trends, filtered by month and level.


# Power-BI--Hospital-Analysis-Dashboard

1.  Project Title-
Hospital Performance Dashboard:
A dynamic, role-based Power BI dashboard designed to streamline and visualize critical operations of a hospital—including patient care, doctor performance, medicine inventory, finance, and hospital-wide KPIs.

2.  Purpose-
Hospital Analytics Dashboard is a modern, interactive Power BI solution that delivers operational visibility and role-specific insights across hospital departments. This dashboard enables secure, tailored views for doctors, patients, finance officers, and administrators using Row-Level Security (RLS). The dashboard is built to support data-driven healthcare decisions, improve resource management, and enhance patient care quality.

3.  Tech Stack-
The dashboard was built using the following tools and technologies:
- 📊 Power BI Desktop – For building interactive visual dashboards and report pages.
- 📂 Power Query – Used to clean, transform, and shape data before loading it into the model.
- 🧠 DAX (Data Analysis Expressions) – For creating calculated columns, measures, and implementing dynamic user-specific logic.
- 📝 Data Modeling – Designed using a star schema with well-defined relationships across tables like patients, doctors, appointments, finance, and medicine stock.
- 🔐 Row-Level Security (RLS) – Enables secure, role-specific data access so users see only relevant information.
- 🗃️ SQL (Structured Query Language) – Used to extract and query hospital data from the relational database before importing it into Power BI.
- 📁 File Format – .pbix for development and .png for dashboard previews.

4. Data Source-

--a. Source: Simulated and anonymized hospital data collected from Kaggle and curated to represent real-world healthcare operations and domains. This dataset was originally sourced from Kaggle and enriched to include key entities across a typical hospital management system.

--b. Data Tables Included:
- Patients: Demographic details, assigned doctors, diagnosis records, and treatment plans.
- Doctors: Doctor names, departments, consultation counts, earnings, and number of patients handled.
- Appointments: Scheduling data including doctor-patient linkage, visit dates, status (attended/cancelled), and purpose of visit.
- Medicine Stock: Details on available inventory, supplier names, medicine categories, stock quantities, and purchase costs.
- Finance: Billing amounts, service charges, total revenue, and monthly financial trends.
- Surgeries: Surgery types, departments, and distribution across different patient age groups.

5. Features-
   
--a. Business Problem: Hospitals often struggle with managing diverse operational data scattered across departments—leading to inefficiencies in decision-making, reporting delays, lack   of personalized insights, and data privacy issues. Key stakeholders (e.g., doctors, patients, finance staff) need tailored access, yet traditional systems offer one-size-fits-all reports.

b. Goal of the Dashboard:
- To build a secure, role-specific, interactive dashboard that:
- Gives doctors access to only their patients and performance metrics.
- Lets patients view only their data.
- Provides the finance team with full visibility into billing, charges, and inventory.
- Equips hospital management with a unified view of KPIs, resource allocation, and performance trends.

c. Walkthrough of Key Visuals:
- Overview Dashboard
KPIs like: Total Patients, Doctors, Appointments, Revenue.
Cards, gauges, and bar charts showing hospital-wide stats.
- Patient Dashboard
Detailed patient cards with medical info.
Gender and age-wise distribution.
Doctor assigned & treatment history.

- Doctor Dashboard
Earnings, appointments count, ratings.
Top-performing doctors based on patient volume.
Doctor-patient linkage table for analysis.

- Hospital Dashboard
Age group vs. surgery type analysis.
Appointments by department and time.
Dynamic slicers for department/doctor filtering.

- Finance Dashboard
Total billing and monthly revenue trends.
Charges per patient and medicine expense breakdown.
Stock details and supplier-wise cost tracking.

d. Business Impact & Insights:
Improved Decision-Making: Real-time access to hospital KPIs enables faster, evidence-based decisions.
Data Privacy & Security: Implemented Row-Level Security (RLS) ensures sensitive data is protected and only visible to authorized users.
Operational Efficiency: Helps management track appointments, surgeries, and stock levels proactively.

e. User-Specific Insights:
Doctors can monitor their performance and patient load.
Finance can track revenue, spending, and cost optimization opportunities.
Patients can transparently view their health journey.
Strategic Planning: Identify trends across departments and patient demographics for long-term planning.

6. Screenshot: 
(https://github.com/prateekrastogi23/Power-BI---Hospital-Analysis-Dashboard/blob/main/Snapshot%20of%20Hospital%20Dashboard%20.png)




# Bangalore-pet-hospital-analytics
An end-to-end Data Analytics project analyzing operations of a pet hospital chain in Bangalore. This project covers the complete DA workflow — from raw data creation, SQL analysis, to an interactive Power BI dashboard.
Tools Used

SQL (SQLite) — Data storage and analysis
DB Browser for SQLite — Writing and running SQL queries
Power BI Desktop — Interactive dashboard and visualizations

Dataset
Self-created realistic dataset simulating a Bangalore pet hospital with:
TableRecordsDescriptionowners150Pet owners across Bangalore areaspatients200Pets (dogs, cats, rabbits, parrots etc.)doctors6Doctors with specializationstreatments14Treatments with pricesvisits600Hospital visits (2023-2024)
SQL Analysis
Key queries written to extract business insights:

Pet type distribution across patients
Area wise pet owner count across Bangalore
Doctor wise patient load
Monthly revenue trend
Top treatments by revenue
Most common treatments

Dashboard Features
Interactive Power BI dashboard with:

📊 4 KPI Cards — Total Revenue, Total Visits, Total Patients, Avg Revenue per Visit
🍩 Donut Chart — Pet type distribution
📊 Bar Chart — Pet owners by Bangalore area
📈 Line Chart — Monthly revenue trend (2023-2024)
🌳 Treemap — Most common treatments
🥧 Pie Chart — Payment mode distribution (Cash, UPI, Card, Net Banking)
📊 Bar Chart — Doctor wise patient load
🎛️ Slicers — Filter by Pet Type and Date Range

Key Insights

🐶 Dogs are the most common pets (43.5% of patients)
🏙️ Yelahanka has the highest number of pet owners in Bangalore
💰 Major Surgery and Emergency Care generate the highest revenue
👩‍⚕️ Dr. Sunita Nair handles the highest patient load
💳 UPI is the most popular payment mode

Files

PET_Hospital.pbix — Power BI Dashboard file
pet_hospital_bangalore.db — SQLite database
pet_hospital_queries.sql — All SQL queries used in analysis
visits.csv, patients.csv, owners.csv, doctors.csv, treatments.csv — Raw data files

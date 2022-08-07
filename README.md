# Cancer_ETL
The technological architecture of our business analytics and decision-making project, as represented  , is based on two layers (2-tier architecture) with a bottom-up approach and where 2 data-marts are considered (despite being installed on the same repository):
•	bottom-tier (back-end) – represented by the data warehouse server, which uses a MySQL database management system, and where the multidimensional database schema (constellation schema) called “nhs_cancer” is installed. , where we have two non-independent data-marts, where one deals with records of cancer diagnoses and the other deals with records of questionnaires made to cancer patients;
•	top-tier (front-end) – represented by the business analytics tool (Tableau) that will allow you to read and prepare the data contained in the data warehouse for visualization in dashboards.




# Data source
As data sources were considered 4 files in csv format. Two of them represent datasets with business information (sevenCancers and NCPES_Wave1), and the other two (ICDO_Codes and QA_Waves1) were created as sources to support data transformation and compliance tasks during the ETL process.

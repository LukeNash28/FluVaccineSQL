# SQL Queries on Synthea Healthcare Data
*This project was adapted from the DataWizardry SQL course on YouTube.* 

The `Healthcare script.sql` file contains the script used to create the tables and the query for extracting the data, which is contained in the CSV file.

The data used to populate the tables can be accessed via Josh Matlock's [DataWizardry website][data].

A Tableau visualisation was constructed from this data, and you can view it via this link: https://public.tableau.com/app/profile/luke.nash/viz/FluVaccinationDashboard/Dashboard1.

It is worth noting:
- The data for this project was generated via [Synthea][Synthea], an open-source project that generates realistic but synthetic patient data so analytics could be performed on patient data in a database similar to that of a hospital without violating data protection or patient confidentiality laws.
- Synthea does ordinarily use SNOMED vocabulary in the original data, but to avoid SNOMED users in some countries needing to pay a fee for this data, Josh from DataWizardry replaced the SNOMED codes with ICD-9 codes, which are public domain. To read more about SNOMED in the UK, visit the [NHS website][SNOMED]. 

[//]: #
[data]: [https://datawizardry.academy/sql-basics-healthcare/]
[Synthea]: [https://synthea.mitre.org/about]
[SNOMED]: [https://www.england.nhs.uk/digitaltechnology/digital-primary-care/snomed-ct/]

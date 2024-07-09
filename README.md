# tokyo-olympic-azure-data-engineering-project



Data Description:

For this project, I will be working with the 2021 Olympics dataset. This includes the information on more than 11,000 athletes competing in 47 sports for 743 Teams in the Tokyo Olympics in 2021. This dataset includes information on the participating Teams, Athletes, Coaches, and Entries by gender. It includes their names, nationalities, sports they compete in, and name of coaches. The dataset contains 5 files as follows:

Athletes file (Details about Athletes):

Name

NOC

Discipline

 

Coaches file (Details about coaches, countries and disciplines along with event):

Name

NOC

Discipline

Event

 

EntriesGender file (Details about the Discipline and the number of females and males participating):

Discipline

Male

Female

Total

 

Medals file (Contains the Medals and Scoreboard of countries that participated in Olympics):

Rank

Team/NOC

Gold

Silver

Bronze

Total

Rank by Total




Teams file (Details about the Teams, discipline, Name of Country and the event):

Name

Discipline

NOC

Event

 

Tech Stack:

Language: SQL

Services: Azure Synapse Analytics, Azure Storage, Azure Synapse SQL Pool, Power BI
 

Approach:

Create an azure storage account and upload data files in a container.

Create an azure synapse analytics workspace.

Create a SQL pool in azure synapse workspace.

Create table structure in SQL pool.

Create a data pipeline to ingest data from azure storage into SQL pool tables.

Load data from SQL pool tables into Power BI.

Prepare dashboard in Power BI.

Publish Power BI dashboard in Azure synapse workspace.

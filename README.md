# USA Real Estate Information Database project
This project is designed to build a database for the real estate market in the States, so it can extract more features when predicting the future. This repository is created for a group coursework project with a team of 5 UCL MSBA students.

**Keywords:** database, SQL, MongoDB, DuckDB, spark, pandas

## Database Structure
Our database structure contains microscopic and macroscopic data about US estates.  In macroscopic scope, we provide economic situation, interest rate, and the index concering US real estates.
![House pirce database schema](https://github.com/pingfanc/US_Real_Estates_Market/assets/99853020/ab9464d7-f3c0-424f-bf6b-e026431d38ae)

The database can be maintained easily and efficiently by linking the state-focus and city-focus tables together, enhancing data integrity. Moreover, users can query more complex commands and understand the data structure more easily. Although the macroscopic tables are not linked with other tables, users can still access and query them from the database. Therefore, this database provides comprehensive information about the US economy and the real estate market and helps users access those data efficiently.

## Data Acquisition
There are three different types of data resources which come from API, web scraping, and Excel documents. These data are first stored in Postgres and MongoDB (OLTP database), then transformed into DuckDB for further analysis as it is an OLAP database. 

## Future steps
- Build it into the automation pipeline with AWS


# MyNotes-Struts-Hibernate
A simple web application that allows users to store their notes online. This project is built using Struts2 and Hibernate. It uses DAO's
(Data Access Objects) which talk to database using Hibernate.

Steps to Run:

->Import the project into eclipse.
->Add all the struts jars along with ojdbc6(Oracle jar). Include Hibernate Jars. All these need to be done manually since maven is not 
used in this project.
->Create mynotes account with password mynotes in Oracle11g Express Edition. This must be done after you log in as SYSTEM user. 
Then create tables and sequences in mynotes account. These commands are also present in tables.sql file in  project source code.
->Run loginOpt to get login page.

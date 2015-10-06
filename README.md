# MySQL-first-aid

A guide on installation of MySQL.

MySQL is a relational database managmenet software package.
It is an excellent method of quickly and efficiently labeling, changing and managing databases and data tables. 

*tmp
 obtain mysql from http://dev.mysql.com/ according to your own platform
 
## Post Installation 
Post-Installation includes
1. Initializing the Data Tables:

Data tables need to be initialized, follow the following guide: 
https://dev.mysql.com/doc/refman/5.7/en/data-directory-initialization.html

- before initialization, it is important that all directories in BASEDIR are owned by mysql user
- to do this execute the command: sudo chmod  775 data/
Understanding mysqld:
https://dev.mysql.com/doc/refman/5.7/en/mysqld.html

if you get a copy of MySQL 5.7.6 or higher you do not need to execute mysql_install_db
to initialize the MySQL installation, run mysqld (found in mysql/bin) 


--> after finishing installation: go to System Preferences (if you're running Mac OSX) and turn on the server















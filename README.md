# Hospital Database System 🏥
A Flask web application for a hospital database system. 
CS 432: Databases assignment, IIT Gandhinagar.

# Table of Contents

**[Explanations](#explanations-)**<br>
**[Files](#files-)**<br>
**[Requirements](#requirements-)**<br>
**[Instructions to run the web app](#instructions-to-run-the-web-app-)**<br>
**[Examples for each command](#examples-for-each-command-)**<br>
**[Contributors](#contributors-%EF%B8%8F)**<br>   

# Explanations 📰

## Task 1

## Task 2

## Task 3

## Task 4
For this task, we used date of discharge in the patient columnn to search for a particular date.
To optimize the query, we added an index on the column, which reduced the execution time to 10% and 
reduced the number of scans from 10% of the complete table to just 191 output rows. 
![before using index](.\images\q4\before_idx.jpg)
![after using index](.\images\q4\after_idx.jpg)
![execution time comparsion](.\images\q4\exec_time.jpeg)
![]()



## Task 5

## Task 6

## Task 7

## Task 8


# Files 📁

* [`contributions.txt`](https://github.com/frank-chris/HospitalDatabaseSystemV2/blob/main/contributions.txt)    
* [`hospitalDB.sql`](https://github.com/frank-chris/HospitalDatabaseSystemV2/blob/main/hospitalDB.sql)   
* [`README.pdf`](https://github.com/frank-chris/HospitalDatabaseSystemV2/blob/main/README.pdf)   
  
# Requirements ⚡
1) MySQL
2) Python 3
3) MySQLdb
4) Flask
5) Flask-MySQLdb

# Instructions to run the web app ⏩

## Install the following packages
```
pip install mysqlclient/ apt-get install python3-mysqldb
```
```
pip install Flask
```
```
pip install Flask-MySQLdb
```

## Import hospitalDB.sql (dump file) to MySQL as a database named hospitalDB

```
mysql -u tempuser -p hospitalDB < hospitalDB.sql
```

## Create a MySQL user as follows

```
CREATE USER 'tempuser'@'localhost' IDENTIFIED BY '123+Temppass';
```

## Grant permission to the account

```
GRANT ALL PRIVILEGES ON hospitalDB.* TO 'tempuser'@'localhost';
```

## Run the web app

```
python3 web_app.py
```

# Examples for each command ⭐

## Home Page
![](images/homepage.png)

## Pick Table
![](images/list_of_tables.png)

## Describe Table
![](images/describe_table.png)

## View Table
![](images/view_table.png)

## Insert Entry
![](images/insert_table.png)

## Insert Successful
![](images/insert_successful.png)

## Pick entry for updation
![](images/update_table.png)

## Update Entry
![](images/update_entry.png)

## Update Successful
![](images/update_successful.png)

## Delete Entry
![](images/delete.png)

## Delete Successful
![](images/delete_successful.png)

# Contributors ✏️

### TEAM G1

* Amey Kulkarni (18110016)

* Chris Francis (18110041)

* Eshan Gujarathi (19110082)

* Hitarth Gandhi (19110087)

### TEAM G2

* Hrushti Naik (19110088)

* Shril Mody (18110162)

* Viraj Shah (18110188)

* Vishal Soni (19110207)

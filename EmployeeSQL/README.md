# Pewlett Hackard 1980s-1990s Employee Database Project
By Kiana Navarre

**Programming Language Used: PostgreSQL**

## Description
In this project, the company Pewlett Hackard (a fictional company) wants to examine the employee data from the 1980s-1990s gathered in a list of csv files.  This project is divided into 3 sections: 
1. Data Modeling
2. Data Engineering 
3. Data Analysis

## Data Modeling
![alt text](https://github.com/knavarre/sql-challenge/blob/main/EmployeeSQL/sql-challenge_ERD.png?raw=true)
The above Enitity Relationship Diagram depicts the relationship between the csv files used for this project.  Each csv file is represented as a seperate table in the ERD.  

## Data Engineering
The schemata file (sql-challenge_schemata.sql) creates tables for each csv file and defines the relationships between the tables.  

After creating the tables in the database by running the schemata.sql file, upload the CSV files in the following order: 
1. departments.csv
2. titles.csv
3. employees.csv
4. dept_manager.csv
5. dept_emp.csv
6. salaries.csv

## Data Analysis
The following lists were created using SQL to query the created tables:  
- employee number, last name, first name, sex, and salary of each employee
-  first name, last name, and hire date for the employees who were hired in 1986
-  manager of each department along with their department number, department name, employee number, last name, and first name
-  department number for each employee along with that employee’s employee number, last name, first name, and department name
-  first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B
-  each employee in the Sales department, including their employee number, last name, and first name
-  each employee in the Sales and Development departments, including their employee number, last name, first name, and department name
-  the frequency counts, in descending order, of all the employee last names
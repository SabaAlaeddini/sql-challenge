# sql-challenge
Module 9 Challenge

# Overview
This Challenge is divided into three parts: data modeling, data engineering, and data analysis.

# Data Modeling
The six CSV files for the project is downloaded from "Module 9 Challenge files" and stored in "data" folder
In this part, “https://www.quickdatabasediagrams.com/" is used for an Entity Relationship Diagram of the requiered tables. The output is in the EmployeesSQL folder, saved as QuickDBD-Free Diagram.

# Data Engineering
By following the instructions, table schema is created for each of the six csv files. Each of the tables include a primary key, foreign keys, composite key (when necessary), datatype and other constraints. After creating the tables, the csv files is imported into its corresponding SQL table, then each of the tables output is saved in to the EmployeesSQL folder.

# Data Analysis
The data_analysis_queries is written in order to answer the requested data anayisis:

List the employee number, last name, first name, sex, and salary of each employee.

List the first name, last name, and hire date for the employees who were hired in 1986.

List the manager of each department along with their department number, department name, employee number, last name, and first name.

List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

List each employee in the Sales department, including their employee number, last name, and first name.

List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
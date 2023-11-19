# sql-challenge


## Data Modeling
Created a Entity Relationship Diagram of the tables using QuickDBD: https://app.quickdatabasediagrams.com/#/

    ### File: QuickDBD-export.png and QuickDBD-export.sql


## Data Engineering
- Created the Database in PostGreSQL
- Created tables for each CSV file in the EmployeeSQL database
- Imported the CSV data into each table

    
    ### File: EmployeeSQL database and data folder with the following CSVx
    - departments.csv
    - t_emp.csv
    - dept_manager.csv
    - employees.csv
    - salaries.csv
    - titles.csv


## Data Analysis
Performed the following analysis
  1. Employee Details and Salaries: This query lists the employee number, last name, first name, sex, and salary of each employee.
  
  2. Employees Hired in 1986: This query retrieves the first name, last name, and hire date of all employees who were hired in the year 1986.
  
  3. Department Managers: This query lists the managers of each department, along with their department number, department name, employee number, last name, and first name.
  
  4. Employee Department Details: This query provides the department number for each employee, along with their employee number, last name, first name, and the name of their department.
  
  5. Employees Named Hercules B: This query lists the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
  
  6. Employees in Sales Department: This query identifies each employee working in the Sales department, including their employee number, last name, and first name.
  
  7. Employees in Sales and Development Departments: This query lists all employees in both the Sales and Development departments, including their employee number, last name, first name, and department name.
  
  8. Frequency of Employee Last Names: This query provides a frequency count of all employee last names in descending order, indicating how many employees share each last name.


    ### File: EmployeeSQL.sql for all the queries and analysis

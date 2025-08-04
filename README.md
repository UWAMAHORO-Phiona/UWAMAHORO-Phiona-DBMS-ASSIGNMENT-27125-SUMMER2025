# UWAMAHORO-Phiona-DBMS-ASSIGNMENT-27125-SUMMER2025

- Names: UWAMAHORO Phiona
- ID:27125
- Date:03/08/2025
- DBMS ASSINMENT 1

Exercises:
Database Setup:
Description: Set up the database company_phiona_uwamahoro, create tables (DEPARTMENTS, EMPLOYEES, PROJECTS, EMPLOYEE_PROJECTS), insert case study data, and add required columns for exercises 8, 22, and 23.
Database Creation:
 <img width="940" height="129" alt="image" src="https://github.com/user-attachments/assets/0ce098b6-def5-4abd-bced-5264c306ba7f" />


CREATION OF TABLES
TABLE DEPARTMENTS:
 
TABLE EMPLOYEES:
 

TABLE PROJECTS:
 
TABLE EMPLOYEE_PROJECTS:

 

INSERTING DATA
INSERT INTO DEPARTMENTS:
 


INSERT INTO EMPLOYEES:

 
INSERT INTO PROJECTS:
 
INSERT INTO EMPLOYEE_PROJECTS:
 

ADD REQUIRED COLUMNS
ALTER TABLE EMPLOYEES:
 

 


 


String Function Exercises (15)
1.	Concatenate first and last name as full_name.
 

2.	Convert all employee names to lowercase.

 

3.	Extract first 3 letters of the employee's first name.
 
4.	Replace '@company.com' in email with '@org.com'.
 
5.	Trim spaces from a padded string.
 
6.	Count characters in an employee’s full name.
 
7.	Find position of '@' in email using INSTR()/CHARINDEX().
 
8.	Add ‘Mr.’ or ‘Ms.’ before names based on gender (assume gender exists).
 
9.	Format project names to uppercase.
 
10.	Remove any dashes from project names.
 
11.	Create a label like “Emp: John Doe (HR)”.
 
12.	Check email length for each employee.
 
13.	Extract last name only from email (before @).
 
14.	Format: “LASTNAME, Firstname” using UPPER and CONCAT.
 
15.	Add “(Active)” next to employee names who have current projects.
 

Numeric Function Exercises (10)
16.	Round salary to the nearest whole number.
 
17.	Show only even salaries using MOD.
 
18.	Show difference between two project end/start dates using DATEDIFF.
 
19.	Show absolute difference in salaries between two employees.
 
 
20.	Raise salary by 10% using POWER.
 
21.	Generate a random number for testing IDs.
 
22.	Use CEIL and FLOOR on a floating salary.
 
23.	Use LENGTH() on phone numbers (assume column exists).
 
24.	Categorize salary: High/Medium/Low using CASE.
 
25.	Count digits in salary amount.
 

Date/Time Function Exercises (10)

26.	Show today’s date using CURRENT_DATE.
 
27.	Calculate how many days an employee has worked.
 
28.	Show employees hired in the current year.
 
29.	Display current date and time using NOW().
 
30.	Extract the year, month, and day from hire_date.
 
31.	Show employees hired before 2020.
 
32.	List projects that ended in the last 30 days.
 
33.	Calculate total days between project start and end dates.
 
34.	Format date: ‘2025-07-23’ to ‘July 23, 2025’ (use CONCAT).
 
35.	Add a CASE: if project still active (end_date IS NULL), show ‘Ongoing’.
 

Conditional Function Exercises (15)

36.	Use CASE to label salaries.
 
37.	Use COALESCE to show ‘No Email’ if email is NULL.
 
38.	CASE: If hire_date < 2015, mark as ‘Veteran’.
 
39.	If salary is NULL, default it to 3000 using COALESCE.
 
40.	CASE: Categorize departments (IT, HR, Other).
 
41.	CASE: If employee has no project, mark as ‘Unassigned’.
 
42.	CASE: Show tax band based on salary.
 
43.	Use nested CASE to label project duration.
 
44.	Use CASE with MOD to show even/odd salary IDs.
 
45.	Combine COALESCE + CONCAT for fallback names.
 
46.	CASE with LENGTH(): if name length > 10, label “Long Name”.
 
47.	CASE + UPPER(): if email has ‘TEST’, mark as dummy account.
 
48.	CASE: Show seniority based on hire year (e.g., Junior/Senior).
 
49.	Use CASE to determine salary increment range.
 
50.	Use CASE with CURDATE() to determine anniversary month.
 

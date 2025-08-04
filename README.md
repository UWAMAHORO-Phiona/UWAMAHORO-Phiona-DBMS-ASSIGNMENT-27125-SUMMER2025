
- Names: UWAMAHORO Phiona
- ID:27125
- Date:03/08/2025
  
  # DBMS ASSINMENT 1

## Exercises:

## Database Setup:

## Description: 

Set up the database company_phiona_uwamahoro, create tables (DEPARTMENTS, EMPLOYEES, PROJECTS, EMPLOYEE_PROJECTS), insert case study data, and add required columns for exercises 8, 22, and 23.
Database Creation:

 <img width="940" height="129" alt="image" src="https://github.com/user-attachments/assets/0ce098b6-def5-4abd-bced-5264c306ba7f" />


# CREATION OF TABLES
TABLE DEPARTMENTS:
 <img width="940" height="206" alt="image" src="https://github.com/user-attachments/assets/37df0469-5cea-4a70-b46a-f4c907d10a89" />

TABLE EMPLOYEES:
 
<img width="940" height="295" alt="image" src="https://github.com/user-attachments/assets/92b005bd-dca8-411d-bb75-c9409235e2b6" />

TABLE PROJECTS:
<img width="895" height="254" alt="image" src="https://github.com/user-attachments/assets/6367cde4-5d39-4b40-bf60-4c470212683f" />


TABLE EMPLOYEE_PROJECTS:
<img width="940" height="241" alt="image" src="https://github.com/user-attachments/assets/2079cc8f-0a15-42b3-8201-24a03b779afb" />

 

# INSERTING DATA
INSERT INTO DEPARTMENTS:
 
<img width="940" height="241" alt="image" src="https://github.com/user-attachments/assets/e34a6e89-d555-4536-af43-2e35175979fd" />


INSERT INTO EMPLOYEES:

 <img width="981" height="276" alt="image" src="https://github.com/user-attachments/assets/e7096d12-b624-4fe5-af4c-f65d072918e6" />

INSERT INTO PROJECTS:
 <img width="940" height="213" alt="image" src="https://github.com/user-attachments/assets/f82a645d-5a9f-4656-bb0c-75f4b13a548b" />

INSERT INTO EMPLOYEE_PROJECTS:
 
<img width="940" height="118" alt="image" src="https://github.com/user-attachments/assets/b6cb50fe-011d-4bde-a996-8653061bcec5" />

ADD REQUIRED COLUMNS
ALTER TABLE EMPLOYEES:
 
<img width="940" height="221" alt="image" src="https://github.com/user-attachments/assets/08a70f48-2e4c-4b70-8a8b-14c81a467ea2" />

 
<img width="940" height="373" alt="image" src="https://github.com/user-attachments/assets/1dc5f984-0ffd-443a-8246-24b7843d00a2" />


 <img width="940" height="129" alt="image" src="https://github.com/user-attachments/assets/491b9908-b3d0-4939-83c7-4cf61fd5e036" />



# STRING FUNCTION EXERCISES (15)
1.	Concatenate first and last name as full_name.
 <img width="940" height="312" alt="image" src="https://github.com/user-attachments/assets/ef5156b8-88bc-456f-99fd-05b9a2dc752d" />


2.	Convert all employee names to lowercase.

 <img width="940" height="246" alt="image" src="https://github.com/user-attachments/assets/f7530742-9c34-4ec1-9ffd-b34f2d559181" />


3.	Extract first 3 letters of the employee's first name.
 <img width="940" height="233" alt="image" src="https://github.com/user-attachments/assets/e1bebb2b-df93-4379-b2fc-e28f398de26f" />

4.	Replace '@company.com' in email with '@org.com'.
 <img width="940" height="220" alt="image" src="https://github.com/user-attachments/assets/9ac81b25-700d-43b6-b487-3c3693edd564" />

5.	Trim spaces from a padded string.
 <img width="940" height="121" alt="image" src="https://github.com/user-attachments/assets/3b7db9f4-1e35-46bf-a157-bf3b151f4043" />

6.	Count characters in an employee’s full name.
 <img width="940" height="209" alt="image" src="https://github.com/user-attachments/assets/b5016d08-adbc-4cd1-b95c-e5b2da14c515" />

7.	Find position of '@' in email using INSTR()/CHARINDEX().
 <img width="940" height="236" alt="image" src="https://github.com/user-attachments/assets/7b4e88a0-8602-46c2-a587-73bf1601e85f" />

8.	Add ‘Mr.’ or ‘Ms.’ before names based on gender (assume gender exists).
 <img width="940" height="214" alt="image" src="https://github.com/user-attachments/assets/b70ebae6-14a9-4f7a-8b22-bf919e493e6a" />

9.	Format project names to uppercase.
 <img width="940" height="292" alt="image" src="https://github.com/user-attachments/assets/a2e31ec1-4cba-4f5e-b6a0-8f01a81bbae6" />

10.	Remove any dashes from project names.
 <img width="940" height="234" alt="image" src="https://github.com/user-attachments/assets/24a3e19d-4a6c-4a21-92aa-2a2fb2886ac2" />

11.	Create a label like “Emp: John Doe (HR)”.
 <img width="940" height="238" alt="image" src="https://github.com/user-attachments/assets/d1bf2dd8-5150-4b3f-85fd-87079a4abf73" />

12.	Check email length for each employee.
 
<img width="940" height="252" alt="image" src="https://github.com/user-attachments/assets/2fee2c22-8554-4b74-bd7d-dfd63f870775" />

13.	Extract last name only from email (before @).
<img width="940" height="218" alt="image" src="https://github.com/user-attachments/assets/0e96c426-6b41-47b6-b062-842e4fa0c69b" />
 
14.	Format: “LASTNAME, Firstname” using UPPER and CONCAT.
 <img width="940" height="261" alt="image" src="https://github.com/user-attachments/assets/b9bd2477-74be-46d9-ae23-e1ebcd34e48c" />

15.	Add “(Active)” next to employee names who have current projects.
 <img width="940" height="508" alt="image" src="https://github.com/user-attachments/assets/b15898ca-6487-4825-8fa9-b7c5cf7554e4" />


# NUMERIC FUNCTION EXERCISES (10)
16.	Round salary to the nearest whole number.
 <img width="940" height="242" alt="image" src="https://github.com/user-attachments/assets/d5772d0d-1ab4-4bc7-ab9d-ef47c0865a0d" />

17.	Show only even salaries using MOD.
 <img width="940" height="349" alt="image" src="https://github.com/user-attachments/assets/db1a071c-f50e-408e-855e-2ef59659ce61" />

18.	Show difference between two project end/start dates using DATEDIFF.
 <img width="940" height="233" alt="image" src="https://github.com/user-attachments/assets/947220d7-8bfc-467f-a7f6-8a3f95ae1681" />

19.	Show absolute difference in salaries between two employees.
 <img width="940" height="495" alt="image" src="https://github.com/user-attachments/assets/e89a0196-3b2a-4dfc-9c92-30c434deb68a" />
<img width="940" height="223" alt="image" src="https://github.com/user-attachments/assets/3eeb193b-6ff3-4c54-984a-d05874137036" />

 
20.	Raise salary by 10% using POWER.
 <img width="940" height="250" alt="image" src="https://github.com/user-attachments/assets/1ce9a156-8eb1-4525-a8fc-e2188bced532" />

21.	Generate a random number for testing IDs.
 <img width="940" height="140" alt="image" src="https://github.com/user-attachments/assets/6a4c1a0d-1d91-46c9-946e-b455bf0e554f" />

22.	Use CEIL and FLOOR on a floating salary.
<img width="940" height="217" alt="image" src="https://github.com/user-attachments/assets/ec868521-788c-47ac-9c56-2db1cbaff1d5" />
 
23.	Use LENGTH() on phone numbers (assume column exists).
 <img width="940" height="227" alt="image" src="https://github.com/user-attachments/assets/ca925bc5-a3d4-4380-a5af-15dfee5bcaf9" />

24.	Categorize salary: High/Medium/Low using CASE.
 <img width="940" height="419" alt="image" src="https://github.com/user-attachments/assets/8167acbc-50be-4303-a93c-e6e522c653aa" />

25.	Count digits in salary amount.
 
<img width="940" height="220" alt="image" src="https://github.com/user-attachments/assets/ffaa5140-dfc5-4307-8c51-cc05ed9c1b21" />

# DATE/TIME FUNCTION EXERCISES (10)

26.	Show today’s date using CURRENT_DATE.
<img width="940" height="144" alt="image" src="https://github.com/user-attachments/assets/3bc229a0-7edb-4811-8c16-1fdf45fd7b48" />
 
27.	Calculate how many days an employee has worked.
 <img width="940" height="236" alt="image" src="https://github.com/user-attachments/assets/7cfbb023-6b2c-4b2b-966a-0afdbebe47af" />

28.	Show employees hired in the current year.
 <img width="940" height="93" alt="image" src="https://github.com/user-attachments/assets/c57a4873-7e31-4856-8309-eaed3c7e7b65" />

29.	Display current date and time using NOW().
 <img width="940" height="157" alt="image" src="https://github.com/user-attachments/assets/8dbb809c-cb5d-46f0-a54d-72b291cbeb82" />

30.	Extract the year, month, and day from hire_date.
 <img width="940" height="403" alt="image" src="https://github.com/user-attachments/assets/c814be37-32c4-4457-9901-b6ea24fbe3cb" />

31.	Show employees hired before 2020.
 <img width="940" height="282" alt="image" src="https://github.com/user-attachments/assets/ff3cdf72-2c8e-433a-a9a4-0e32877a0ee1" />

32.	List projects that ended in the last 30 days.
 <img width="940" height="150" alt="image" src="https://github.com/user-attachments/assets/398cda00-d4ad-4681-91dd-0726a3d0eb2d" />

33.	Calculate total days between project start and end dates.
 <img width="940" height="240" alt="image" src="https://github.com/user-attachments/assets/d659d339-bd1e-448b-8f2e-33b813c3c6d4" />

34.	Format date: ‘2025-07-23’ to ‘July 23, 2025’ (use CONCAT).
 <img width="940" height="318" alt="image" src="https://github.com/user-attachments/assets/f1b52224-0919-425c-ad2a-5af69d709e2b" />

35.	Add a CASE: if project still active (end_date IS NULL), show ‘Ongoing’.
 <img width="940" height="484" alt="image" src="https://github.com/user-attachments/assets/10e75339-e253-4d72-a094-2fa696a4cef1" />


# CONDITIONAL FUNCTION EXERCISES (15)

36.	Use CASE to label salaries.
 <img width="940" height="430" alt="image" src="https://github.com/user-attachments/assets/5be44490-0d25-41d4-a618-50a047d183da" />

37.	Use COALESCE to show ‘No Email’ if email is NULL.
 <img width="940" height="242" alt="image" src="https://github.com/user-attachments/assets/cd64242d-fe86-4f3a-8a73-b0be0439a96f" />

38.	CASE: If hire_date < 2015, mark as ‘Veteran’.
 <img width="940" height="394" alt="image" src="https://github.com/user-attachments/assets/136185d2-d89e-4758-b407-f716e9bf592d" />

39.	If salary is NULL, default it to 3000 using COALESCE.
 <img width="940" height="251" alt="image" src="https://github.com/user-attachments/assets/e4d86aad-a952-4bb0-8a73-382f96089d0f" />

40.	CASE: Categorize departments (IT, HR, Other).
 <img width="940" height="381" alt="image" src="https://github.com/user-attachments/assets/b2c4d972-9611-4542-955e-c682087cd508" />

41.	CASE: If employee has no project, mark as ‘Unassigned’.
 <img width="940" height="444" alt="image" src="https://github.com/user-attachments/assets/ebbe1f7a-0669-4b9e-a46a-bb681be68b34" />

42.	CASE: Show tax band based on salary.
<img width="940" height="425" alt="image" src="https://github.com/user-attachments/assets/d9e671f3-aff8-4974-8ab1-3af403beef33" />
 
43.	Use nested CASE to label project duration.
 <img width="940" height="386" alt="image" src="https://github.com/user-attachments/assets/8fea6168-b275-46d7-9e64-429e0d01d284" />

44.	Use CASE with MOD to show even/odd salary IDs.
 <img width="940" height="356" alt="image" src="https://github.com/user-attachments/assets/a71e7f43-7348-4fb6-8a81-30ad1baee240" />

45.	Combine COALESCE + CONCAT for fallback names.

<img width="940" height="268" alt="image" src="https://github.com/user-attachments/assets/e546546f-c51e-45f5-84de-61b3de0a1c22" />

46.	CASE with LENGTH(): if name length > 10, label “Long Name”.
 <img width="940" height="345" alt="image" src="https://github.com/user-attachments/assets/b192205e-10b1-4652-830e-9b92d5b627c9" />

47.	CASE + UPPER(): if email has ‘TEST’, mark as dummy account.
 <img width="940" height="408" alt="image" src="https://github.com/user-attachments/assets/f1edc03b-3472-4bce-9497-563fc7da9fb6" />

48.	CASE: Show seniority based on hire year (e.g., Junior/Senior).
 <img width="940" height="394" alt="image" src="https://github.com/user-attachments/assets/85cfafc1-1930-4efb-aca4-aa961e82c228" />

49.	Use CASE to determine salary increment range.
 <img width="940" height="428" alt="image" src="https://github.com/user-attachments/assets/011a7107-4b83-4f0e-8181-0f1b531b7912" />

50.	Use CASE with CURDATE() to determine anniversary month.
 <img width="940" height="399" alt="image" src="https://github.com/user-attachments/assets/c31111a9-d9ef-44ba-b0fd-a82339b62e0e" />


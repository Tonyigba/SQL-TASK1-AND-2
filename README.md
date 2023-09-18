# INTRODUCTION AND PROJECT TO SQL 

# SQL-TASK1-AND-TASK 2

USE STAFF;

SELECT * FROM employee_info;

-- Code for adding a column name Date_of_Exit to the table 
ALTER TABLE Employee_Info
ADD COLUMN Date_of_Exit Varchar(50);

-- CODE RETURNING ONLY NAME AND ADDING 10 YEARS INTERVAL TO THE DATE OF ENTRY OF EACH STAFF
SELECT NAME, DATE_ADD(DATE_OF_ENTRY, INTERVAL 10 YEAR) FROM Employee_Info;

-- CODE UPDATING TABLE WITH DATE_ADD INTERVAL OF 10 YEARS FROM THE Employees date of Entry
UPDATE Employee_Info 
SET Date_of_Exit =DATE_ADD(DATE_OF_ENTRY, INTERVAL 10 YEAR);

![Adding 10 row to the table staff_info](https://github.com/Tonyigba/SQL-TASK1-AND-2/assets/143624967/b453753c-b82c-4081-a54c-1294c7e2839c)

![SQL TASK 2(00)](https://github.com/Tonyigba/SQL-TASK1-AND-2/assets/143624967/ae3b0f50-63ab-4a9b-8c20-abb37129c0f6)


USE STAFF;

SELECT * FROM Employee_Info;

-- CODE RETURNING ONLY NAME AND ADDING 10 YEARS INTERVAL TO THE DATE OF ENTRY OF EACH STAFF

SELECT NAME, DATE_ADD(DATE_OF_ENTRY, INTERVAL 10 YEAR) FROM Employee_Info;

ALTER TABLE Employee_Info
ADD COLUMN Date_of_Exit Varchar(50);

![SQL TASK 2()](https://github.com/Tonyigba/SQL-TASK1-AND-2/assets/143624967/be1d361b-8c82-4f05-b27b-5ff1f07b2da7)



USE STAFF;

SELECT * FROM employee_info;

-- RUNNING CODE THE RETURNED ONLY THE DAYNAME IN THE DATE OF ENTRY

SELECT DAYNAME(Date_of_Entry) FROM Employee_Info;


![Code returning only dayname](https://github.com/Tonyigba/SQL-TASK1-AND-2/assets/143624967/330193b9-4f6e-466e-978e-7c000ac165a3)


![SQL TASK 2(01)](https://github.com/Tonyigba/SQL-TASK1-AND-2/assets/143624967/0635292e-c399-42fe-bd9a-1bbeedea09b2)




USE STAFF;

SELECT * FROM staff.employee_info;

-- RUNNING CODE THAT RETURNED ONLY YEAR IN THE DATE OF ENTRY

SELECT YEAR(Date_of_Entry) FROM Employee_Info;


![CODE returning only year of entry](https://github.com/Tonyigba/SQL-TASK1-AND-2/assets/143624967/b00d0736-3430-4bc3-8c08-4f2acac5eaf5)


USE STAFF;

SELECT * FROM employee_info;

ALTER TABLE Employee_Info CHANGE ID Employee_ID INT;

-- CHANGING THE ID COLUMN TO Employee_ID


![Changing table name from staff_info to Employee_info](https://github.com/Tonyigba/SQL-TASK1-AND-2/assets/143624967/239c7405-b1f5-4de5-b855-8ae62c129c36)


![Changing ID cplumn](https://github.com/Tonyigba/SQL-TASK1-AND-2/assets/143624967/0ec11a48-e93e-4ed9-a63a-ae7104ed8a47)


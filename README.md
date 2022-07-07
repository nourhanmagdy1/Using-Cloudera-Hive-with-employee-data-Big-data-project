# Using-Cloudera-Hive-with-employee-data-Big-data-project
Employee data analysis:

The given dataset contains information about chicago employee data. The file name: employee-data.csv

1. Create a Hive table named employee-data-hive based on the given dataset. 

2. Create a department-data-hive table by selecting unique department names from the employee-data-hive and adding a column named deptID in the new department-data-hive table, 
and put unique values in the deptID column. 

Alternatively, you can pre-process the employee-data and select the unique department names, 
add DeptID column and assign unique value in the new colum using excel or mySQL database separately, 
and then consider this structure (depart-name, DeptID) to create the department-data-hive table.

3. Update the employee-data-hive table by replacing the department field data with the deptID values as created in the department-data-hive table. 
Also update the employee-data-hive table 'annual salary' field based on the 'Typical Hours' * 'Hourly Rate' * 52 if the annual salary field is empty.

4. Display all employees list with salary more than $100,000 based on employee-data-hive table. 
Also join the employee-data-hive and department-data-hive table to show the average salary of employees by department name

5. Create 5 partitions in a employees_ptn table to store 5 departments in the appropriate partition. Display the partition structure.

6. Create spark DataFrame based on the given dataset. Identify # of records in the DataFrame and show top 10 records.

Submission: A report with all steps, screenshots, and all commands/syntaxes applied. 
Precise but clear explanation of the task need to be written. There will be just one submission per group. 
Each team should mention who did what part of the project in a group. Format report in a presentable way.

NOTE: Do not copy/paste/view other group's solution.

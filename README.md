**Employees Whose Manager Left the Company**

The Employees table contains information about the employees, their salary, and the ID of their manager. Some employees do not have a manager (manager_id is null). 
In SQL, employee_id is the primary key for this table.
Find the IDs of the employees whose salary is strictly less than $30000 and whose manager left the company. When a manager leaves the company, their information is deleted from the Employees table, but the reports still have their manager_id set to the manager that left.
Return the result table ordered by employee_id.

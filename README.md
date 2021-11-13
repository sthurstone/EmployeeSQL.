# EmployeeSQL
Instructions

Data Modeling
Inspect the CSVs and sketch out an ERD of the tables. Feel free to use a tool like http://www.quickdatabasediagrams.com.

![image](https://user-images.githubusercontent.com/89807813/141657752-2211ba03-c643-4c4a-93f2-c221f7387def.png)

Data Engineering

Use the information you have to create a table schema for each of the six CSV files. Remember to specify data types, primary keys, foreign keys, and other constraints.

For the primary keys check to see if the column is unique, otherwise create a composite key. Which takes to primary keys in order to uniquely identify a row.
Be sure to create tables in the correct order to handle foreign keys.

Import each CSV file into the corresponding SQL table. Note be sure to import the data in the same order that the tables were created and account for the headers when importing to avoid errors.

Data Analysis
Once you have a complete database, do the following:

List the following details of each employee: employee number, last name, first name, sex, and salary.

![image](https://user-images.githubusercontent.com/89807813/141657787-24330fab-a70e-42a2-b119-2e99ff39604f.png)

List first name, last name, and hire date for employees who were hired in 1986.

![image](https://user-images.githubusercontent.com/89807813/141657812-2df39da1-16ae-4e3b-b57f-9f5bf9635e4d.png)

List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

![image](https://user-images.githubusercontent.com/89807813/141657827-bdddfb18-6f84-4507-848c-27316d4e4c5c.png)

List the department of each employee with the following information: employee number, last name, first name, and department name.

![image](https://user-images.githubusercontent.com/89807813/141657840-1c125ff5-65e6-4a70-8fe7-13a496153106.png)

List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

![image](https://user-images.githubusercontent.com/89807813/141657855-8038ead8-ba4d-4303-b922-7026bff4482d.png)

List all employees in the Sales department, including their employee number, last name, first name, and department name.

![image](https://user-images.githubusercontent.com/89807813/141657870-f4c05f2f-554b-4d21-a7f3-075ee0cb93ea.png)

List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

![image](https://user-images.githubusercontent.com/89807813/141657884-1633ac23-8793-488f-9ccc-64c5445e8118.png)

In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

![image](https://user-images.githubusercontent.com/89807813/141657912-3d814cf3-4207-4c70-9c79-0abc33a5543f.png)

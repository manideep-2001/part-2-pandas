# part-2-pandas
There was a school named "XYZ" where student information was gathered in the admittance cell, including the student's name, DOB, any essential information about their parents, and any prior school information. The class instructor has accessibility to student academic information, such as student roll numbers and test scores for the relevant subjects. Now that the administration wants to evaluate all of the data for each and every student, they hired a data scientist since they needed someone who could clean the data and give the essential data insights.

# About the dataset

The data scientist began gathering information from administrators and instructors, carrying two tables. 

# Student master table

Student Id: Unique number assigned to each student.
DOB: Date of birth of the student.

# Student Result table 

Student Id: Unique number assigned to each student.
Math: Mathematics subject scores of each student.
Science: Science subject scores of each student.
History: History subject scores of each student.

# Expected outcomes

Make two data frames for each table. 
Add new column age in Student Master table where student age should be there in (years) with respect to 31st Dec 2021.
 Make a new data frame from two tables containing all columns of tables Student master and Student result except DOB column. 
Add a new column " Percentage " data frame and calculate it. Max marks in each subject are 100. 
Add a 5% bonus percentage to the student whose percentage is more than 65%. Update the Percentage column with new values. 
Update Student Id, replace the first letter with "X" in place of "A" where the percentage is less than 60%. Other remaining letters of student id must remain the same.

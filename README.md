# Pewlett_Hackard_Analysis
Create entity relationship diagrams, perform data modeling and complete analysis on an employee database using SQL techniques.

## Overivew
Pewlett Hackard is a large company with thousands of employees who have been there for a long time. As these people are approaching retirement, the company is looking into the future in two ways. Firstly, it is offering retirement packages for employees meeting the criteria and second, its starting to think about the thousands of new job openings that will result from upcoming retirements.

Bobby is the HR analyst whose job is to perform employee research. His task was to check who will be retiring in the next few years and how many positions the company needs to fill. This analysis will help future proof Pewlett Hackard by generating a list of employees eligible for a retirement package.
The data that bobby needed was only in 6 CSV files because the company was mainly using Excel and VBA. But they finally decided to update their methods and instead use SQL.
Our Task was to help Bobby build an employee database with SQL by applying our data modeling, engineering, and analysis skills.

## Challenge Overview
After generating the report Bobby's manager gave us two more assignments -
1. Determine the number of retiring employees per title.
2. Identify employees who are eligible to participate in a mentorship program.

## Results 
- We created SQL queries to generate a list with the number of retiring employees by Title. But with the generated list we noticed there were duplicate entries for some employees because they had switched titles over the years.

- We then created queries to retrieve employees with the most recent job title about to retire. Below you can see a list of employees with their latest titles.

![image](https://user-images.githubusercontent.com/78935551/115163393-e7c58a00-a076-11eb-8398-eaeb5883cd47.png)

- Another file was created to retrieve the number of employees by their most recent job title who are about to retire. This count of employees gives us a clear picture of how many employees are about to retire and that's quite a lot of employees. 29,414 are Senior Engineers. Pewlett Hackard might have to promote employees in a similar role or hire for senior positions.

![image](https://user-images.githubusercontent.com/78935551/115163732-be0d6280-a078-11eb-8eea-a8ac36b1be9e.png)

- Using our knowledge of SQL queries, we created a mentorship-eligibility table that holds the current employees who were born between January 1, 1965, and December 31, 1965. This is a great approach so that the new staffs are well trained and they receive guidance, motivation, support, and role modeling. this list had almost 1549 employees who were eligible for mentorship and majority of them are Senior staff or Department Leaders.

![image](https://user-images.githubusercontent.com/78935551/115165206-d8484000-a07a-11eb-8e0f-77b9ca25f9d2.png)










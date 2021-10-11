# An Analysis of Pewlett Hackard Employee Database with SQL

## Overview of Project

### Purpose

This is an anlayis for Pewlett Hackard to find which positions will need to be filled in the near future. We help build an employee database with sql by applying by applying your data modeling, engineering, and analysis skills.  

## Results

### The Number of Retiring Employees by Title

- The retirment_titles table shows retiring employees and thier titles with birth dates between 1/1/1952 and 12/31/1955.

![retirement_titles.png](https://github.com/alexhuynh0530/Pewlett_Hackard_Analysis/blob/main/retirement_titles.png)

- The unique titles table uses Dictinct with Orderby to remove duplicate rows on retirement_titles.

![unique_titles.png](https://github.com/alexhuynh0530/Pewlett_Hackard_Analysis/blob/main/unique_titles.png)

- The retiring_titles table retrieves the number of employees by job title

![retiring_titles.png](https://github.com/alexhuynh0530/Pewlett_Hackard_Analysis/blob/main/retiring_titles.png)

### The Employees Eligible for the Mentorship Program

- The mentorship_eligibilty table holds data for retiring employees with their title.

![mentorship_eligibilty.png](https://github.com/alexhuynh0530/Pewlett_Hackard_Analysis/blob/main/mentorship_eligibilty.png)

## Summary

How many roles will need to be filled as the "silver tsunami" begins to make an impact?

- 29414 Senior Engineers
- 28254 Senior Staff
- 14222 Engineer
- 12243 Staff
- 4502 Techinque Leader
- 1761 Assistant Engineer
- 2 Manager

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

No, we are missing mentorship qualified employees that are managers to mentor the next generation.

![mentorship_eligibility_count.png](https://github.com/alexhuynh0530/Pewlett_Hackard_Analysis/blob/main/Vmentorship_eligibility_count.png)

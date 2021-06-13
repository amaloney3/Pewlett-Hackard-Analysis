# Enough For a 'SQL'? Helping 'Pewlett Hackard' Prepare For Mass Retirements Using Database Management Tools

## Overview
The purpose of this project was to help the fictional computer company 'Pewlett Hackard' better understand the scope of its workforce
by crafting SQL queries using Postgres/pgAdmin. The analysis focused on selecting, merging and grouping data by birthdays, job titles and other 
variables to show how close the company was to facing a "silver tsunami" -- a mass of employees reaching retirement age.

## Results
The company has tens of thousands of employees eligible for retirement (i.e., employees born between the years 1952 and 1955).
According to the analysis, there were 90,398 employees who fit the criteria -- nearly one-third of the company's 300,000+ workforce (number derived
from the 'employees' database, which houses the company's unique employee ID numbers). It's not clear (or likely) that every single one of them would
walk out the door at the same time. However, it's probably reasonable for the company to be concerned it will see significant attrition over the next
five years or so. Based on this analysis, company decisionmakers should keep a few things in mind to begin successfully replenishing its workforce.

### Takeaways

* Almost 65% of retirement-eligible workers are senior-level employees (fig 1). That includes senior engineers and senior staff (57,668 total). PH will want to invest
significantly in training and elevating its junior-level workers in those positions especially.

* Only 2 (.002%) managers have reached the retirement threshold (fig 1). Such positions are clearly not in super-high demand solely due to the 'silver tsunami,' but given the looming void in leadership more broadly, PH may want to consider restructuring its hierarchy to give more workers a crack at leadership and spread institutional knowledge more widely.

![image](https://user-images.githubusercontent.com/1015285/121822088-c6da7900-cc62-11eb-9eb0-a70474e179ea.png)

Figure 1

* Only about 0.5% (1,549 out of 300,024) of workers are eligible to be employee mentors at PH. Although not an impossibly small percentage, especially given how many employees are on the cusp of retirement and wouldn't need the mentoring, PH should consider a larger pool of eligibility to adequately train the next generation.

* If PH mostly maintains the current standard for mentorship eligibility, it may want to consider broadening the pool for assistant engineers and technique leaders. There
is a relative dearth of mentorship-eligible workers in those fields (67 and 77, respectively, or about 9% total of mentorship-eligible workers).

![image](https://user-images.githubusercontent.com/1015285/121822591-829ca800-cc65-11eb-84b5-61a85b155835.png)

Figure 2

## Summary

As noted above, the analysis here suggests PH is on the verge of a massive reorientation of its workforce. 
![image](https://user-images.githubusercontent.com/1015285/121823188-29cf0e80-cc69-11eb-905f-be2e316c08cf.png)

For this part of the Challenge, you’ll write a report to help the manager prepare for the upcoming "silver tsunami."

The analysis should contain the following:

Overview of the analysis: Explain the purpose of this analysis.
Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.
Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
How many roles will need to be filled as the "silver tsunami" begins to make an impact?
Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
Deliverable 3 Requirements
Structure, Organization, and Formatting (6 points)
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections. (2 pt)
Each section has a heading and subheading. (2 pt)
Links to images are working and displayed correctly. (2 pt)
Analysis (14 points)
The written analysis has the following:

Overview of the analysis:

The purpose of the new analysis is well defined. (3 pt)
Results:

There is a bulleted list with four major points from the two analysis deliverables. (6 pt)
Summary:

The summary addresses the two questions and contains two additional queries or tables that may provide more insight. (5 pt)

# Pewlett Hackard Analysis



## Overview of the analysis:

Pewlett Hackard is preparing for the “silver tsunami” as many of their employees are reaching retirement age. Bobby and his manager have provided 6 CSVs with data for their employees at PH that we will use to create an ERD and run queries to create tables to use of our anlaysis.

## Results:
We created this ERD for the 6 CSVs that were provided. As seen below, most of the files use the employee number as the primary key. We will use this to run our query and pull the data for deliverable 1 and 2.

![EmployeeDB](https://user-images.githubusercontent.com/107590196/182744790-5ccef342-5f91-4cc9-84ac-a803f1368c73.png)

### Deliverable 1: The Number of Retiring Employees by Title

![Deliverable #1](https://user-images.githubusercontent.com/107590196/182746001-38a5936b-16bd-407b-9afc-ecd9b1b81f77.png)

- This query ran the count of the people retiring by their title, this shows 72,458 will be retiing soon. 
- This shows that majority of the upcoming retiries are Senior Engineers (25,916) and Senior Staff (24,926).
- This file alone does not give details to be able to make decisions. 
- Since Majority of the retiries are seniors, this could be an opportunity for promotion for staff and engineers who are not at a sr. level.

### Deliverable 2: The Employees Eligible for the Mentorship Program

![Deliverable #2](https://user-images.githubusercontent.com/107590196/182746017-2bbee5e3-c078-4167-9cea-bc6bc6a418b3.png)

- This query show the employees who were born between January 1, 1965 and December 31, 1965 and are eligilbe to be mentors.
- There are a total of 1,549 employees currently eligible for the employee mentorship program.
- Here are the titles and the number of mentors available by title (Assistant Engineer: 58, Engineer: 397, Senior Engineer: 293, Senior Staff: 415, Staff:	309, Technique Leader: 77)
- There are no managers available for the mentor program but there are a couple of managers who will be retiring soon.


## Summary:

The summary addresses the two questions and contains two additional queries or tables that may provide more insight. 
Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?
There will be about 41,380 employees who will be retiring. There are 7 positions that will have employees retiring soon. 

<img width="98" alt="Emp retiring" src="https://user-images.githubusercontent.com/107590196/182750887-86780946-219e-48c2-bde9-da49b0bff676.png">



### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

There are only 1,549 qualified, retirement-ready employees in the departments to mentor the next generation. There are 41,380 employees who will be retiring. This means there are about 26 people retiring for every 1 person that can be a mentor. 

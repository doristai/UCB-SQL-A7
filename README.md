# UCB-SQL-A7

## Overview 

The goal of the project is to identify the number of retiring employees by title and determine which employees are eligible for the mentorship programme. 

- Retired employee information: 

    - Titles 

    - Born between 01-01-1952 and 31-12-1955

- Steps and Output

    1. ```retirement_titles``` table : Retired employees with their titles.

    2.  ```unique_titles``` table : Remove employees with duplicate enteries due to switching of titles by using ```DISTINCT ON``` function.

    3. ```retiring_titles``` table : Count the total number of employees for each title.

    4. ```mentorship_eligibility``` table : Use information from Employees, Department Employees and Titles table to determine which employee is elgible for the mentorship programmes. 

## Results 

- ```retirement_titles```

Retired Employees with Titles ![image](https://user-images.githubusercontent.com/70616488/116862653-f30dcf00-abb9-11eb-96f9-98c7fe2b98c0.png)


- ```unique_titles```

Remove Duplicates![image](https://user-images.githubusercontent.com/70616488/116862970-6c0d2680-abba-11eb-8027-1109bafbc094.png)



- ```retiring_titles``` 

    - Majority of the retired employees were in senior-level (64%)

Counts of Retired Employees for each Title![image](https://user-images.githubusercontent.com/70616488/116862750-133d8e00-abba-11eb-8144-cc50889fc97b.png)


- ```mentorship_eligibility```

    - Most of the employees who are eligible for mentorship programme have a senior title. 

Employees who are elgibile for montorship programme![image](https://user-images.githubusercontent.com/70616488/116863028-85ae6e00-abba-11eb-9134-a7ff978d9cf6.png)


## Summary

63-64% of the current workforce are either retired or eligible for mentorship programme which those positions need to be filled within the next 5-10 years. Issues can still be raised even if those vaccancies can be filled immmediately. For instance, newly hired employees might lack of experiences which requires extra time for training. The company should  build up long-lasting employmentship with their employees to avoid high turnover rate of each positions. Also, the HR should hire new employees with relevant experiences in each position. However, rapid development of automation and technologies can overcome the problems with lack in workforce which can ensure a company to function stably in the future to maintain its revenues.


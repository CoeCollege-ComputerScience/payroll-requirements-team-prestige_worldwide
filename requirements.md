# Requirements - Prestige Worldwide

## Scope

* System needs to track payroll (no other expenses)
* No need to track project budgets from which employees are being payed
	-  Workers are payed from one singular project budget.

## Design

### How Employee Data is Stored
* Each employee has the following data associated with him/her:
	- First Name
	- Last Name
	- Employee ID
	- Salary
		- Deductions
	- Active?


* Visual - how the information is desplayed
* Command Line program
	- no GUI necessary

### Input
* Each time a new binary file is added employee data is processed and added to master record

### Output

* Once a year, program generates W-2 forms based on records from the last year
* these records are for Employee tax purposes only and are not maintained in the system
	- the relevant detailed is stored in master record file

* Technical
    - Add, update, employee information
    - Calculate pay breakdown and return
    - Meets security requirements


## Data Retention

* Data saved every time in one master record file

* Retains payroll records of terminated employees for two years

## Access Management
* Who gets to add/remove employees?
* Who gets to grant/revoke access privileges?

## Legal

* System meets U.S regulations for payroll software


## Compensation Method

* Employees are salaried for the sake of simplicity.
        - Salary is a base, bonuses/commission on top

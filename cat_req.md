#  Categorized Requirements

## Business -
* ( What the customer wants to achieve )
* Store and manage payroll information
* Generate W2's

## User -
* ( How the project the will be utilized by users )
* Command line program
* Users can add binary files to be read and access information through command line options

## Functional-
* (Detailed statements of capability)
* Each employee has the following data associated with him/her:
    - First Name 
    - Last Name
    - Employee ID
    - Salary (Monthly)
    - Deductions 
        Federal tax (Percent)
        state tax (Percent)
        medical (Fixed cost)
    - Active
    - directory pass or USPS.
* Each empolyee record generates the following W2 data:
    Bi-weekly gross pay (Monthly pay *12  / 26)
    Bi-weekly medical ( Monthly medical *12 / 26)
    Bi-weekly federal tax (Bi-weekly gross pay * federal tax / 100)
    Bi-weekly state tax (Bi-weekly gross pay * state tax /100)
    Bi-weekly net pay (Bi-weekly gross pay - Bi-weekly medical - Bi-weekly federal tax - Bi-weekly state tax )
* The following data is tracked from the employer:
    Total gross pay
    Total medical 
    Total federal tax
    Total state tax


## Non-Functional-
* ( Statements of quality )
* Flexible initially a few hundred payrolls to several thousand later


## Implementation-
* ( Temporary requirements to implement the project )

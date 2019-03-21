## Must have (essential)
* Reads binary file(s) as command line argument(s).
    (Functional, Implimentation), the core functionality of the payroll software, it must be able to read the records before everything else.
* Stores information in MySQL database.
    (Functional, Business), out of scope for the classroom, but information from the records needs to be securely stored somewhere once read.
* Sorts employee records alphabetically by last name (ties are broken with first name).
    (Functional), a sort function is required to properly order the data aquired from previous records.
* Allows users to search for records they have access to (query runs against MySQL db).
    (Functional, User), a search function for users to navigate the database and find a single record, as well as for use in our other funcitons.
* Calculates and generates W2 files for employees yearly.
    (Functional, business), a calc function which is able to break down pay for all employees into net pay and deductions, as well as keep running totals for the business side.
* Ability to add active and remove inactive employees from payroll for users with write access to the database.
    (Functional, business), add and remove functions so the program maintains relevance to the business past the initial implimentation.
* Records are displayed with tabular formatting, making them easy to move to spreadsheet software for reporting and forecasting.
    (Functional, User), a print function allowing users to view records in the terminal, output is formatted for readability, information must be visible to the users to be usable.

## Should have (desired)
* System meets U.S regulations for payroll software.
    (Non-functional), essential for any actual commercial software, but not for ours.
* Different types of user, such as admin, employee.
    (Functional), base of security system, tiering information access 
* Ability for certain users to edit employee records.
    (Functional), an edit function to update employee records directly
* Personally identifying employee data should be encrypted.

## Could have (optional)
* Two-Factor Authentication to maintain the security of the system.
* A simple help menu so users are able to see what they are able to do within the system.
* System could have the ability to display the records in a different format.
* Let employees individually enter their own time sheets.
* Could send emails to employees reminding them to submit their time sheets before a deadline.
* A back-up files could be created once there a significant modification of payroll records. For example(the modification of employee adress). So when some error occurred, we can go back and check the back-up files.
* The system could provide some error exceptions or usages which would reduce the invalid inputs or unexpected handling caused by users.

## Won't have
* Project budgets to track (employees all paid from single project)
* Interface or GUI



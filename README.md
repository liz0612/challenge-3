# Employee Payroll Tracker Starter Code

Description

The Employee Payroll Tracker is a web application designed for payroll managers to efficiently view and manage employee payroll data. This application provides a dynamic and interactive interface to add, display, and analyze employee information, such as names and salaries. With its clean and responsive design, the application ensures an intuitive user experience across various screen sizes.

User Story

AS A payroll managerI WANT an employee payroll trackerSO THAT I can see my employees' payroll data and properly budget for the company

Acceptance Criteria

GIVEN an employee payroll tracker

WHEN I click the "Add employee" button

THEN I am presented with prompts asking for the employee's first name, last name, and salary.

WHEN I finish adding an employee

THEN I am prompted to either continue adding employees or cancel.

WHEN I choose to continue

THEN I am prompted to add another employee.

WHEN I choose to cancel

THEN the employee data is displayed on the page sorted alphabetically by last name, and the console shows computed and aggregated data.

Features

Add Employees:

Prompt user for employee details (first name, last name, salary).

Validate salary input; default to $0 if invalid.

Display Employees:

Render employee data in an HTML table sorted alphabetically by last name.

Console Outputs:

Display average salary and total number of employees.

Randomly select and log one employee's full name.

Responsive Design:

Ensures compatibility across multiple screen sizes for ease of use.

Functions Implemented

collectEmployees

Description: Allows the user to add multiple employees via prompts.

Output: Returns an array of employee objects in the format:

[
  {
    firstName: "John",
    lastName: "Smith",
    salary: 12345
  },
  {
    firstName: "Jane",
    lastName: "Doe",
    salary: 54321
  }
]

displayAverageSalary

Description: Logs the average salary and the number of employees to the console using template literals.

getRandomEmployee

Description: Randomly selects an employee from the array and logs their full name to the console using template literals.

Deployment

The application is deployed at: Live URL

GitHub Repository: Repository URL

Mock-Up

The following images showcase the application's functionality:

Add Employees: Interactive prompts for adding employee details.

Display Table: Sorted table of employee data.

Console Logs: Display of average salary, total employees, and a randomly selected employee.

Technical Details

Languages Used: HTML, CSS, JavaScript

Tools: Built-in JavaScript functions (e.g., Math.random, isNaN), DOM manipulation.

Starter Code: Modified and extended the provided starter code.

Repository Details

Unique Repository Name: Employee-Payroll-Tracker

Best Practices:

Follows proper file structure and naming conventions.

Includes meaningful commit messages.

Contains quality comments for code clarity.

How to Use

Clone the repository:

git clone [repository-url]

Open the index.html file in your browser.

Click the "Add Employees" button to begin adding employee data.

Screenshots

![image](./images/Screenshot%202025-01-27%20at%208.09.26 PM.png)
![image](./images/Screenshot%202025-01-27%20at%208.09.42 PM.png)
![image](./images/Screenshot%202025-01-27%20at%208.09.51 PM.png)
Employee Payroll Tracker



Contributions

Contributions are welcome! Please open an issue or submit a pull request for any suggestions or improvements.


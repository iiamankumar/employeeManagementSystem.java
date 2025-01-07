EmployeeManagementSystem.java

A simple Java program to manage employee records. The EmployeeManagementSystem allows users to perform basic operations such as adding employees, removing employees, and displaying employee details, including their ID, name, age, and salary.

Features

Add Employee: Add an employee by entering their details (ID, name, age, salary).
Remove Employee: Remove an employee by their ID.
Display Employee Details: View the details of all employees, including their ID, name, age, and salary.
Getting Started

Prerequisites
To run this project, ensure you have the following installed:

Java Development Kit (JDK) (version 8 or higher)
A code editor or IDE (e.g., IntelliJ IDEA, Eclipse, or a text editor like VS Code).

How to Use

When you run the program, you will be presented with a menu to choose from the following options:

Add Employee:
Enter the employee's details, including their ID, name, age, and salary.
Remove Employee:
Enter the employee ID of the employee you wish to remove.
Display Employee Details:
View all employee details, including their ID, name, age, and salary.
Exit:
Exit the program.

Code Overview

The EmployeeManagementSystem.java program is structured as follows:

Classes:
Employee: Represents an employee with attributes for ID, name, age, and salary.
EmployeeManagementSystem: The main class that manages employee records and provides the menu interface.
Methods:
addEmployee(): Adds an employee to the system.
removeEmployee(): Removes an employee from the system based on their ID.
displayEmployees(): Displays the details of all employees.
main(String[] args): The entry point of the program, presenting the user menu.

Future Enhancements

Potential updates to improve functionality:

Allow data persistence by saving employee records to a file or database.
Implement search functionality to find employees by ID or name.
Add sorting options (e.g., sort by name, age, or salary).
Include input validation to handle invalid entries (e.g., duplicate IDs or non-numeric input).
Add a graphical user interface (GUI) for better usability.

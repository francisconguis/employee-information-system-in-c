📁 ABC COMPANY - Employees Information System

# 📁 ABC COMPANY - Employees Information System

![Language](https://img.shields.io/badge/Language-C-blue.svg)
![Standard](https://img.shields.io/badge/Standard-C99-informational.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey.svg)

This is a simple C program that manages employee records for ABC COMPANY. It allows users to input, view, and evaluate employee data such as ID, name, address, department, position, and year hired. It also determines employees eligible for a Loyalty Award (10+ years of service).

📌 Features

    ✅ Add new employee records
    
    📋 Display all stored employee information
    
    🏅 Show employees who are eligible for a loyalty award (10 or more years of service)
    
    💾 Data is stored in a plain text file (record.txt) using a pipe-separated format

🛠 How to Use

      📦 Compile the Program
        Use any C compiler (e.g., GCC):
        bash
        gcc employee_system.c -o employee_system
    
      ▶️ Run the Program
        bash
        ./employee_system

🧾 Menu Options

    1. Enter new record             -> Input employee data and save to file
    2. Display Employee Information -> View all stored employee records
    3. Display Loyalty Awardees     -> Show employees with 10+ years in service
    4. Exit                         -> Close the program

🗃 Data Format

All records are stored in a file called record.txt with the following format per line:

    EmployeeID|EmployeeName|EmployeeAddress|DeptName|Position|YearHired

Example:

    EMP001|Juan Dela Cruz|123 Buendia St, Manila|IT|Programmer|2010


🧮 Loyalty Award Logic

The function yearsInService() calculates how many years the employee has been with the company by subtracting YearHired from CURRENT_YEAR (defined as 2025 in the code). If the result is 10 or more, the employee qualifies as a Loyalty Awardee.

📁 File Structure

    employee_system.c → Main source code
    
    record.txt → Automatically created data file that stores employee records

🧑‍💻 Author

Developed for educational or internal use in managing basic employee information in C.

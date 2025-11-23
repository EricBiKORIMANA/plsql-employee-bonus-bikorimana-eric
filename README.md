# Employee Bonus Manager (PL/SQL Project)

### ID: 27928

### Name: BIKORIMANA Eric

---
## Overview
This project demonstrates how to use **PL/SQL Collections**, **Records**, and **GOTO statements** together.  
The program calculates employee bonuses while skipping invalid salary entries using PL/SQL control structures.


## Features
- **Record Type**:  Defines employee structure (ID, name, salary, bonus)
- **Nested Table Collection**:  Stores multiple employee records in memory
- **GOTO Control Flow**: Skips employees with invalid salaries
- **DBMS_OUTPUT**: Prints formatted report to console 
- **Bulk Collect + Update**: Loads and updates employee data efficiently

## Table Structure
```sql
employee(ID, name, salary, bonus)
```

## File description

| File Name           | Purpose / Description |
|--------------------|-----------------------|
| `sql/01_create_table.sql`   | Creates the `employees` table and inserts employee records with salaries.|
| `sql/02_calculate_bonus.sql`    | Contains the stored procedure that loads employees into a collection, calculates bonus amounts, skips invalid salaries using `GOTO`, and updates the database. |
| `sql/03_display.sql`     | Contains the stored procedure that prints employee data (ID, name, salary, bonus) using `DBMS_OUTPUT`.|
| `sql/04_test_run.sql`       | Runs the program by calling both procedures: calculates bonuses then displays results. |


## Image description

| Image Description           | View Image link |
|--------------------|-----------------------|
| Creates the `employees` table | [![Static Badge](https://img.shields.io/badge/github-view_image-blue?logo=github)](images/01_create_table.png) |
| Inserts records  | [![Static Badge](https://img.shields.io/badge/github-view_image-blue?logo=github)](images/02_Insert_data.png) |
| Preview inserted records | [![Static Badge](https://img.shields.io/badge/github-view_image-blue?logo=github)](images/02.1_preview_data.png) |
| Create procedure `calculate_bonus` | [![Static Badge](https://img.shields.io/badge/github-view_image-blue?logo=github)](images/03_create_procedure_calculate_bonus.png) |
| Create procedure `display_employees` | [![Static Badge](https://img.shields.io/badge/github-view_image-blue?logo=github)](images/04_create_procedure_for_display.png) |
| Executes the procedure by calling both procedures  | [![Static Badge](https://img.shields.io/badge/github-view_image-blue?logo=github)](images/05_test_procedure.png) |





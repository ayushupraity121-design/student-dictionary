# Student Information Dictionary System

A lightweight Python project that implements a student record management system using built-in Python dictionaries and structured data.

## Features
- **Structured Data:** Stores records inside nested dictionaries using unique Student IDs as keys.
- **Add Operation:** Inserts a new student record after validating unique IDs.
- **Search Operation:** Retrieves specific student details instantly.
- **Update Operation:** Modifies individual properties (`name`, `age`, `course`, `grade`) of existing students.

## How to Run
1. Open the project folder in **VS Code**.
2. Open a terminal panel (`Ctrl + ~`).
3. Execute the script with the following command:
   ```bash
   python main.py
   ```

## Example Console Output
The script automatically executes a suite of tests demonstrating success paths and error handling:
- Rejects duplicate ID additions.
- Displays comprehensive errors for missing records during lookups.
- Modifies and displays updated dataset states seamlessly.
-
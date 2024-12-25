# Employee Management System (EMS)

The **Employee Management System (EMS)** is a simple Java-based console application that allows users to manage employee information effectively. This includes adding, viewing, updating, and removing employee details.

---

## Features

1. **Add Employee Details**  
   Create a new employee profile by providing details like name, ID, contact information, position, salary, etc. Data is saved in text files for each employee.

2. **View Employee Details**  
   Retrieve and display employee details by entering their unique ID.

3. **Update Employee Details**  
   Modify specific details of an employee's profile.

4. **Remove Employee**  
   Delete an employee's record by providing their ID.

5. **Exit the System**  
   Gracefully exit the application.

---

## Application Overview

- **Programming Language:** Java  
- **File-Based Storage:** Employee data is stored as individual text files for simplicity. Each file is named using the employee's unique ID.

---

## How to Run the Application

1. **Prerequisites:**
   - Ensure you have the Java Development Kit (JDK) installed on your system.
   - A text editor or IDE (e.g., IntelliJ IDEA, Eclipse) to run Java code.

2. **Steps:**
   - Clone this repository or download the source code:
     ```bash
     git clone https://github.com/yourusername/EmployeeManagementSystem.git
     ```
   - Navigate to the project directory:
     ```bash
     cd EmployeeManagementSystem
     ```
   - Compile the code:
     ```bash
     javac EmployManagementSystem.java
     ```
   - Run the application:
     ```bash
     java EmployManagementSystem
     ```

---

## File Structure

- **Main Classes:**
  - `MainMenu`: Displays the main menu.
  - `Employee_Add`: Handles adding new employees and saving their details to files.
  - `EmployDetail`: Collects and organizes employee information.
  - `Employee_Show`: Retrieves and displays details of a specific employee.
  - `Employee_Remove`: Deletes an employee's record.
  - `Employee_Update`: Updates specific details of an employee.
  - `CodeExit`: Handles graceful exit from the application.

- **Storage:**  
  Employee data is stored in text files named as `file<employee_id>.txt`.

---

## Example Usage

### Adding an Employee
1. Launch the application.
2. Select option `1` from the menu.
3. Enter the required employee details.
4. A new text file is created to store the employee's information.

### Viewing Employee Details
1. Select option `2`.
2. Enter the employee's ID to view their profile.

### Updating Employee Details
1. Select option `4`.
2. Enter the employee's ID.
3. Specify the current value and the new value to update the desired field.

### Removing an Employee
1. Select option `3`.
2. Enter the employee's ID to delete their record.

---

## Known Limitations

1. The application uses file-based storage, which is not suitable for handling a large number of employees.
2. Error handling could be improved for a more robust user experience.
3. The application runs on the console, and there is no graphical user interface (GUI).

---

## Future Enhancements

- Implement a database (e.g., MySQL or SQLite) for efficient data storage.
- Add a graphical user interface (GUI) for better user interaction.
- Include authentication to secure access to the EMS portal.
- Support for exporting data in various formats (e.g., CSV, JSON).

---

## Author

- **Praveen Kumar**  
  Passionate developer with a keen interest in building practical and efficient applications.

---

## Acknowledgements

- Java documentation and tutorials.
- Community support and feedback.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

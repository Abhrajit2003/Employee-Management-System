# **Employee Management System**  

The **Employee Management System** is a Java-based desktop application designed to simplify employee record management. Built using **Swing**, **AWT**, and **MySQL Workbench**, the system offers a secure, intuitive interface for administrators to manage employee data with ease.  

## **Key Features**  

- **Admin Authentication**  
  - Secure login system to restrict access to authorized users only.  

- **Employee Management Options**  
  - Add new employee records with details such as:  
    - Name, Father’s Name, Designation, Address, Phone Number, Aadhaar Number, Salary, and Employee ID.  
  - Update existing records for corrections or modifications.  
  - Remove employee records from the system.  

- **Advanced Functionalities**  
  - **Search**: Retrieve employee details using Employee ID.  
  - **Print**: Generate and print employee details for documentation.  
  - **Back Navigation**: Seamlessly return to the main menu from any feature.  

## **Technologies Used**  

- **Programming Language**: Core Java  
- **Graphical User Interface**: Swing and AWT  
- **Database**: MySQL Workbench  

## **Installation**  

### **Prerequisites**  
- Java Development Kit (JDK) 8 or higher installed.  
- MySQL Workbench installed and configured.  
- Java IDE (e.g., IntelliJ IDEA, Eclipse, or NetBeans).  

### **Steps to Install and Run**  

1. **Clone the Repository**  
   Clone the project from GitHub using the following command:  
   ```bash  
   git clone https://github.com/Abhrajit2003/Employee-Management-System.git 

2. **Set Up the Database**  
   - Open MySQL Workbench and create a database named `employee_management`.  
   - Execute the SQL script provided in the `database` folder of the repository to create the necessary tables.  
   - Update the database connection details (e.g., username, password, database URL) in the project’s code.  

3. **Import the Project**  
   - Open your Java IDE and import the project.  
   - Configure the project’s build path to include necessary libraries (if required).  

4. **Run the Application**  
   - Locate the main class file in the project.  
   - Compile and run the application.  

5. **Log In as Admin**  
   - Use the default admin credentials provided in the database to log in and access the system.  

## **Future Enhancements**  

- Add multi-user roles with role-based permissions for better access control.  
- Implement analytics features for insights into employee performance and salary distribution.  
- Upgrade the UI/UX using JavaFX for a modern look and feel.  

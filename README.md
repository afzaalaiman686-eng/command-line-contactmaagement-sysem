### Contact Management System (Python) Task 1

### Intoduction:
- This is a simple Contact Management System built in Python
- It allows users to store, manage, and organize contact details such as name, phone number, email, city, and company
- The program runs in the terminal and saves data using a JSON file

### Features:
- Add new contacts
- View all contacts in table format
- Search contacts (by name, phone, or email)
- Filter contacts (by city or company)
- Update existing contacts
- Delete contacts
- Data stored permanently in http://contacts.json

### Technologies Used:
- Python
- JSON (for data storage)
- Regular Expressions (for validation)

### How to Run:
- Open terminal / Jupyter Notebook
- Run the Python file:
- Bash
- python file_name.py
- Choose options from the menu (1–7)

### Data Structure:
- Each contact contains:
- ID
- Name
- Phone
- Email
- City
- Company
- Example:
- JSON
- {
- "id": 1,
- "name": "Ali Ahmed",
- "phone": "03001234567",
- "email": "ali@gmail.com",
- "city": "Islamabad",
- "company": "TechSoft"
- }

### Validation Rules:
- Phone must contain digits only (min 10 digits)
- Email must follow valid format

### Future Improvements:
- GUI version (Tkinter)
- Database integration (SQLite)
- Login system
- OOP-based structure
# Conclusion
- The Contact Management System is a simple yet effective application that demonstrates how basic programming concepts can be used to solve real-world problems
- It allows users to efficiently store, manage, search, and update contact information in an organized way
- Through this project, key concepts such as file handling, data structures (lists and dictionaries), input validation, and    programming are applied in a practical scenario
- The use of a JSON file ensures data persistence, making the system useful beyond a single session
- Overall, this project provides a strong foundation for building more advanced applications
- It can be further enhanced by integrating graphical interfaces, databases, or object-oriented programming techniques
  
# Multi-User Authentication System (Python - JSON Based) Task 2

# Introduction:
- This project is a Command-Line Interface (CLI) based authentication system developed using Python
- It allows multiple users to register, login, and manage their accounts securely
- User data is stored in a JSON file, simulating a basic real-world authentication system

# Features:

- User Registration
- Unique username and email validation
- Strong password enforcement

# User Login:
- Login using username or email
- Password verification using hashing

# Password Security:
- Passwords are hashed using SHA-256
- Plain text passwords are not stored

# JSON Data Storage:
- User data stored in http://users.json
- Data loads on program start and updates dynamically

# Additional Functionalities:
- Password reset
- Account deletion
- Input validation using regex
- Modular code structure

# Technologies Used;
- Python
- JSON (for data storage)
- hashlib (for password hashing)
- re (for regex validation)
- os (for file handling)

# How to Run:
- Make sure Python is installed
- Save the file as http://main.py (or any name)
- Run the program: Follow the on-screen menu options
- Example Operations
- Register a new user
- Login with credentials
- Reset password
- Delete account




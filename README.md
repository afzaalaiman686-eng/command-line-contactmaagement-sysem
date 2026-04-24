
# Contact Management System (Python)
Intoduction:
This is a simple Contact Management System built in Python.
It allows users to store, manage, and organize contact details such as name, phone number, email, city, and company.
The program runs in the terminal and saves data using a JSON file.
#Features:
Add new contacts
View all contacts in table format
Search contacts (by name, phone, or email)
Filter contacts (by city or company)
Update existing contacts
Delete contacts
Data stored permanently in contacts.json
#Technologies Used:
Python
JSON (for data storage)
Regular Expressions (for validation)
#How to Run:
Open terminal / Jupyter Notebook
Run the Python file:
Bash
python file_name.py
Choose options from the menu (1–7)
#Data Structure:
Each contact contains:
ID
Name
Phone
Email
City
Company
Example:
JSON
{
  "id": 1,
  "name": "Ali Ahmed",
  "phone": "03001234567",
  "email": "ali@gmail.com",
  "city": "Islamabad",
  "company": "TechSoft"
}
#Validation Rules:
Phone must contain digits only (min 10 digits)
Email must follow valid format
#Future Improvements:
GUI version (Tkinter)
Database integration (SQLite)
Login system
OOP-based structure

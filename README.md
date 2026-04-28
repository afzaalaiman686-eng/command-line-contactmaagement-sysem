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

# Custom Data Encryption & Decryption Tool Task 3
# Project Description:
- This project is a Python-based CLI (Command Line Interface) application designed to encrypt and decrypt data using a custom-built algorithm. It simulates basic real-world data protection techniques by converting readable text into an unreadable format and then reversing it back when needed.
- The system also supports saving encrypted data into a file and loading it later for decryption.
# Objective
The main objective of this project is to:
- Understand how data encryption and decryption works
- Implement a custom encryption algorithm instead of using built-in libraries
- Practice file handling in Python
- Build a modular and user-friendly CLI application
- Simulate real-world data security concepts in a simple way
# Features:
- Encrypt plain text using a custom algorithm
- Decrypt encrypted text back to original
- Key/password-based encryption for extra security
- Save encrypted data into a JSON file
- Load encrypted data from file and decrypt it
- Timestamp included for saved data
- Menu-driven CLI interface
- Exception handling for error management
# Encryption Logic (Simple Explanation)
The encryption process uses multiple steps:
1. Each character in the text is shifted using a key (password)
2. The shifted text is then reversed
3. This makes the encrypted output difficult to read
Decryption performs the reverse steps:
1. Reverse the encrypted text
2. Shift characters back using the same key
3. Original text is restored
4. # Technologies Used
- Python
- JSON (for file storage)
- Datetime module
  # How to Run:
1. Open the project in Jupyter Notebook or any Python IDE
2. Run all the cells
3. Execute the main program
4. Choose options from the menu:
   - Encrypt data
   - Decrypt data
   - Save data
   - Load data
   - Exit
# Requirements:
- Python 3.x
- Basic understanding of functions and loops
  # Conclusion:

- In this project, we successfully developed a custom data encryption and decryption tool using Python. The program demonstrates how basic encryption techniques like character shifting and string manipulation can be combined to protect data.

This project helped in understanding:
- Core concepts of encryption and decryption
- Importance of data security
- File handling and modular programming
# Future Improvements
- Add GUI interface using Tkinter
- Implement multi-layer encryption
- Support encryption of files (images, documents)
- Improve algorithm complexity for stronger security.

# System Log Analyzer & Report Generator Task 4 :

# Project Description:
- This project is a Python-based CLI (Command Line Interface) application that analyzes system or application log files. It reads log data, identifies different types of log messages (ERROR, WARNING, INFO), and generates a summary report.
- The tool also allows users to search for specific keywords in logs and filter logs based on their level, making it useful for debugging and monitoring purposes.
#  Objective:

The main objectives of this project are:

- To understand how log files are used in real-world systems
- To implement log analysis using Python
- To use regular expressions (regex) for pattern detection
- To practice file handling and data processing
- To build a modular and user-friendly CLI tool
- To generate meaningful reports from raw log data
# Features:

- Load log files (.txt or .log)
- Analyze logs for:
  - ERROR messages
  - WARNING messages
  - INFO messages
- Count occurrences of each log type
- Extract timestamps from logs
- Search logs using keywords (case-insensitive)
- Filter logs by level (ERROR/WARNING/INFO)
- Generate summary report
- Save report in TXT and CSV formats
- Menu-driven CLI interface
- Exception handling for file errors
# How It Works:

1. User loads a log file
2. The program reads it line by line
3. It uses regex to detect log levels
4. Counts total number of errors, warnings, and info logs
5. Allows searching and filtering logs
6. Generates a report and optionally saves it
# Technologies Used;

- Python
- Regular Expressions (re module)
- CSV module
- File Handling
# How to Run:

1. Open the project in Jupyter Notebook or any Python IDE
2. Run all the cells
3. Start the program
4. Choose options from the menu:
   - Load File
   - Analyze Logs
   - Search Logs
   - Filter Logs
   - Generate Report
   - Exit
# Requirements:

- Python 3.x
- Basic knowledge of loops and functions
# Conclusion:

In this project, we successfully built a system log analyzer that can process and analyze log files efficiently. The tool helps in identifying errors, warnings, and informational messages, which are essential for debugging and system monitoring.

This project improved understanding of:

- Log file structure and importance
- Data parsing using regular expressions
- File handling and modular programming
- Building practical tools used in real-world software systems

Overall, this project provides a simple yet effective simulation of how developers and system administrators analyze logs to maintain and improve applications.
# Future Improvements:

- Add graphical visualization (charts using matplotlib)
- Export reports as PDF
- Real-time log monitoring
- Highlight critical errors automatically
- Develop GUI version using Tkinter.

  # Automated Bulk Email Sender with Templates Task 5 :
# Project Overview:
- This project is a Python-based automated email sending system that allows users to send bulk emails to multiple recipients using predefined templates. It supports personalization, CSV-based contact loading, and email history tracking. The system is designed to simulate real-world email automation used in marketing, notifications, and organizational communication.
# Objective:
- To automate the process of sending emails to multiple users.
- To use SMTP protocol for email delivery.
- To implement reusable email templates with dynamic placeholders.
- To personalize emails using recipient data (name, company, etc.).
- To load contacts from CSV/JSON files.
- To track email sending history (success/failure with timestamp).
- To handle errors and ensure smooth execution.
  # Features:
- Bulk email sending using SMTP
- Load contacts from CSV or JSON files
-  Predefined email templates
-  ersonalized emails using placeholders like {name} and {company}
-  mail history tracking (Sent / Failed / Timestamp)
-  etry handling for failed emails
-  imple CLI-based menu system
-  ecure login using Gmail App Password
# Technologies Used:
- Python 3
- smtplib (SMTP protocol)
- csv module
- json module
- datetime module

# CSV File Format:
Your contacts file should look like this:
- Csv
- name,email,company
- Ali,ali@gmail.com,HK Academy
- Sara,sara@gmail.com,Tech Corp
- Ahmed,ahmed@gmail.com,Soft Solutions
  # How to Run the Project:
- Step 1: Create Contacts File
Create a contacts.csv file with recipient details.
- Step 2: Run the Program
Open Jupyter Notebook or Python file and execute:
Python
menu()
- Step 3: Follow Menu Options
Load Contacts
Send Bulk Emails
View History
Exit
  # Email Templates Example:
Python
templates = {
    "welcome": "Hello {name},\nWelcome to {company}! We are glad to have you.",
    "promotion": "Hi {name},\nSpecial offers available for {company}."
}
# Important Note:
Gmail requires App Password for SMTP login.
Normal Gmail password will NOT work.
Enable 2-Step Verification before using the system.
# Future Improvements:
- GUI version using Tkinter
- Email scheduling feature
- HTML email templates with styling
- File attachments support (PDF, images)
- Dashboard for analytics


# PDF Report Generator Task 6 :
# Description:
- This project is a Python-based application that generates professional PDF reports using user-provided data. It supports both student and company reporting formats.
# Features:
- Add data manually through console
- Generate Student Reports
- Generate Company Reports
- Structured table-based PDF output
- Automatic timestamp generation
- Clean and professional formatting
- Simple menu-driven interface
# Technologies Used:
- Python 3
- ReportLab library
- Jupyter Notebook
  # Installation:
- Install required library:
Bash
pip install reportlab
#  How to Run:
- Open Jupyter Notebook or Python environment
- Run all code cells
- Use the menu system:
- Add Data
- Generate Student Report
- Generate Company Report
- Exit
  # Output:
- PDF files are saved in the reports/ folder
- Each file has a unique timestamp-based name
- Example:

Student_Report_20260427_153012.pdf

# Excel Data Cleaning & Analysis Tool Task 7 :
# Description:
T- his is a Python-based CLI application that allows users to load, clean, analyze, and save Excel data. The tool is designed to simulate real-world data analysis tasks commonly performed in organizations.
# Features:
- Load Excel (.xlsx) files
- Clean data:
- Remove duplicates
- Handle missing values (mean, median, custom, drop)
- Standardize column names
- Perform data analysis:
- Summary statistics
- Column information
- Grouping data
- Filter and search records (case-insensitive)
- Save cleaned data to Excel/CSV
- Generate summary reports (TXT)
# Technologies Used:
- Python
- Pandas
- NumPy
- Matplotlib 
# How to Run:
- Install required libraries:
Bash
pip install pandas numpy matplotlib openpyxl
- Open Jupyter Notebook or Python environment
- Run all cells step-by-step
- Use the menu system to:
Load file
Clean data
Analyze data
Filter/search
Save output
 # Future Improvements:
- GUI using Tkinter
- Data visualization dashboards
- Export reports to PDF
- Support for multiple file uploads
- Automatic data issue detection


# Bulk File Renamer & Smart Organizer Task 8 :

## Overview:
- This Python project is a CLI-based automation tool that helps users rename and organize multiple files efficiently. It simulates real-world file management systems used in automation workflows.
## Features:

### Bulk File Renaming
- Add prefix or suffix
- Replace text in filenames
- Auto numbering system (file_1, file_2, ...)

### File Organization
- Organize files by extension (PDF, JPG, MP4, etc.)
- Automatically creates folders

### Preview System
- Shows before/after file names
- Confirms changes before execution

### Logging System
- Stores all operations in CSV file
- Tracks:
  - Old filename
  - New filename
  - Timestamp
  - Action type

### Safety Features
- Prevents file overwriting
- Error handling for missing or locked files

---

## Technologies Used
- Python 3
- os module
- shutil module
- datetime module
- csv module
##  How to Run:
1. Open Jupyter Notebook or Python IDE
2. Copy the code into cells or script
3. Run the `main()` function
4. Enter folder path when prompted
## Example Usage:
- Before:
# Conclusion :
- This project is a Python-based automation tool for bulk file renaming and organization.
- It helps manage large numbers of files efficiently and saves manual effort.
- Supports multiple renaming options like prefix, suffix, replacement, and auto-numbering.
- Organizes files into folders based on file extensions.
- Includes a preview feature to review changes before applying them.
- Maintains a log of all operations with timestamps for tracking.
- Implements error handling to avoid crashes and file conflicts.
- Uses Python libraries like os, shutil, and csv for file management and logging.
- Demonstrates real-world automation concepts and modular programming.

# Dynamic Web Scraper for Jobs Task 9 :

## Overview:
- This project is a Python-based CLI tool that extracts data from websites such as jobs listings, product pages, or news sites. It automates data collection and allows users to search, filter, and store the extracted information.
##  Features:
### Web Scraping
- Uses requests and BeautifulSoup
- Fetches real-time data from websites
- Handles pagination (multiple pages)
### Data Extraction
Extracts:
- Title / Name
- Author / Company / Source
- Links
- Other relevant details
### Search & Filter
- Search data using keywords
- Filter results easily
### Data Storage
- Save data in:
  - JSON format
  - CSV format
### Menu System
- Scrape Data
- Search Data
- Save Data
- Exit
## Technologies Used
- Python 3
- requests
- BeautifulSoup (bs4)
- csv module
- json module

# Future Improvements
- Add Selenium for dynamic websites
- GUI using Tkinter
- Export to Excel
- Email notifications
- Scheduled scraping

 #  Project Conclusion:
- The Dynamic Web Scraper project successfully demonstrates the practical application of web scraping techniques for real-time data collection. The system efficiently extracts and organizes information from web pages, reducing the need for manual data gathering.
- By integrating features such as pagination, search functionality, and data storage, the project showcases how raw web data can be transformed into structured and useful information. It also highlights the importance of error handling and clean data extraction in building reliable scraping tools.

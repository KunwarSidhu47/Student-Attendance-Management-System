# Attendance Management System

Attendance Management System is a console-based application developed in C++ to record, view, and manage student attendance efficiently using file handling and sorting algorithms.

## Features

- Add and store student attendance records  
- Display all records from the database  
- Search records by name  
- Sort records alphabetically using Insertion Sort  
- Persistent data storage using text files  
- Default login credentials: **Username:** admin | **Password:** admin

## Tech Stack

C++, File Handling, Object-Oriented Programming (OOP), Insertion Sort Algorithm, Console I/O

## How to Run

1. Compile the code using any C++ compiler:  
   `g++ attendance.cpp -o attendance`

2. Run the executable:  
   `./attendance`

3. Login using the default credentials:  
   `Username: admin`  
   `Password: admin`

## Project Structure

```
.
├── attendance.cpp      # Main source file  
├── record.txt          # Stores attendance records  
└── README.md           # Project info
```

## How It Works

- User logs in with default credentials  
- Inputs student name, roll number, and attendance  
- Data is saved to a text file for persistence  
- Records can be viewed or sorted alphabetically  
- Simple CLI menu allows interaction with the system

## Future Improvements

- Add editing and deletion of records  
- Implement monthly attendance summaries  
- Include subject-wise tracking and reports

## License

This project is licensed under the MIT License.

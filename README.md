# 📚 Crime Record Management System

## 🚀 Overview
A desktop-based application for managing and displaying crime records, built with *Python Tkinter* (frontend) and *SQL Server* (backend).

---

## 🛠️ Technologies Used
- *Frontend:* Python 3.x, Tkinter, pyodbc  
- *Backend:* Microsoft SQL Server  

---

## 🌟 Features
- View crime records in a table format (Treeview)
- Fetch records from the database with a button click
- Simple, user-friendly GUI
- Exception handling for database operations

---

## 🏗️ System Structure
Crime Record Management System/
├── README.md
├── crime_management_system.py # Tkinter frontend
└── sql/
└── crime_table.sql # SQL backend script

---

## 🔐 Setup Instructions
1. Create the proj database and Crime table in SQL Server.  
2. Update the *server name* in the Python script to match your environment.  
3. Install required Python libraries (pyodbc).  
4. Run the Python script to launch the GUI.

---

## 💾 Backend Highlights
- Database: proj  
- Table: Crime with fields: CrimeID, Description, Location, Date.

---

## 💡 Future Enhancements
- Add search and filter features  
- Implement CRUD operations  
- Enhance user authentication and design

Part of the Object-Oriented Programming course at Afeka College of Engineering.

This project is a simple College Management System built in Java using Object-Oriented Programming principles.
It allows users to manage data related to lecturers, study departments, and academic committees, and persist this data using binary file serialization.

Features:
- Add and manage Lecturers (regular, Doctors, and Professors).
- Manage Departments and assign lecturers to them.
- Manage Committees:
  - Add committees with chairmen.
  - Add/remove lecturers from committees.
  - Update chairman
  - Clone a committee.
  - Compare two committees based on number of lecturers and articles.
- Show average salaries (general or per department).
- Compare between Doctors/Professors based on number of articles.
- Save and load data from a binary file.

Technologies Used:
- Serialization (File I/O).
- Custom Exception Handling.
- Object-Oriented Design (Encapsulation, Inheritance, Polymorphism).
- Interfaces and Abstract Design.

Data Persistence:
- On startup, the system tries to load previous data from a binary file.
- If the file doesn't exist, it starts fresh by asking the user to input the college name.
- When exiting, the current data is automatically saved to a file.

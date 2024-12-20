LIBRARY MANAGEMENT SYSTEM

Use the following credentials to access the system as either an Admin or a Member.

- Admin Login:
  
   User ID: U001
  
   Password: 123

- Member Login:
  
    User ID: U002
  
    Password: 456


  
The Library Management System (LMS) seeks to modernize library book, user, and borrowing operation administration. As library operations expand, traditional hand-operated systems are prone to data loss, inefficiency, and difficulty expanding. Using Python, this project develops an automated system with fundamental capabilities such as book and user administration, role-based authentication, borrowing and returning books, and data storage via CSV files, thereby addressing these constraints. Even with larger datasets, the system guarantees good performance by using effective algorithms such as binary search for fast user location and merge sort for book sorting. Exceptional handling improves resilience and guarantees that the software elegantly manages faulty inputs and file faults without stopping. While members may browse for books, borrow currently available titles, and manage their profiles, administrators can add, edit, or delete books and users. Following Object Oriented Programming (OOP) principles, the system's modular design guarantees scalability, maintainability, and code organization. This project shows how to provide dependable and practical answers for real-world issues by integrating theoretical ideas such as algorithmic analysis, error handling, and data management into pragmatic applications. 

Functional Requirements
1.	Admin Features: 
-	Add, modify, and delete books.
-	Manage user records, including adding, updating, and deleting.
-	Sort all books and users.
-	Manage book borrowing and return policies.
2.	Member Features: 
-	Sort and look for books by author, title, book ID or stock availability
-	Borrow and return books.
-	Update or modify profile data.
3.	System Features: 
-	Role-based authentication for admin and members.
-	Data persistence using CSV files to store books, users, and borrowing records
-	Organize books according to qualities such title, stock, etc.
  
Non-Functional Requirements
1.	Scalability: The system should manage a lot of users and books without compromising speed.
2.	Efficiency: Operations of sorting and searching have to be effective.
3.	Usability: The terminal-based interface of the system must be straightforward and easy to use.
4.	Security: Role-based access control meant to stop illegal activity.
5.	Reliability: Data has to be kept constantly and stay available even after systems restarts.
6.	Maintainability: Maintaining simplicity and scalability, the system should be built in modules to facilitate changes.

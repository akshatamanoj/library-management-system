# Libraray-Management-Project
This is Library Management project which uses JAVA (GUI and Backend) and MYSQL (Database).

Scope and Objective of Project:-

The Library Management System allows the Librarian to login using a username and a password to access the system.

![Screenshot 2024-10-10 112235](https://github.com/user-attachments/assets/6c879b01-5f92-4510-ae72-7543673f261e)


The Librarian can perform many functions after logging into the system, such as, adding a new book, adding a new student, issuing a book, returning (accepting) a book, and view transactions (statistics about issuing and returning of books).

![Screenshot 2024-10-10 112243](https://github.com/user-attachments/assets/897fb697-2e1f-4201-9778-cef855e2c30f)

In the System, every book has an ISBN no., Name, Author, and a Price.


![Screenshot 2024-10-10 112251](https://github.com/user-attachments/assets/8d50af44-5482-4eed-898d-0e5b0f354fa8)

Every student has a student ID, Name, Course, Branch, and Year.

![Screenshot 2024-10-10 112301](https://github.com/user-attachments/assets/c9e32103-1407-40cf-b074-bb2da281c8a8)

While issuing a book the Librarian must enter the ISBN number of the book, the ID of the student, and the issue date.

![Screenshot 2024-10-10 112318](https://github.com/user-attachments/assets/5c08bd50-0710-4dd1-8c7f-e81e61a8c0e2)


When the book is returned, student ID is entered by the Librarian to get details of the book issued, further the return date is mentioned and the book’s status is changed to returned/available.

![Screenshot 2024-10-10 112327](https://github.com/user-attachments/assets/3ad86c0f-2f5e-4b97-b7af-5384fb2df51c)




# Database
MYSQL has been used for database in this project. It contains 4 tables :-

Book : This table contains fields like ISBN, Title, Author, Quantity and Price.

Admin: This table contains fields like User_id and Password.

Student: This table contains fields like Student_ID, Name, Course, Branch and Year.

Record: This table contains fields like Return_Date, ISBN, Student_id and Issue_Date.

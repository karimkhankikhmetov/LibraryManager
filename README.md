A simple command-line Java application for managing a library system with two types of users: Students and Teachers. This project demonstrates object-oriented principles.

Features
User registration and login with role checking

Different roles:

Students can view, borrow, and return books

Teachers can do everything students can, but also add and remove books

Tracks which books are available

Console-based interface

User Roles
Student: Can borrow and return books

Teacher: Can borrow, return, add, and remove books

Classes.
Book: Stores book details like title, author, ISBN, and availability status

User (abstract, becuase Teacher and Student have a lot of common things, yet there are some differences): Base class extended by Student and Teacher classes

image.png contains the UML

Library: Handles all book and user management

LibraryApp: Main class that runs the console interface




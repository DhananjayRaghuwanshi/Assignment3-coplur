# Assignment3-coplur
You are tasked with designing a Library Management System for a small library using Object-Oriented Programming (OOP) principles. The purpose of the system is to manage a simple collection of books and handle basic library operations. This system must showcase your understanding of classes, objects, abstraction, polymorphism, interfaces, and exception handling.
________________________________________
System Requirements:
1.	Add Books
o	Design a feature that allows a librarian to add books to the system.
o	Each book must have the following details:
	A unique identifier (e.g., Book ID)
	Title
	Author
	Availability status (whether the book is available for borrowing)
2.	Borrow Books
o	Create a mechanism for users to borrow books using the unique Book ID.
o	Ensure that a book cannot be borrowed if it is not available.
o	Provide appropriate feedback in case of errors, such as invalid Book IDs or unavailability.
3.	Return Books
o	Implement a way for users to return borrowed books using the unique Book ID.
o	Verify that the returned book belongs to the library and was borrowed.
o	Handle scenarios where users attempt to return invalid or non-borrowed books.
4.	View Available Books
o	Provide a method to display all books that are currently available for borrowing.
o	Include the book's details, such as its ID, title, and author.
5.	Logging System
o	Introduce an interface for logging all actions performed in the system, such as adding books, borrowing, and returning.
o	Implement the interface to log messages that can be displayed to the librarian or user.
6.	Error Handling
o	Handle edge cases and errors gracefully, such as:
	Trying to add a book with invalid details (e.g., empty title or non-unique ID).
	Borrowing a book that is already borrowed or does not exist.
	Returning a book that is not part of the library.


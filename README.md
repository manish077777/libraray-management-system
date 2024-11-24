# libraray-management-system

This Python code implements a Library Management System using Tkinter for the graphical user interface (GUI) and SQLite for database management. The system allows users to add, update, delete, and search for books in a library.

Key Components:
SQLite Database:

The system uses an SQLite database (library.db) to store book information in a table books with columns: id, title, author, genre, and isbn.
Tkinter GUI:

The GUI is built using Tkinter, providing input fields for book details (title, author, genre, ISBN), and buttons for adding, updating, deleting, and searching books.
A listbox is used to display the current book records.
Functions:

Add Book: Adds a new book to the database after validating input fields.
Search Book: Allows users to search for books by title, author, genre, or ISBN.
Show Books: Displays all books from the database in the listbox.
Update Book: Updates the details of a selected book.
Delete Book: Deletes the selected book from the database.
Clear Entries: Clears the input fields after each operation.
Database Interaction:

SQLite Commands: The system uses SQL queries to interact with the database, including INSERT, SELECT, UPDATE, and DELETE.
User Feedback:

Messagebox is used to show success or warning messages for each action (e.g., adding, updating, or deleting a book).
Initialization:

The database table is created if it doesn't exist.
The listbox is populated with books upon starting the application.
Closing:

The connection to the SQLite database is closed when the application ends.

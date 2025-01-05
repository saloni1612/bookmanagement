
Library Book Management System
This project is a Library Book Management System implemented in C++. It allows users to manage a collection of books in a library, perform various operations like adding books, viewing details, searching by author or title, and more. The program uses object-oriented programming (OOP) concepts such as classes and encapsulation.

Features
Add Book Information
Allows the user to add details about a new book, including:

Book name
Author name
Book ID
Price
Issued status (yes/no)
Display All Books
Lists all the books currently stored in the library with their details.

Search Books by Author
Displays all books written by a specified author.

Count of Books
Displays the total number of books available in the library.

Search Book by Title
Finds and displays information about a book based on its title.

Search Book by ID
Finds and displays information about a book based on its unique ID.

Exit
Exits the program.

Key Functions
addbookinfo()
Collects details about a book from the user.

displaybookinfo()
Prints details about a book.

addbook()
Adds a book to the library.

displayallbooks()
Displays all books in the library.

displaybooksbyauthor(char* author)
Finds and displays books by the specified author.

displaybookbyname(char* bookname)
Finds and displays a book by its title.

displaybookbyid(int id)
Finds and displays a book by its unique ID.

Notes
The library can store up to 100 books.
Input validation is minimal, so ensure to enter valid data.
The program uses cin.ignore() and cin.getline() for reading strings to handle buffer issues.
The search by author and title is case-sensitive.

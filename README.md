**Library Book Management System**

This project is a Library Book Management System implemented in C++. It allows users to manage a collection of books in a library, perform various operations like adding books, viewing details, searching by author or title, and more. The program uses object-oriented programming (OOP) concepts such as classes and encapsulation.

_Features_
1.Add Book Information
Allows the user to add details about a new book, including:
Book name
Author name
Book ID
Price
Issued status (yes/no)

2.Display All Books
Lists all the books currently stored in the library with their details.

3.Search Books by Author
Displays all books written by a specified author.

4.Count of Books
Displays the total number of books available in the library.

5.Search Book by Title
Finds and displays information about a book based on its title.

6.Search Book by ID
Finds and displays information about a book based on its unique ID.

7.Exit
Exits the program.

_Key Functions_
1.addbookinfo()
Collects details about a book from the user.

2.displaybookinfo()
Prints details about a book.

3.addbook()
Adds a book to the library.

4.displayallbooks()
Displays all books in the library.

5.displaybooksbyauthor(char* author)
Finds and displays books by the specified author.

6.displaybookbyname(char* bookname)
Finds and displays a book by its title.

7.displaybookbyid(int id)
Finds and displays a book by its unique ID.

Notes
The library can store up to 100 books.
Input validation is minimal, so ensure to enter valid data.
The program uses cin.ignore() and cin.getline() for reading strings to handle buffer issues.
The search by author and title is case-sensitive.

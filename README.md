Library Database SQL Queries

Overview
This repository contains SQL queries designed to interact with a library database. The database consists of four main tables: Authors, Books, Borrowers, and Loans. The provided queries cover various common use cases, such as retrieving book information, author statistics, borrower details, and book availability.

Database Structure
The following tables are used in the queries:
- Authors: Contains details about book authors.
- Books: Holds information about available books, including their genre and publication year.
- Borrowers: Stores details about people who borrow books.
- Loans: Tracks the books borrowed, including the loan and return dates.

 Queries Included
Here is a list of the queries included in the file:

1. Find all books by a specific author (e.g., J.K. Rowling)
   Retrieves a list of books by a particular author.

2. List all books currently borrowed and their borrowers
   Shows which books have been borrowed and by whom.

3. Get the number of books each author has written
   Counts the total books written by each author.

4. Find all borrowers who have not returned their books yet 
   Displays borrowers who currently have books checked out.

5. Get the details of books published before a certain year (e.g., 1950) 
   Retrieves books published before a specified year.

6. Find all authors who have written more than one book 
   Lists authors who have written multiple books.

7. Retrieve the total number of books and borrowers 
   Provides the total number of books and active borrowers.

8. Get a list of books and their availability status
   Shows whether a book is available or currently borrowed.

9. Find books borrowed by a specific borrower (e.g., 'John')  
   Retrieves the list of books borrowed by a particular borrower.

How to Use this query
- Load the SQL queries from the `library_sql_queries.txt` file into your SQL environment.
- Execute the queries individually or as needed depending on the operation you want to perform on the database.

Contact
For any questions or further details, feel free to reach out through GitHub Issues or contact me directly ediomoetesin40@gmai.com


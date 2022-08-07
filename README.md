# Books-Library-For-GSG
Final Project in Python for Information Technology Foundations and Coding Course - GSG Foundation
Requirements:

● Client

○ Properties: 

  ■ id 
  ■ full_name 
  ■ age 
  ■ id_no 
  ■ phone_number 
● Librarian

○ Properties: 

  ■ id 
  ■ full_name 
  ■ age 
  ■ id_no 
  ■ emplyment_type(Full/part) 
● Book

○ Properties: 

  ■ id 
  ■ title 
  ■ description 
  ■ author 
  ■ status(Active-Inactive) 
● Borrowing Order:

○ Properties: 

  ■ id 
  ■ date 
  ■ client_id 
  ■ book_id 
  ■ status (Active - Expired - Cancelled) 
● Main File

○ Properties: 

  ■ list of clients 
  ■ list of librarians 
  ■ list of books 
  ■ list of borrowed_orders 
  ■ total_borrowed_books 
  ■ total_available_books 
  ■ total_borrowed_orders
Scenario:

Create a new client and add it to the client's list.
Create a new librarian and add it to the librarian’s list.
Create more than 3 books and add them to the book’s list.
Ask Librarian to borrow a book
The librarian will ask you which book you want to borrow.
Checkbook status, Check if the box is active for borrowing or not, 7. if active the librarian will ask you about your information (id_no)
The librarian will check if the client exists in the system or not.
if it exists the librarian will create a borrow_order with the selected book and the selected client
Return book to librarian will be like that the client enters borrowing_id to the librarian to return it.

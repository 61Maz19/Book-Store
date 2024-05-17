# Book-Store
A simple book management system in C++

## System properties
1. **Menu-Driven Book Management System:**
   - The program presents a menu-driven interface for managing books.
   - Users can perform various actions related to book data.

2. **Key Menu Options:**
   - **1. Entry of New Book:**
     - Creates a new `book` object and feeds its data (author, title, publisher, price, and stock).
   - **2. Buy Book:**
     - Asks for the title and author of a book.
     - Searches for the book in the existing list.
     - If found, allows the user to buy a specified number of copies.
   - **3. Search For Book:**
     - Asks for the title and author of a book.
     - Searches for the book in the existing list.
     - If found, displays its details.
   - **4. Edit Details Of Book:**
     - Asks for the title and author of a book.
     - Searches for the book in the existing list.
     - If found, allows editing of its details.
   - **5. Show All Books:**
     - Displays details of all existing books.
   - **6. Show Sold Book with Quantity:**
     - Displays the title and number of sold copies for each book.
   - **7. Total Profit:**
     - Shows the total profit earned from book sales.
   - **8. Exit:**
     - Exits the program.

3. **Implementation Details:**
   - An array of pointers (`B`) is used to store book objects.
   - The `book` class methods (`feeddata()`, `buybook()`, etc.) are invoked based on user choices.

## Code components
1. **Class Definition:**
   - The class is named `book`.
   - It has private member variables: `author`, `title`, `publisher`, `price`, `stock`, and `sold`.
   - There's a constructor (`book()`) that initializes these variables.
   - A static integer variable `Total_profit` is also declared.

2. **Member Functions:**
   - `feeddata()`: Reads input for author, title, publisher, price, and stock.
   - `editdata()`: Allows editing of author, title, publisher, price, and stock.
   - `showdata()`: Displays information about the book.
   - `search(char[], char[])`: Searches for a book based on title and author.
   - `buybook()`: Handles book purchases, updating sold copies and profit.
   - `soldBook()`: Displays the title and number of sold copies.

3. **Usage:**
   - You can create an instance of the `book` class and use its member functions to manage book data.

**Mohammad Ali Zaid**

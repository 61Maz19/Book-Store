# Book-Store
A simple book management system in C++


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

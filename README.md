Library Manager App - Python & JSON
A simple Python-based Library Manager application to manage a personal book collection. It allows you to add, remove, search, and display books, along with providing statistics about your reading progress. The data is saved in a JSON file for persistent storage.

Features
Add Books: Add a new book with title, author, year, genre, and reading status.

Remove Books: Remove a book by its title.

Search Books: Search books by title or author.

Display All Books: View a list of all books in your collection along with their reading status.

Statistics: View the total number of books in the collection and the percentage of books you’ve read.

Data Storage: All book details are stored in a JSON file for easy data management and retrieval.

Requirements
Python 3.x

Basic knowledge of Python and JSON files

How to Run
Clone the repository (or download the script):

bash
Copy
git clone <https://github.com/syedjalees/PY-Personal-Library-Manager-sirZia>
cd <PY-Personal-Library-Manager-sirZia>
Install dependencies (if any, though this project doesn’t require external libraries).

Run the script:

bash
Copy
python library_manager.py
The program will prompt you with the following menu to choose actions:

plaintext
Copy
Welcome to the Library Manager
Menu:
1. Add a book
2. Remove a book
3. Search the library
4. Display all books
5. Display statistics
6. Exit
Choose options as per the on-screen instructions to manage your library.

Data Storage
All book details are saved in a library.txt file in JSON format. The data file will be created automatically if it doesn't exist.

Example JSON File Structure
json
Copy
[
    {
        "title": "The Great Gatsby",
        "author": "F. Scott Fitzgerald",
        "year": "1925",
        "genre": "Classic",
        "read": true
    },
    {
        "title": "To Kill a Mockingbird",
        "author": "Harper Lee",
        "year": "1960",
        "genre": "Fiction",
        "read": false
    }
]
Key Functions
add_book(): Adds a new book to the library.

remove_book(): Removes a book by its title.

search_library(): Searches books by title or author.

display_all_books(): Displays all books in the library.

display_statistics(): Displays statistics about the total number of books and reading progress.

Contributing
Feel free to contribute to this project! You can fork the repository, make changes, and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

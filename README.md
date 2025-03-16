# Library Manager

## Overview
The **Library Manager** is a simple Python project that allows users to manage a collection of books. Users can add, remove, search, display, and view statistics of books stored in a library file.

## Features
- **Add a Book**: Users can add books with details like title, author, year, genre, and reading status.
- **Remove a Book**: Users can remove books by their title.
- **Search for a Book**: Users can search books by title or author.
- **Display All Books**: Lists all books stored in the library.
- **Show Statistics**: Displays the total number of books and the percentage of books read.
- **Persistent Storage**: Books are stored in a `library.txt` file using JSON format.

## Requirements
- Python 3.x

## Installation
1. Clone or download the repository.
2. Ensure Python 3.x is installed.
3. No external dependencies are required.

## Usage
Run the script using the following command:
```sh
python library_manager.py
```

### Menu Options:
1. Add a book
2. Remove a book
3. Search the library
4. Display all books
5. Display statistics
6. Exit

## File Structure
```
/library_manager
│── library_manager.py  # Main script
│── library.txt         # Stores book data (generated automatically)
│── README.md           # Project documentation
```

## Data Storage Format
The books are stored in `library.txt` in the following JSON format:
```json
[
    {
        "title": "Book Title",
        "author": "Author Name",
        "year": "2023",
        "genre": "Fiction",
        "read": true
    }
]
```

## License
This project is open-source and free to use.

## Contributions
Feel free to contribute by improving the code or adding new features. Fork the repository and submit a pull request!

## Contact
For any questions or suggestions, reach out via GitHub issues or email.


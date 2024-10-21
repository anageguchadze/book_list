# Django Book and Author Management Application

This is a simple Django-based web application for managing books and authors. The application allows users to view a list of books, details about individual books, and their associated authors.

## Features

- **View All Books**: Display a list of all books in the database.
- **Book Details**: View details of a specific book, including the title, publication date, and author.
- **Author Management**: Each book is linked to an author, and authors have associated biographies.

## Models

### Author

- `name`: The name of the author (maximum 50 characters).
- `biography`: A detailed biography of the author.

### Book

- `title`: The title of the book (maximum 100 characters).
- `publication_date`: The date the book was published.
- `author`: A foreign key linking each book to an author.

## Installation and Setup

### Prerequisites

- Python 3.x
- Django 4.x or later
- A virtual environment (recommended)

### Steps to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/anageguchadze/book_list

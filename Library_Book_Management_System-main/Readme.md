# Library Book Checkout System

This project is a RESTful API for managing a library book checkout system. It allows users to add, delete, and modify books and users, as well as check out and return books.

## Prerequisites

Before running the application, ensure you have the following installed:

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone the repository:
    git clone https://github.com/EniyanCSE/Library_Book_Management_System.git
    (unzip the node files and paste it in the same directory)

2. Navigate to the project directory:
    cd Library_Book_Management_System

3. Install dependencies:
    npm install

## Usage

1. Start the server:
    node index.js

2. Access the API using a tool like Postman or curl:
    GET /api/books - Get all books
    POST /api/add_book - Add a new book
    PUT /api/edit_book/:id - Edit a book
    DELETE /api/delete_book/:id - Delete a book


## Excel Integration

- The application integrates with Excel files to store and update book information.
- Ensure you have a file named `data.xlsx` in the project directory to store book data.

## How to Run the Program

1. Make sure you have completed the installation steps mentioned above.
2. Start the server by running `node index.js` in the project directory.
3. Once the server is running, you can access the API endpoints using tools like Postman or curl as described in the "Usage" section.

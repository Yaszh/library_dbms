# Library Management System

This is a comprehensive Library Management System designed to facilitate efficient management of library resources and user transactions. The system includes a MySQL database schema and SQL queries for performing various library operations.

## Table of Contents

- [Features](#features)
- [Database Schema](#database-schema)
- [Queries](#queries)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- **Book Management:** Add, remove, and update book details such as ID, name, category, and publication year.
- **Author Management:** Manage author details including ID and name.
- **Lending System:** Track books lent to library members, along with lend and return dates.
- **Fine Management:** Record fines imposed on members for late returns.
- **Member Management:** Maintain records of library members, including ID, full name, email, joined date, and status.
- **Reservation System:** Allow members to reserve books if they are unavailable.
- **Payment Handling:** Record payments made by members for fines and lending fees.

## Database Schema

The database schema consists of eight tables:
- `book`
- `author`
- `book_author`
- `lend`
- `fine`
- `member`
- `reservation`
- `payment`

For detailed information about each table and its attributes, refer to the SQL file.

## Queries

Several SQL queries are provided to perform common library operations such as:
- Searching for books by author
- Retrieving author details for a given book
- Checking member fines
- Tracking book lending and reservations
- Updating lending records after book return

For detailed information on how to use these queries, refer to the [Approach Document](approach.docx) and click on view raw to get the exact document file in proper format.

## Usage

To use the Library Management System:
1. Import the provided SQL file into your MySQL database.
2. Execute the SQL queries to perform various library operations.
3. Customize the system as needed to fit your library's requirements.

## Contributing

Contributions are welcome! If you have suggestions or improvements for the project, feel free to submit a pull request.

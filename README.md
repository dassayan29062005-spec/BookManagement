# BookManagement

# Book Management System

A simple Java JDBC project that connects to a PostgreSQL database and performs CRUD operations on a `books` table.

## Features

* Insert a book record
* View all books
* Update book details
* Delete a book record

## Technologies Used

* Java
* JDBC
* PostgreSQL
* Supabase Database

## Database Table

```sql
CREATE TABLE books (
    id SERIAL PRIMARY KEY,
    title VARCHAR(255),
    author VARCHAR(255),
    price DECIMAL(10,2)
);
```

## Run the Project

1. Download the PostgreSQL JDBC Driver.
2. Compile the program:

```bash
javac -cp "lib/postgresql.jar" BookManagement.java
```

3. Run the program:

```bash
java -cp ".:lib/postgresql.jar" BookManagement
```

## Output

The program demonstrates:

* Database Connection
* Insert Operation
* Read Operation
* Update Operation
* Delete Operation

## Author

Sayan Das

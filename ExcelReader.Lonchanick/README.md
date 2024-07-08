# Excel to Database Application

## Requirements

This is an application that will read data from an Excel spreadsheet into a database.

- When the application starts, it should delete the database if it exists, create a new one, create all tables, read from Excel, and seed into the database.
- You need to use the EPPlus package for reading Excel files directly.
- You shouldn't convert the Excel data to JSON format before inserting into the database.
- You can choose SQLite or SQL Server (or MySQL if you're using a Mac) as your database.
- Once the database is populated, you'll fetch data from it and display it in the console.
- The application does not require any user input.
- Print messages to the console to inform the user about the current activities (e.g., reading from Excel, creating tables).
- The application will be designed for a specific table structure; it does not need to be dynamic.
- When submitting the project for review, include an `.xls` file that can be read by your application.


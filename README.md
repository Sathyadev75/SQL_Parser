# SQL_Parser
Python code to execute SQL CRUD operation using python and file handling.
SQL Parser and CRUD Operations for Contacts CSV
Welcome to the SQL Parser for contacts.csv!

This program allows you to:

Parse arbitrary SQL queries: Enter any valid SQL query involving the contacts.csv file, and the program will analyze its syntax and structure.
Perform CRUD operations: Create, Read, Update, and Delete records in the contacts.csv file using your parsed SQL queries.
Getting Started:

Install dependencies: You'll need a Python environment with the pandas .
Run the program: Execute python sql_parser.py in your terminal.
Enter your SQL query: Type in any valid SQL query that operates on the contacts.csv file. Supported tables, columns, and operations are listed below.
Supported Features:

Tables: contacts
Columns: name, email, phone1, phone2
Operations:
SELECT: Retrieve data from the table.
INSERT: Add new entries to the table.
UPDATE: Modify existing entries in the table.
DELETE: Remove entries from the table.
WHERE: Filter data based on conditions.

Example Usage:

Retrieve all contacts: SELECT * FROM contacts;
Add a new contact: INSERT INTO contacts (name, email, phone1, phone2) VALUES ('John Doe', 'johndoe@example.com', '1234567890', '');
Update a contact's phone number: UPDATE contacts SET phone1='9876543210' WHERE name='John Doe';
Delete a contact: DELETE FROM contacts WHERE email='johndoe@example.com';
Output:

The program will print the parsed representation of your SQL query, including the type of operation, affected table and columns, and any conditions or filters. Additionally, for CRUD operations, it will attempt to execute the query on the contacts.csv file and print the result (e.g., number of rows inserted, updated, or deleted).

Important Notes:

The program assumes the contacts.csv file exists in the same directory as the script.
Make sure your SQL queries are syntactically correct and adhere to the supported features.
The program performs basic validation but may not handle complex or edge-case queries.
Further Development:

This is a basic implementation and can be extended to support more features like different databases, joins, and data validation.
Feel free to modify and improve the code to suit your specific needs.
We hope this SQL parser helps you manage your contacts data efficiently!

For any questions or suggestions, feel free to reach out!

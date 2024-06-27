# Week 1: Introduction & Foundational Skills (Focus on Project Relevance)

## Question 1. Research  

### Imagine a dynamic website like an online store. How do you think SQL plays a role in managing data behind the scenes? Consider how product information, user accounts, and order details might be stored and accessed.

- SQL is essential for managing data in dynamic websites like online stores. It allows for the structured storage, retrieval, and manipulation of data such as product information, user accounts, and order details. SQL queries are used to fetch and display product data, manage user login credentials and account details, and ensure accurate order processing and inventory tracking. This ensures the website operates smoothly and efficiently, providing a seamless user experience.

## Question 1.2 
### Write a short explanation (3-5 sentences) in your document about the role of SQL in web applications.

SQL is essential for managing data in web applications like online stores. It stores and retrieves product information, user accounts, and order details. SQL queries display products, manage user data, and track orders. This ensures the website runs efficiently and provides a good user experience.

## Question 1.3 
### List 3 benefits of using SQL for web applications.

- Efficient Data Management: SQL allows for efficient storage, retrieval, and manipulation of large volumes of data, ensuring that web applications can handle numerous products, user accounts, and transactions seamlessly.

- Data Integrity and Security: SQL provides robust mechanisms for enforcing data integrity and security. It ensures that data is consistent, accurate, and protected from unauthorized access, which is critical for maintaining user trust and regulatory compliance.

- Scalability and Performance: SQL databases are designed to scale with the growing needs of a web application. They can handle increasing amounts of data and user requests without compromising performance, ensuring a smooth and responsive user experience.

## Question 1.4
### Think about efficiency, data organization, and data retrieval capabilities. Briefly explain each benefit in your document (1-2 sentences per benefit).

- Efficient Data Management: SQL allows for efficient storage, retrieval, and manipulation of large volumes of data, ensuring that web applications can handle numerous products, user accounts, and transactions seamlessly.

- Data Organization: SQL organizes data into tables with predefined relationships, making it easier to manage and maintain structured data. This organized approach simplifies complex queries and data analysis.

- Data Retrieval Capabilities: SQL provides powerful querying capabilities that enable fast and precise data retrieval. This ensures that web applications can quickly respond to user requests and deliver relevant information efficiently

## Question 1.5
### List any 3 Database Management Systems.

- MySQL
- PostgreSQL
- Microsoft SQL Server


## Part 2 
### Question 2.1 
### Think about how data is organized in rows and columns. In your document, define a database table and explain its similarity to a spreadsheet (2-3 sentences).

A database table is a collection of data organized in rows and columns. Each row represents a record, and each column represents a field within the record. This structure is similar to a spreadsheet where data is also arranged in rows and columns, making it easy to understand and manipulate.

## Question 2.2: Columns

### Consider different types of data like text, numbers, and dates. Define "columns" and provide an example with an explanation (2-3 sentences) in your document. Data Types: Why are data types important in a database? Briefly explain 3 common data types (e.g., Text, Number, Date).

In a database context, a column refers to a vertical arrangement within a table that stores specific types of data. Each column is designated to hold a particular data type, such as text, numbers, or dates. For instance, in a table storing customer information, the "Name" column would typically hold text data, allowing entries like "John Smith" or "Jane Doe".

## Question 2.3: Data Types
### Think about how data types ensure data integrity and efficient storage. Explain the importance of data types and provide brief explanations of 3 common types (2-3 sentences each) in your document.

- Text: Text data types are used for storing alphanumeric characters, strings, or textual data. They define the format and size of text entries, ensuring consistency and enabling text-specific operations like substring searches or text manipulation functions.

- Number: Numeric data types are essential for storing numerical values such as integers or floating-point numbers. They ensure that mathematical operations are performed accurately and efficiently, while also optimizing storage space based on the range and precision required for the data.

- Date: Date data types are used to store calendar dates, including both date and time information in some cases. They enable date-specific operations such as date arithmetic, comparisons, and formatting for various display purposes. Properly defining date formats helps maintain data consistency and facilitates chronological ordering of records.


## Part 3  Expense Tracker Database Design
### 3.1. Planning
To build an Expense Tracker application, we need to track various data points related to expenses. Here are at least five data points that are relevant to our project:

- Expense Amount: The amount of money spent on a particular expense.
- Date: The date when the expense occurred.
- Category: The category of the expense (e.g., Food, Transportation, Entertainment).
- Description: A brief description or note about the expense.
- Payment Method: The method of payment used for the expense (e.g., Cash, Credit Card, Debit Card).
- Vendor: The name of the vendor or merchant where the expense was made.
- User ID: The identifier for the user who logged the expense (useful for applications with multiple users).

## 3.2. Tables
- Considering the data points listed above, we can design a basic database schema with one main table named Expenses. Below is the structure for the Expenses table, including column names and data types:

![Alt text](images/tables.jpg)

## Define the columns needed for this table.
* Assign appropriate data types to each column based on the kind of data it will hold. (e.g., amount: number, date: date, category: text)
  
  In your document, create a table structure that includes:
* Table name (e.g., Expenses)
* Column names (e.g., expense_id, amount, date, category)
* Data type for each column (e.g., INT, DECIMAL, DATE, TEXT)

![Alt text](images/table2.jpg)

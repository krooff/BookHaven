Authors Table:
author_id serves as the primary key.
This table stores details about each author, and the author_id is referenced in the Books table.

Books Table:
Each book has a unique book_id. The author_id references the Authors table.
The stock_quantity column keeps track of how many copies are available in the store.
The price is defined as a decimal to allow for monetary values with two decimal places.

Customers Table:
The customer_id serves as the primary key. Customer information is stored here, including their name, email, and contact details.

Transactions Table:
Each purchase transaction is recorded here, associating a customer with the books they have purchased.

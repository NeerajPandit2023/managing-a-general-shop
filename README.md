# managing-a-general-shop
This program is a Python-based management system for a general shop. It allows the user to perform various operations related to customers, purchases, payments, and generating reports using a MySQL database.

The program starts by prompting the user for a password. If the correct password is entered, the user gains access to a menu with several options:

1. Daily Cash Customer: This option allows the user to enter the details of items purchased by a cash customer. The program prompts for the customer's name, the number of items purchased, and the details of each item (name, price, and quantity/weight). The information is then stored in the MySQL database.

2. Credit Customer: This option is similar to the previous one but is used for credit customers. In addition to entering the purchase details, the program also updates the due balance for the customer and stores the information in the database.

3. Pay Balance/Check Dues Balance: With this option, the user can check the dues balance of a customer and make a payment to reduce the balance. The program retrieves the customer's balance from the database and provides options to either check the balance or make a payment.

4. Register New Customer: This option allows the user to register a new customer by entering their details such as name, mobile number, and address. The program generates a unique customer ID and stores the information in the database.

5. Check Customer ID: This option enables the user to search for a customer by name and retrieve their details from the database. The program prompts for the customer's name and displays their ID, name, mobile number, address, and registration date.

6. Show All Registered Customers: Choosing this option retrieves all registered customers' details from the database and displays them, including their ID, name, mobile number, and address.

7. Date-wise Check Ceiling Amount: This option calculates and displays the total selling price for the current date. It includes both cash and credit amounts, providing a summary of the day's sales.

The program ensures data integrity by utilizing a MySQL database to store and retrieve customer information, purchase details, due balances, and payments. It utilizes SQL queries to interact with the database and performs various database operations, such as inserting new records, updating existing records, and fetching data for display.

Overall, this program provides a user-friendly interface for managing a general shop, keeping track of customers, purchases, dues, and generating daily sales reports. It simplifies the process of maintaining customer records and financial transactions, making it easier for shop owners to organize and manage their business effectively.

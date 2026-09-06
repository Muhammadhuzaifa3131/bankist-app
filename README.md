🏦 Bankist App

A simple banking application built with HTML, CSS, and JavaScript.

This project focuses on working with arrays, objects, higher-order array methods, DOM manipulation, and JavaScript event handling.

📌 About the Project

Bankist is a mini banking application where users can log in to their account and perform different banking operations.

The application uses JavaScript to manage account data, transactions, balances, transfers, loans, and account deletion.

✨ Features
🔐 User login with username and PIN
💰 Display current account balance
📊 Display total deposits
💸 Display total withdrawals
💵 Calculate interest
🔄 Transfer money between accounts
🏦 Request a loan
❌ Close an account
🔢 Sort transactions
📱 Dynamically update the user interface
🧠 JavaScript Concepts Used
Arrays

Arrays are one of the main parts of this project.

Each account contains a movements array that stores all deposits and withdrawals.

For example:

movements: [200, 450, -400, 3000, -650, -130, 70, 1300]


Positive values represent deposits, while negative values represent withdrawals.

Higher-Order Array Methods

This project uses several important JavaScript array methods:

forEach() — used to loop through accounts and transactions.
map() — used to transform data, such as creating usernames and calculating interest.
filter() — used to separate deposits and withdrawals.
reduce() — used to calculate balances, total income, withdrawals, and interest.
find() — used to find a specific account.
findIndex() — used to find the index of an account before deleting it.
some() — used to check loan eligibility.
sort() — used to sort transactions.
slice() — used to create a copy of the movements array before sorting.
splice() — used to remove an account from the accounts array.
push() — used to add new transactions during transfers and loans.
🔄 How the Application Works
1. Login

The user enters a username and PIN.

JavaScript searches the accounts array using find() and verifies the PIN.

2. Account Dashboard

After successful login, the application displays:

Account balance
Deposits
Withdrawals
Interest
Transaction history
3. Money Transfer

The user can transfer money to another account.

The sender receives a negative movement and the receiver receives a positive movement.

4. Loan Request

The application checks the user's previous movements using some() before approving a loan.

5. Account Closing

The user can close their account after entering the correct username and PIN.

The account is removed from the accounts array using splice().

6. Transaction Sorting

Transactions can be sorted using JavaScript's sort() method.

🛠️ Technologies Used
HTML5
CSS3
JavaScript
DOM Manipulation
JavaScript Array Methods
📚 What I Learned

Through this project, I practiced how JavaScript arrays and objects can be used to build a real-world interactive application.

The main concepts I practiced were:

Working with arrays and objects
Higher-order array methods
Array chaining
DOM manipulation
Event listeners
Form handling
Conditional logic
Template literals
Optional chaining
Updating data dynamically
🚀 Future Improvements

Some possible improvements for this project:

Add real authentication
Store data using a backend/database
Add transaction dates
Improve responsive design
Add persistent login using local storage
Add more detailed transaction information
👨‍💻 Author

Muhammad Bin Atif

Built as a JavaScript learning project focused on arrays and higher-order array methods.

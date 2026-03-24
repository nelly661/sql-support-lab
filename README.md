# SQL Support Lab

This project demonstrates beginner SQL queries used in support-related troubleshooting scenarios.

## Scenario 1: Find Pending Payments

### Query
SELECT * FROM billing WHERE payment_status = 'Pending';

### Purpose
Used to identify customer accounts with pending billing status.
## Scenario 2: Search Customer by Email

### Query
SELECT * FROM customers WHERE email = 'example@email.com';

### Purpose
Used to locate customer account information during support inquiries.

## Scenario 3: View High Priority Tickets

### Query
SELECT * FROM tickets WHERE priority = 'High';

### Purpose
Used to identify urgent support cases requiring immediate attention.
## Scenario 4: Find Duplicate Customer Records

### Query
SELECT email, COUNT(*) 
FROM customers 
GROUP BY email 
HAVING COUNT(*) > 1;

### Purpose
Used to identify duplicate customer records in the database.

## Scenario 5: Check Active Accounts

### Query
SELECT * FROM customers WHERE account_status = 'Active';

### Purpose
Used to review active customer accounts during support investigations.

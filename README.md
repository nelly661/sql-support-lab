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

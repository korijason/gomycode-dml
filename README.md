# Data Manipulation Language (DML) Checkpoint

## Overview
This project demonstrates how to populate a relational database with data using SQL commands. The database includes three tables:
- `CUSTOMER`
- `PRODUCT`
- `ORDERS`

Data was inserted into the tables to establish relationships and test functionality.

## Steps to Execute
1. **Set Up the Database**:
   - Create the tables (`CUSTOMER`, `PRODUCT`, `ORDERS`) using the provided SQL schema.

2. **Insert Data**:
   - Use the `INSERT` commands to populate the tables with the specified data.

3. **Verify Results**:
   - Use `SELECT` statements to verify that the data was inserted correctly.

## Table Data
1. **CUSTOMER Table**:
   - Contains customer details such as `CustomerID`, `Name`, `Address`, and `Phone`.

2. **PRODUCT Table**:
   - Contains product details such as `ProductID`, `ProductName`, and `Price`.

3. **ORDERS Table**:
   - Contains order details such as `OrderID`, `OrderDate`, `CustomerID`, `ProductID`, and `Quantity`.

## Example Data:
### CUSTOMER Table:
| CustomerID | Name        | Address          | Phone     |
|------------|-------------|------------------|-----------|
| 1          | John Smith  | 123 Elm Street   | 555-1234  |
| 2          | Jane Doe    | 456 Maple Avenue | 555-5678  |

### PRODUCT Table:
| ProductID | ProductName | Price    |
|-----------|-------------|----------|
| 1         | Laptop      | 999.99   |
| 2         | Smartphone  | 599.99   |

### ORDERS Table:
| OrderID | OrderDate  | CustomerID | ProductID | Quantity |
|---------|------------|------------|-----------|----------|
| 1       | 2024-01-15 | 1          | 1         | 2        |
| 2       | 2024-01-16 | 2          | 2         | 1        |

## Tools
- MySQL Workbench for executing SQL scripts.
- SQL commands for creating, inserting, and querying data.

## Author
Created by [Your Name]. Feedback is welcome!

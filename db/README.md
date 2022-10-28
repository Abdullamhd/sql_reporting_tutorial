#  Configuring PostgreSQL with pgAdmin 4 in Docker & understanding the data


### Clone the repository
```bash

git clone https://github.com/Abdullamhd/postgres_setup.git

```

### Change directory to the repository
```bash
cd sql_reporting_tutorial
cd db
```


### Run the docker-compose file
```bash
docker-compose up -d
```


### Open the browser and go to the following link (Optional)

```bash
http://localhost:5050
```

### Login with the following credentials
```bash
email:localhost@localhost.com
password:123456
```

### Create a new server
```bash
name:postgres
host:db
port:5432
username:postgres
password:postgres
```


### Connection info for Azure Data Studio

```bash

server:localhost
port:5432
username:postgres
password:postgres
database:northwind

```









---
## get to know the data


### Select all employees from the employees table
```sql
SELECT * FROM employees;
```

### select all customers from the customers table
```sql
SELECT * FROM customers;
```

### select all products and categories from the products and categories tables
```sql
SELECT * FROM products;
SELECT * FROM categories;
```

### Select all suppliers from the suppliers table
```sql
SELECT * FROM suppliers;
```

### Select all from the orders table
```sql
SELECT * FROM orders;
```

### Select all from the order_details table
```sql
SELECT * FROM order_details;
```

### Select all from the employees territories table
```sql
SELECT * FROM employees_territories;
```

### Select all from the customer_demographics table
```sql
SELECT * FROM customer_demographics;
```

### Select all from the region table
```sql
SELECT * FROM region;
```
### Select all from shippers table
```sql
SELECT * FROM shippers;
```

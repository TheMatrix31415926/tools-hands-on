##### PostgreSQL Data Storage Workflow

###### **Data Scenario**

###### 

###### **Scenario:** Customer Details Management System

###### Used by a small business to store and manage customer information in an organized way.

###### 

###### **Data Fields (Table: customers)**

* ###### Customer\_ID (Primary Key)

###### Unique identifier for each customer (ensures no duplicates)

* ###### Full\_Name

###### Stores the customer’s name for identification

* ###### Email

###### Used for communication and login/contact purposes

* ###### Phone\_Number

###### Alternative contact method

* ###### City

###### Helps in location-based filtering and analysis

###### 

###### **Adding Data (Insert Process)**

* ###### Who adds it:

###### Admin staff or sales representative

* ###### When it is added:

###### When a new customer signs up or makes first contact

* ###### How it is added:

###### Data is entered via a form (or manually in DB tool like DBeaver)

###### 

###### **SQL Example:**

###### 

###### INSERT INTO customers (customer\_id, full\_name, email, phone\_number, city)

###### VALUES (101, 'Rahul Sharma', 'rahul@email.com', '9876543210', 'Delhi');



* ###### Purpose:

###### Ensures all new customer data is stored in a structured format





###### **Viewing Data (Read/Search Process)**

* ###### Who uses it:

###### Sales team or support team



* ###### How data is viewed:

###### 

###### View all customers:

###### SELECT \* FROM customers;

###### Search by city:

###### SELECT \* FROM customers WHERE city = 'Delhi';

###### Search by email:

###### SELECT \* FROM customers WHERE email = 'rahul@email.com';



###### Purpose:

###### Quickly retrieve relevant customer information when needed





###### **Updating Data (Update Process)**

* ###### When it is updated:

###### When customer details change (e.g., phone number, city)

###### 

* ###### How it is updated:

###### UPDATE customers

###### SET phone\_number = '9999999999'

###### WHERE customer\_id = 101;



* ###### Who updates it:

###### Admin or authorized staff

###### Purpose:

###### Keeps customer records current and accurate



###### **Data Accuracy Rule**

###### Rule:

###### Email must be unique for every customer (no duplicates allowed)

###### 

###### **How enforced:**

###### ALTER TABLE customers

###### ADD CONSTRAINT unique\_email UNIQUE (email);



###### **Benefit:**

###### Prevents duplicate entries and maintains clean data





##### **Outcome**

###### Organized and structured customer database

###### Easy data entry, retrieval, and updates

###### Reduced errors and duplication

###### Better data management for business operations


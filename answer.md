# Database Relationships

## Definition of Database Relationship
A database relationship defines how two or more tables are connected in a relational database using primary keys and foreign keys. Relationships help maintain data integrity and reduce redundancy.

---

## Types of Database Relationships

### 1. One-to-One Relationship (1:1)
One record in a table is linked to one record in another table.

**E-commerce Example:**  
User and User Profile  
Each user has one profile, and each profile belongs to one user.


---

### 2. One-to-Many Relationship (1:M)
One record in a table can be related to many records in another table.

**E-commerce Example:**  
Customer and Orders  
One customer can place many orders, but each order belongs to one customer.


---

### 3. Many-to-Many Relationship (M:N)
Many records in one table relate to many records in another table.  
A junction table is required.

**E-commerce Example:**  
Orders and Products  
An order can contain many products, and a product can appear in many orders.


---

## Conclusion
Database relationships are essential for designing structured and scalable e-commerce systems. Choosing the correct relationship type ensures efficient data storage and retrieval.

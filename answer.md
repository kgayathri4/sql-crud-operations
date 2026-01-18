Database Relationships
What is a Database Relationship?

A database relationship shows how data in one table is connected to data in another table.
These connections are made using keys.

Primary Key (PK) → uniquely identifies a record

Foreign Key (FK) → connects one table to another

Relationships help keep data organized, accurate, and non-duplicate.

Types of Database Relationships

There are three main types:

One-to-One

One-to-Many

Many-to-Many

1. One-to-One Relationship
Meaning

One record in one table is linked to one record in another table.

E-commerce Example

User and User Profile

One user has one profile

One profile belongs to one user

Diagram
User  <---->  User_Profile

2. One-to-Many Relationship
Meaning

One record in one table is linked to many records in another table.

E-commerce Example

Customer and Orders

One customer can place many orders

Each order belongs to one customer

Diagram
Customer  ---->  Orders

3. Many-to-Many Relationship
Meaning

Many records in one table are linked to many records in another table.

This relationship uses a junction (middle) table.

E-commerce Example

Orders and Products

One order can have many products

One product can be in many orders

Diagram
Orders  ---->  Order_Items  <----  Products

Summary Table
Relationship Type	Meaning	E-commerce Example
One-to-One	One ↔ One	User ↔ Profile
One-to-Many	One ↔ Many	Customer ↔ Orders
Many-to-Many	Many ↔ Many	Orders ↔ Products
Conclusion

Database relationships define how tables are connected.
In e-commerce applications, they help manage users, orders, and products efficiently.
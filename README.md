# Book_Database_Management

This project creates the Relational database for Book Store Management, Where we handled all the  CRUD operations using SQL. Created the complete Backend project using Nodejs and SQL. Procedures are created for insertion and update. Api is created for each operation.


Create the database connection in the index.js.

change the username and password below line of index.js.



var mysqlConnection= mysql.createConnection({
    host:'localhost',
    user:'root',
    password:'Anusha12345@',

    database:'book_management_store'
})


Create the tables and procedure. using above files.
Create 3 procedure, use procedure.txt for all 3 procedures.
We can test the api using postman.

Operation can be performed are- CRUD
And also the data will be updated on issue and return. like the copies left and limit of user etc.

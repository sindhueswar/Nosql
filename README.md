CAR DEALERSHIP


This project uses HBase, a distributed, non-relational database management system, for storing and accessing data. The project creates three tables - customer, car, and staff - and inserts  data into them. It then read data from the tables.


Tables


Customer:


The customer table has the following columns:

              Row Key
              Name
              Membership Type


Car

The car table has the following columns:

              Row Key
              Brand
              Customer ID
              Model
              Engine
              Year




Staff

The staff table has the following columns:

             Row Key
             Name
             Customer ID
             Position
             Salary

In this project, HBase is used as a distributed NoSQL database to store and retrieve large amounts of data. Some of the common HBase commands used in this project are:

create - used to create a new table in HBase. This application creates three tables:

           customer
           car 
           staff.
           
           
           
![1](https://user-images.githubusercontent.com/109608217/227257127-15e02d60-b1bb-4aae-a3d8-2fd860ea888e.png)


put - used to insert data into a specific row and column of a table .All the values for the attributes of the tables are given using this command.This command also used to update the values for the attributes in the table.
            
            
            

 

scan - used to retrieve data from multiple rows and columns of a table.Using this command the three tables are displayed.


 ![2](https://user-images.githubusercontent.com/109608217/227257146-0fc80820-1255-40e3-8878-2d87c57f73e6.png)
 
 

delete - used to delete a specific row or column from a table .The st3 row of the staff table is deleted by this command

These commands can be executed through the HBase shell or through client APIs in programming languages such as Java or Python.
              

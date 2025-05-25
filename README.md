# FINAL-EXAM
Names: MURUNGI Deborah

Student_id: 26020

 MY PROJECT NAME
Online Bookstore Inventory Management System
Problem Statement
Traditional bookstore operations often rely on manual inventory tracking, leading to data inconsistencies, stock mismanagement, 
and delays in order processing. These inefficiencies result in poor customer satisfaction, increased operational costs,
and the risk of stockouts or overstocking.  

# PHASE 1 

[Online-Bookstore-Inventory-Management-System by DEBORAH MURUNGI.pptx](https://github.com/user-attachments/files/20430333/Online-Bookstore-Inventory-Management-System.by.DEBORAH.MURUNGI.pptx)

# PHASE 2: BPMN(Business Process Modeling Notation)

![bpmn](https://github.com/user-attachments/assets/2140e3a3-daf9-40d5-8f4b-0bfc19b9e400)
 

# PHASE 3: Logical and Model Design

![ERDIAGRAM](https://github.com/user-attachments/assets/16ecc31a-10be-4245-9500-dd4053ea6676)
 

Relationships & Constraints:
Modify customer 

![customer modi](https://github.com/user-attachments/assets/a9177f61-25d3-4199-b258-0cfda544e59b)

Modify book

![book modi](https://github.com/user-attachments/assets/5fde8d2b-2944-4ee9-a626-f534499cff80) 

Modify Order

![orders modi](https://github.com/user-attachments/assets/58c58dd8-62d4-49be-9442-80c5f1b170dc)

 Modify OrderDetail 
 
![ordersdtlsmodi](https://github.com/user-attachments/assets/c042cda8-1108-4487-b71f-128d1b230112)

Modify Payment

![paymentmodi](https://github.com/user-attachments/assets/9a40180a-29bf-491b-9581-2a615d2848b7)

Modify Stock

![stock modi](https://github.com/user-attachments/assets/63fa04d7-aa61-406a-ab3a-898c376dbcff)

Modify Admin

![admin modi](https://github.com/user-attachments/assets/ebb2234b-3bcb-4b41-991e-1d24889da012)






# PHASE 4: Database Creation 

A Pluggable Database (PDB) that allows multiple databases to be stored and managed within a single Container Database (CDB).
 
![PDBS](https://github.com/user-attachments/assets/5a4c7062-5df6-413c-88f8-7cf82b96f59a)

 User of PDB allows us to create tables. 
 
![USER](https://github.com/user-attachments/assets/214949fb-6b1b-4dc4-99fc-8b689603647d)

This is when the user is given access to make modification in PDB

![USER GRANTED](https://github.com/user-attachments/assets/6ab76039-19b0-4ef5-98ba-562ecbd4c007)

Oracle Enterprise Manager (OEM): OEMs play a crucial role in many industries, including automotive, electronics, and computer hardware. 

![eom](https://github.com/user-attachments/assets/58bb8861-6a72-41d5-b848-b75d014d0751)

TABLE SPACE

![tablespace](https://github.com/user-attachments/assets/86c6c17d-0c1d-40e9-902e-6cc8780fb6bd)


# PHASE 5: Table Implementation and Data Insertion

TABLE CREATION
customer table

![customer](https://github.com/user-attachments/assets/2bb8516d-d683-46ce-b514-d3d8a318cc81)

Book table

![book](https://github.com/user-attachments/assets/8f97e97f-1e89-4656-895f-68673110e298)

OREDERS TABLE

![order](https://github.com/user-attachments/assets/11a90db7-1a9c-411a-8d54-3db91c7ab816)

ORDERDETAILS TABLE

![orederdetail](https://github.com/user-attachments/assets/f625aaad-015d-4470-bca9-c7f67676d084)

PAYMENT TABLE

![payment](https://github.com/user-attachments/assets/1c48467b-bcb2-42e5-bc79-567440ea38bf)

STOCK TABLE

![STOCK](https://github.com/user-attachments/assets/898ae0dd-1c55-4841-b0f7-bc642b653426)

ADMINISTRATOR TABLE

![Admn](https://github.com/user-attachments/assets/0e004162-d706-4259-a81e-7ac4ac2205a7)
 
 Data Insertion in Customer
 
![insert in cust](https://github.com/user-attachments/assets/a48e276b-37e7-4cb9-9be1-cc0260072527)

 Data Insertion in book
 
![row affected on book](https://github.com/user-attachments/assets/1e97d559-3bda-406a-b5f5-4e898c36b4f0)

 Data Insertion in orders
 
![row insrted on orders](https://github.com/user-attachments/assets/97dccb95-aa9a-4b4e-8740-d6c26f090a81)

 Data Insertion in OrderDetails
 
![row inserted on orderdtls](https://github.com/user-attachments/assets/0437d850-1e09-443c-a63e-fd0fd6fe7ae2) 

 Data Insertion in Payment
 
![row inserted in payment](https://github.com/user-attachments/assets/94d3eaea-68a1-414f-bff4-6e6e9057a4ba)

 Data Insertion in Stock
 
![insert in stock](https://github.com/user-attachments/assets/6e7fccd5-cbd1-42bb-993e-843b70e79615)

 Data Insertion in Admin
 
![row inserted in admn](https://github.com/user-attachments/assets/8538f7cf-a817-4297-beed-6234ef0209d2)

Update STOCK

![updates](https://github.com/user-attachments/assets/2b25aaac-0851-4db6-a6c7-49f99c636e56)

DELETE

![customer delete](https://github.com/user-attachments/assets/c5296c81-4fdb-44e8-aeba-44694b751958)

DROP

![drop category](https://github.com/user-attachments/assets/646d3db4-58ca-4233-be61-5b2c778238d0)


# PHASE 6:Database Interaction and Transactions


WINDOW FUNCTION  

A window function performs a calculation across a set of table rows that are related to the current row, without collapsing the result into a single row.

![Show how many of each book each customer has purchased in total](https://github.com/user-attachments/assets/ea631e6b-a790-4ad2-8b8e-90ec472017ba)
![Find the Top 3 Books per Customer](https://github.com/user-attachments/assets/d92c6c57-9491-41d2-82e6-83810d2296a3)
![Assign a row number to each book purchase, ranked by Subtotal (highest first)](https://github.com/user-attachments/assets/48beaa9b-3173-4528-a7e4-660a779975af)

PROCEDURE  

A procedure is a named block of code that performs a specific task, but does not return a value directly 

![test procedure](https://github.com/user-attachments/assets/2f7c1cc8-f431-4812-80a7-59c4bce06f34)
![procedures](https://github.com/user-attachments/assets/d7c79164-4c00-4e3b-a9c5-38d7ea8b2639)

FUNCTIONS

A  Function is a named block of code that performs a specific task and returns a single value.
 
![FUNCTION](https://github.com/user-attachments/assets/18555c7c-2678-466c-a075-ba5a572b07c2)

CURSOR

A cursor is a pointer to a result set of a query. It allows you to process query results row-by-row in PL/SQL.
 
![CURSOR](https://github.com/user-attachments/assets/29dbf53d-6dde-4637-80e8-aeba4358f0df)

PACKAGE

A package in PL/SQL is a grouping of related procedures, functions, variables, cursors, and other PL/SQL elements stored together in the database.

![packege](https://github.com/user-attachments/assets/049b5c81-d813-47db-ac72-be7d2386baad)

Problem Statement
Traditional bookstore operations often rely on manual inventory tracking, leading to data inconsistencies, stock mismanagement, 
and delays in order processing. These inefficiencies result in poor customer satisfaction, increased operational costs,
and the risk of stockouts or overstocking.  



# PHASE 7: Advanced Database Programming and Auditing

UPDATE AND DELETE IN TRIGGER

![deletebefore trigger](https://github.com/user-attachments/assets/8604d709-7b91-4965-8c9b-d21ec588c936) 
![update and delete from triger output](https://github.com/user-attachments/assets/90f93f92-f3bd-4d46-b5b1-0a7e160c0018)

COMPOUND TRIGGER AND SIMPLE TRIGGER

![simple trigger](https://github.com/user-attachments/assets/37dd3e28-a5d3-4f9f-8d23-39e7123187b2)
![compondtriggers](https://github.com/user-attachments/assets/55e2570c-dac6-483b-90cb-e98b27ccc000)

REFERENCE TABLE

![refer and inserted](https://github.com/user-attachments/assets/74e88170-ec30-4ab5-a8d6-039d8052eb6c)

AUDITING TABLE

![inventory](https://github.com/user-attachments/assets/5c4df38a-fa46-4bbb-9778-c20f6735c274) 
![triger1](https://github.com/user-attachments/assets/3d33a4e4-c4b6-4b23-8f09-843740e9218b)
![ristriction](https://github.com/user-attachments/assets/71d01317-dce6-44dd-a23a-dfe956085f67)


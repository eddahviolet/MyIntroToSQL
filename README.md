# MyIntroToDatabases
SQL seemed complex to me though I had previously never taken the time to know anything about it other than how bland the screen looked when someone was working with it. This was my first interaction with a DBMS with an open mind. Creating my first database and table, this is when I realized, I will fall love SQL

This repo is my first exercises working with MySQL. Enjoy

## Mission 1:Working with numerical values in a database. 
#### Task 1

Mr. Carl Merkel owns a small business named CM Mobiles that sells mobile devices. He wants to create a database and a devices table to store key information about mobile devices. This information includes: 

*	The device ID or number
*	The device name
*	And the price of the device

The first step is creating a database

![create database1](https://user-images.githubusercontent.com/106580846/204785625-d07b0f63-5aca-4ed0-93d2-bcaa2bc89cf9.png)

Then navigate to the created database

![use database](https://user-images.githubusercontent.com/106580846/204785717-38895d7b-5548-473a-8704-357e6cf79cec.png)

Create the devices table with the required columns

![create table 1](https://user-images.githubusercontent.com/106580846/204785859-9bd96eff-b3a2-43be-a4b2-5afb0f1f8cc1.png)
 
Display columns from the table to display the numerical data types used (int & decimal)

![columns devices](https://user-images.githubusercontent.com/106580846/204785976-31a7dfc3-a964-4fe8-9f4a-9103a5f0e3a7.png)

#### Task 2

Mr. Merkel wants to create another basic table in the database to store data about the stock of the devices including device ID, quantity available in the stock and total available cost of the quantity. 

*	Identify an appropriate table name to create, given the information provided. 
Table name: Stock 
*	Identify columns that should be available in this table and define them with the appropriate data types.
    -Device id INT

    -Quantity INT 

    -Total cost: Decimal

*	Write the full SQL statement that creates the table and columns.

Create the stock table with the required columns

![11](https://user-images.githubusercontent.com/106580846/230353000-21565a96-d23e-4b81-9c25-bc538d18b7b6.png)

Display columns from the table to display the numerical data types used (int & decimal)

![12](https://user-images.githubusercontent.com/106580846/230353144-e3b3e987-bd9a-437a-ba3e-b8d33f23db55.png)

## Mission 2:Working with strings

#### Task 1

Mr. Carl Merkel wants to create a new table to store key information about customers such as 

*	username
*	full name 
*	email address

Create the customers table with the required columns

![customers table](https://user-images.githubusercontent.com/106580846/204786779-3fd0c0c2-9388-4b66-afa9-1ac785c00a0c.png)

Display the columns from the customers table to show the string datatypes used (varchar & char)

![colums from customers](https://user-images.githubusercontent.com/106580846/204786867-175384f0-ec13-436d-b196-395191ac4c36.png)

#### Task 2
Mr. Carl Merkel wants to create another basic table in the cm_devices database to store the customers' feedback. This table need to include three columns:

*	Feedback ID column
*	Feedback type column with a maximum of 100 characters
*	A comment column with a maximum of 500 characters

The data types for the columns will be:
* Feedback id: CHAR(8)
* Category: VARCHAR(100)
* Comment:  TEXT(500)  

Create the Feedback table with the required columns

![20](https://user-images.githubusercontent.com/106580846/230355181-b22fab00-bc36-4dba-bbdb-c35094dab123.png)

Display the columns from the Feedback table to show the string datatypes used 

![21](https://user-images.githubusercontent.com/106580846/230355222-249a20dd-6cfb-4652-9cd2-4e995ec35d50.png)

## Mission 3: Working with default values
#### Task 1

Mr. Carl Merkel owns a small business that sells mobile devices called “CM Mobiles” in Harrow, London. He wants to create a database to store key information about customers' addresses including customer ID, street, postcode and town name. The list of columns need for the table are:
* Customer ID	
* Street	
* Postal Code	
* Town

Most customers are living in Harrow area and come from the same postcode “HA97DE” write the SQL statement to declare both the postcode and the town name with default values.

Include a "not null" constarint in the Address cloumn

Create an SQL statement  with relevant attributes and constraints, identify the column that requires default values.  

![30](https://user-images.githubusercontent.com/106580846/230358778-f0e78172-5009-46da-aaa4-aa4af4014c81.png)

Display the columns from the Address table to show the constraints used 


![31](https://user-images.githubusercontent.com/106580846/230358819-f086190b-9455-4cef-8317-3c1ba305bac9.png)






# SRS document for super market management

## 1. Functional Requirements:
1. User login : A registered user can login to the system by providing his username and password.
	 After successful login, the home page is shown from where the user can access the different 
	 functionalities of the system like adding, deleting, viewing, updating product details, add 
	 customer details. If the user enters wrong username or password or if the user is not authorised,
	 then he cannot access the home page and a login failure message will be shown to the user and the
	 user has to enter the correct username and password to successfully login.
	   
2. Add product : A valid user of the system can add a new product by entering various details of the
	 product like product name, brand, price per unit, quantity.
	   
3. View products : A valid user of the system can view the existing products and their details like
	 product name, brand, price per unit, quantity.
	  
4. Update product details : A valid user of the system can update the details of existing products
	 like updating product quantity of existing product.
	
5. Remove a product : A valid user of the system can remove an existing product in cases like product
	 expiry.
	   
6. Sell products : A valid user of the system can sell one or more products and once the products are 
	 sold, the database will be updated.
	   
7. Add new customer : A valid user of the system can add a new customer by providing details like customer
	 name, mobile number, address.
	   
8. View customer details : A valid user of the system can view the details of existing customers.
	
## 2. Non-Functional Requirements:
1. Minimum system requirements:
	 1. RAM - 1GB
	 2. Processor - Pentium Dual Core 1.8 Ghz or better
   3. Operating System - Linux / Windows 7 or later
   
2. Performance requirements: 
	 1. The system should remain accessible 24x7.
  
3. Design constraints:
	 1. The system should be developed as an offline application using Python programming language.
	 2. The application should use MySQL database.


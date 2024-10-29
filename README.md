java c
CS-GY 6083B, Fall 2024 
Principles of Database Systems 
Assignment: 1 [100 points - 5% weight towards final grades] 
Problem 1: 50 points 
Business Case:
CORD (Customer Order Return Department) of Amazon is engaged in storing and analyzing returned order related data. With an increased volume of the order returns, CORD is undergoing constraints about analyzing data to find products that   have high return rates and their vendors who supply the product. To overcome these constraints and enhance their business performance, CORD has decided to design and develop relational database system. Following are the initial requirements and business rules for the data model. 
Entity Name 
Attributes 
Remarks 
CUSTOMER 
CUST_ID, FNAME, LNAME, ADDRESS, EMAIL, PHONE 
Customer can have many addresses 
such as home address, business address, vacation home etc., and there may be 
many customers at the same address. 
CORD will store the type of the address in their dataset. CORD will store only one email address and phone number of their customers. 
ORDER 
ORDER_ID, ORDER_DATE, DELIVERY_DATE, 
RETURN_SATUS, RETURN_DATE, RETURN_REASON 
Customer can return entire order or 
any specific items of the order. If order is returned, CORD will store return 
status as ‘R’ with return date and return reason for each of the item returned. 
SUPPLIER 
SUPP_ID, COMPANY NAME, ADDRESS, EMAIL, PHONE 
A supplier can supply many items, and also same item may be supplied by many suppliers. 
ITEM 
ITEM_ID, ITEM_NAME, UNIT_PRICE, ITEM_COLOR 
Each item will have fixed unit price. However, price charged to customers may be different based upon any promotion, i.e., the sale price of the item may vary with orders. 
CORD want to store number of items (quantity) sold for each item in the order. At presents CORD operates within United States only. 
Resolve composite, derived, and multi-valued attributes, if any. Please use Oracle Data Modeler for creating E-R diagrams. DrawERD (both Logical and Relational model) of this schema with appropriate primary keys, foreign keys, and relationships among them. If you have made valid assumptions other than those stated in the business case, please state them clearly in support of your ERD models. 
WAIT: Please verify your solutions against DB DESIGN CHECK LIST (as posted under Module 2) before submitting your assignment. 
Submit: 1) 代 写CS-GY 6083B, Fall 2024 Principles of Database Systems Assignment: 1Prolog
代做程序编程语言Logical Model 2) Relational Model 3) Any valid assumptions made 4) DDL code 
Problem 2: 50 points 
Business Case: 
Uber has undertaken a project, Uber Elevate that provides Air Taxi services using eVTOL (Electric Vertical Take Off and 
Landing). eVTOL operates on high energy battery and can carry four to six passengers and the pilot. The average range of eVTOL is estimated at 50 miles. The cost of eVTOL ride is estimated between $4 to $5 per passenger mile. 

EVTOL                                                                                              TAKE OFF / LANDING STATION 
You have been hired as a database design intern for the Uber Elevate project. The business team has provided following details about entities and their characteristics to develop a database model. 
Entity Name 
Attributes 
Remarks 
EVTOL 
EVTOL_ID, MANUFACTURER, SEAT_CAPACITY, WEIGHT, MILE_RANGE, ENERGY_TYPE, 
MANUFACTURE_DATE 
Energy Type can be Electric Battery or Electric Hybrid, Electric Hydrogen 
PILOT 
pID, pGENDER, pAGE, pNAME, pADDRESS, pLICENSE_NO, pLICENSE_DATE 
Only one address of the pilot will be stored. 
TRAVELER 
tID, tGENDER, tAGE, tNAME, tTYPE 
Traveler type can be Individual or Corporate 
STATION 
sID, sADDRESS, STATAION_TYPE 
Station type can be Airport/ Hospital/ Urban/ Rural 
For each trip, Uber want to store trip date, take off station, landing station, passengers in the trip, travel miles, cost per passenger par mile.  Pilots may operate multiple eVTOL aircrafts, and between multiple take off/ landing stations. 
Hint: There is four ways M: N relationships. 
Please identify entities, their appropriate attributes, characteristics of attributes, relationships amongst entities, and resolve many to many relationships, if any. Resolve any composite, derived, and multi-valued attributes, if any. Please use Oracle Data Modeler for creating E-R diagrams. Draw ERD (both Logical and Relational model) of this project. If you have made valid assumptions other than those stated in the business case, please state them clearly in support of your ERD models. 
WAIT: Please verify your solutions against DB DESIGN CHECK LIST (as posted under Module 2) before submitting your assignment. 
Submit: 1) Logical Model 2) Relational Model 3) Any valid assumptions made (other than stated business rules), 4 DDL code 

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

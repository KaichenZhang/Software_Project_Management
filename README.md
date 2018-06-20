# Software_Project_Management
First of all, I would like to express my highest respect to Dr.Olga Ormandjieva for her generous help to us.<br />
And I want to give my highest gratefulness to all of my teammates who made this project perfect.<br />
Both of our documentation and presentation ranked #1 among 10 competitive teams!<br />

SOEN 6841 <br />
Contributed by Kaichen Zhang, Yang Zhou, Jinsong Liu,  Zhu Liu, Yu Luo, Ruijia, Yang Kundi Yao, Mo Chen<br />


Course Topics:
=============
Part I:   Software Measurement  
-------------
Subtopics:
1. The measurement process
2. Software Management measures
3. Software measurement techniques (Goal-Question-Metric GQM)
4. Measures for the requirements phase (Functional Size Measurement FSM)

Part II:  Software Project Management 
-------------
Subtopics:
1. Measurement planning  
2. Initiation and Scope Definition: 
3. Software Project Planning  
4. Risk Management  

Part III: Agile Estimating and Planning. 
-------------
Subtopics:
1. Agile Estimating 
2. Agile Planning





Project Title:
===========
Online Shopping System

Project description:
======
Functional User Requirement: 
--------
Buy a product via web. 

Pre-conditions: 
--------
The customer has a valid credit card 

Flow of events: 
--------
- The customer accesses the online store via a browser 
- The customer can search for a product by choosing the corresponding group that appears in the menu (Brands, What’s new, Clothing, .... Sale) or by typing a keyword. 
- The system displays the products of the selected group or the products that match the search criteria. In this example, the customer selected the products on Sale. 
- Next, the customer selects the product that she wants to purchase. 
- The system displays the details of the product. 
- When the customer enters the quantity of the desired product, she can adds it to the shopping cart (add to bag). 
- If the product is added to the bag, the system displays the content of the shopping cart. There are three possible choices here: 
o The customer can remove the item, or change the current quantity. In both cases, the customer has to update the cart. 
o The customer can continue shopping and add more products into the shopping cart. 
o The customer can checkout and pay for the product. 
- When the customer decides to checkout, the system will ask for an authentication (in the case of returning customers) or for the creation of a new account (in the case of new customers). 
- Returning customers must enter their e-mail address and password. 
- New customers need to enter personal information including a user and password. 
- For shipping purposes, the customer has to confirm or update the shipping address; and to select the shipping method. 
- To change the shipping address, the customer has to fill out a form (New shipping address). 
- When the shipping address has been selected or changed, the system prompts the customer to select the payment method. 
- The customer must enter the credit card information. If an error occurs during the verification of the credit card, a message is displayed. Otherwise, the system asks the customer to 'pay now'. 
- Next, the customer has to review and confirm the order. 

Purpose and Scope of measurement: 
--------
Measure the size of the functionality “Buy a product via web” as it is currently described in the set of requirements documented in the previous pages for teaching purposes. 

Functional user: 
--------
The customer, the Banking system 

Functional processes: 
--------
FP1) Select product group, FP2) Search product, FP3) Display product, FP4) view size charts, FP5) Select for purchase, FP6) Update order item, FP7) Delete order item, FP8) Place an order, FP9) Create new customer, 10) New shipping address, 11) Make the payment. 
Browse and select products:       FP1 to FP7 
Delivery (shipping) information:    FP8 to FP10 
Payment and order confirmation:    FP11

Data groups: 
--------
Customer:   Customer ID, Gender, First Name, Last Name, Date of Birth, E-mail address, Password. 
Customer shipping address:   Customer_shipping_address_ID, Customer ID, Gender, First Name, Last Name, E-mail address, Telephone number, Fax number, Street_address, Zip_code, City, State-Province, Country, Address_type, date creation address.

Product Group:   
--------
Product Group ID, Product group description, Size chart group (footwear, clothes, accessories, etc). 

Product:    
--------
Product ID, Product Group ID, Name, General description, set of characteristics (size, color, additional details), Provider, Stock Quantity, Unit cost, Unit price, Image. 

Order:    
--------
Order ID, Customer ID, Creation date, Order status (selected, paid, cancelled, delivered), total order value, customer_shipping_address ID, shipping method ID, shipping charges, payment method, payment date, authorization payment ID, comments. 

Order item:   
--------
Order Item ID, Order ID, product ID, order quantity, item status (selected, ordered, paid, cancelled, delivered). 

Shipping method:    
--------
Shipping method ID, Shipping method description (standard, FedEx, UPS, etc), shipping charges.
Data model:As shown in the graph.

Data movements:   
--------
E: Entry X: eXit R: Read W: Write

Limitations: 
--------
This project does not consider 'timeout' situations, which are commonly used in this type of applications.

**The right to the description of project belongs to Dr.Olga Ormandjieva**

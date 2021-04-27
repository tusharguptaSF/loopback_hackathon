# RestEasy Application Development Assignment

## Expectations & scope:- 

The problem statement below describes the functionality of an application that has to be created as
an outcome of this exercise. The application will have the following properties

1) Choice of programming language is left to the candidate
2) The application should be fully functioning and must include all functionality aspects described in the problem statement.
3) the candidate is welcome to add any additional functionality based on his/her wishes.
4) Data storage can be handled by using transactional database.
4) Unit tests must be added to the application,including but not limited to a sanity check.
5) The application must be accessible via a command line interface,or via API tools such as Postman.
6) If an API approach is taken to the problem, an API reference will be required.

## Problem Statement:

RestEasy is an online food ordering web application. Below are the set of requirements to be fulfilled.

1. As a customer, I should be able to Login to the application
2. As a customer, I can view either the list of Food vendors or search by dish
3. As a customer, I should be viewing a list of all the vendors (Food vendors)
4. As a customer, I should be able to view the dishes.
5. As a customer, I should be able to sort the dishes by price (both ascending and descending)
6. As a customer, I should be able to add the quantity
7. As a customer, I can order many dishes along with quantity
8. Each order will contain the below fields
9. Each Order will container 1-N OrderLineItems.
10. Each Order Item can be from different vendor
11. Each Dish should contain Name, calories fields
12. A Dish can be sold by different vendor with different price. Only the name and calories will be same across the vendors.
13. The admin should be able to view all the orders and sort based on order amount and order date.


## Appendix: Sample Order
Order Id: 4
Customer Name: Vinay Kumar
Order Date: 22-04-2020
Order Amount: Rs 850
Dish Vendor Qty Unit Price Total Price
1. Gobi Manchuri Adigas 2 50 100 2. Fried Rice RotiGhar 2 200 400 3. Dahi Bhalla Punjabi Rasaoi 1 150
150 4. Dahi Bhalla Adigas 1 200 200
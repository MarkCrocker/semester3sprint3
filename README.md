# semester3sprint3

This app was made under react, and follows a MERN stack layout.  

There is a user login system that logs all users to a database that you can retrieve.  It also has authentication for logging in and registering.
You can add to cart and actually update your orders in the cart by clicking the plus or minus.  You can have a maximum of 10 of 1 item, which will then 
prompt you that you have reached the limit.  You can decrease as well, and when you get to 0, it will remove the item from the cart.This will update your subtotal in real time
as well. 

You can also test out the stripe
function for payment by using test credit card:  4242 4242 4242 4242  exp 12/23 code 123.  

This will create a payment in the database that you can retrieve and will log the order to the user that is logged in.  You can then view your past orders by clicking
on your username and selecting orders. 

***NOTE:  THE ORDERS SECTION OF THE USER SYSTEM CURRENTLY RUNS AN INFINITE AMOUNT OF POST REQUESTS AND I DON'T KNOW HOW TO STOP IT ****

There is also a hidden admin panel, built from scratch that you can only access by going into the users database, and changing isAdmin: false, to isAdmin: true.  Once
this is done, you can then go to localhost:3000/admin to access the admin panel.  From there, you can see all registered users,  all inventory listings, edit or delete
those listings, add new listings, and view current orders.  In the orders section, there will be a button that you can click that will set the deliver status to delivered.

I think that covers just about everything.

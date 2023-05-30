# E-Commerce Web Application

> A basic online marketplace. 
> A web app on which vendors can register themselves and add items they want to sell.
> Users can add money  and order these items.


## Features

##### Basic Features:
- Registeration: Users need to register first. There are different registerations for vendors and customers.
- Authentication: Vendors and customers need to re-login by verifying. This was done using Django's in-built authentication system.

##### Vendor-side Features:

The web-app has a page for each vendor where his items are listed, sort of like a 'vendor profile'.
Vendors can:
- Add **multiple items** 
- Items can have **many units** (specified by the vendor)
- Each item can have a *image, a title, a price and a description*.
- Vendors can **add or delete items** to sell
- *View all orders* that were placed for items that they're selling 
- **get an email** whenever someone buys from him
- *generate a CSV/Excel report* of all his sales till now
- *show discounts* on items

##### Customer-side Features:

The web-app has a page for each customer where all the items are listed kinda like a 'home-page'
Customers can:
- order from **multiple vendors** at a time 
- order **multiple items**
- order upto *10 units* of the same item
- *add money* (virtual) to their account  
- View all **previous orders** 
- order *only if he has sufficient funds* for the items he's buying
- *edit shipping address*
- **add items to their wishlists**
- view all *details of a previous order* on clicking it in the previous orders section
- directly **move an item from the wishlist to the cart**

## Tech

I used a number of tech-stacks to make this project successful

- [Django](https://www.djangoproject.com/) - The framework used to create this project 
- [Django Allauth](https://www.section.io/engineering-education/django-google-oauth/) - for  authentication 
- [Mailjet](https://www.mailjet.com/) - to send mails to vendors
- [Postgresql](https://www.postgresql.org/) - to create a database for the web application

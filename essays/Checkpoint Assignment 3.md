---
layout: essay
type: essay
title: Assignment 3 Checkpoint
date: 2020-05-09
labels:
  - My Progress
  - Checkpoint
  - Blog Entry
  - Assignment 3
---
Checkpoint A:

Describe your design for your site's shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.



   The shopping cart is a separate page that the user can view and edit.  On each product page, the user has the ability to “add to cart” for each tour.  Those tour quantities will be saved in a session as the user continues to navigate throughout the pages and add more tours.  The user can access the cart at any time and edit the tour amounts.  Once pressing the purchase button on the shopping cart page, if the user is not already logged in, he/she will be redirected to a login page, and after logging in (or registering), they will be taken to the invoice page.  This will thank them personally for their purchase and show the invoice from their purchase (also giving a notification that an email copy has been sent to them at their email address).

 

Checkpoint B:

Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their keys) you will use to manage the shopping cart data and how they will be used in $_SESSION. 



   When the customer clicks “Add to Cart” I will save that data to a session as a JSON object.

 

Checkpoint C:

How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?



   I will do a verification on the server to check cookies to verify that the user has an account, or if not, I will direct them to the registration page.  The particular security concern is that a non-member would get to the purchase page, so I will set an if-statement on the server-side to redirect to the login page if there is no user information about the person trying to access the page.



Checkpoint D:

Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary):



  I will welcome the user by their name (or username if a name is not given).  When they are sent to the invoice page, I will specifically list their email address so they know that the invoice was sent to the correct place.



Checkpoint E:

If you are working with partners, how will you split up the work in your team so that you are working in parallel as effectively as possible? That is, who is doing what and when?



  I am working solo.



Checkpoint F:

How are you approaching Assignment 3 differently than Assignment 2?



  I am doing a similar approach as in Assignment 2 where I write down the immediate next steps I need to take.  For example, if I need to stop a user from accessing the invoice page, I would write down to “verify the user by requesting and verifying cookie when they press ‘purchase’”.  This helps keep me focused on the immediate task when there seems like a million and one things could be worked on.
  
  
  

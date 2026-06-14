# Project3_Product-Management-Journey-8
Product Mangement CRUD App

The database is an important part of any application. Without it, an application is just like a human without a brain.
One of the most basic scenarios in real life would be a simple CRUD app that would interact with the database and help us to store and manipulate data..
But, what is a CRUD app?

CRUD is an acronym for the four basic types of operations: Create, Read, Update, Delete. A CRUD application is one that uses a GUI to get 
data in and out of a database.
And here we'll try to create a simple Product Management CRUD App that will help us interact with the database and store product details such as product id, product name, and more!

Welcome to yet another project section in our Java Programming journey. If you have completed the previous projects, then you surely know the drill.
But, this time, rather than a simple command-line appliction, we will create an amazing GUI project.

We will use all the major concepts that we have learned so far, but the focus of this project would be on understanding how to use the 
Swing GUI to communicate with the databse.

image

This will help you brush up your knowledge so far. This will help you enhance your skills and create a bit of an advanced-level project.
It's time to level up!

image

What are we going to do in this section? What is the project about?

1) Insert and store product details such as Product ID, Product Name, Product Price, and Product Quantity in the database
2) Perform various other operations such as fetching data, deleting data, updating existing data, and more
3) A simple GUI interface to perform all the above operations

*Imortant Concepts*
The project flow would be quite similar to our previous projects, but the major focus would be on implementing the project with a GUI.
*Project Flow*

image

Let's have a look at how the flow of our project would look like,
1) The very first step is to create a simple GUI that will help us interact with the appliction and perform operations over the database.
2) The GUI would have the following options to Add, Update, Search, and Delete the data.
3) Whenever the user hits any of these buttons, the data entered by the user will be stored/fetched from the database. Accordingly, we will also generate a dialog box that will contain the details fo the operation performed.

*The Approach*
Since the major focus would be on the GUI and the database, 
we will create a simple GUI and a database with the required table in MySQL so that our app can interact with it.
Once our GUI and database are ready, we'll handle the events that will be responsible to perform the assigned CRUD operations.
Based on the event invoked, the operation will be performed.

We are done with the 'add products' functionality. Now let's move ahead and implement the 'update products' functionality.

image

There are situations where we might need to update the data such as if the price of the product has changed, or there is a change in the product quantity, and more.

Understand that, the product ID is unique since it's a primary key. Therefore, we can access other details using the ID as the primary key.

But before we move ahead, let's have a look at some MySQL theory on how we can update the data using the UPDATE statement.
Updating Values

## Updating Values
We can update the data in MySQL using the UPDATE statement. It helps to modify any field value of any MySQL table. Following is the syntax of the UPDATE statement,

Image

Here, we can specify any condition using the WHERE clause. The WHERE clause will help us to update the values by targeting specific IDs in our products table.

Now that we know how the UPDATE statement works, let's have a look at the logic.

### Logic

The logic is quite simple! Just like in the 'add' functionality, the very first step will be to create a database connection by making a call to the connect() method.

Once we have created the database connection, we will get the values entered by the user in the JTextField's using the getText() method and update those values into the products table of our ProductData database using the update statement.

Based on the productID given by the user, we will use the WHERE clause and update the other values for that particular productID.

Again, the values will be dynamic in nature, hence, instead of using the Statement, we will need to use the PreparedStatement. Finally, once the operation is completed, we will display a dialog box with an appropriate message.
Done

Simple, right?

Just like the 'add' functionality, once we update the values into the database, we clear the data from the text fields using the setText() method. Also, on the successful data update, we show a message dialog box with a success message.

Now, let's move ahead and try to execute it.

Once you enter some data into the fields and hit 'Update', above is how it would look. Yay! It's working...

We have updated the price of the product with ID as '101' from 9000 to 9500. We can verify that using the 'select *' statement in our MySQL command-line.

It should produce output something like below,

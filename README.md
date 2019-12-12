# OOPFall2019-FinalProject

Shopping Cart is a program that simulates how a user can add, remove, or pay for items in their cart. Items are created by importing a .csv file of products with a unique product ID, name, price, and quantity, or through manual addition or removal by the user. The shopping cart is represented as an array list that will be filled by instances of the Product class. Users can also print a summary of their cart, or choose to "pay" for their items with cash or credit. 

The features of the program are as follows: 
-The system will read a .csv files and store the information into an array list.
-User can add or delete items from the list manually
-The system offers users to pay with either cash or credit
-The system will create a new .csv file of the user's transaction

To use the program, specify the path location of the .csv file in the main method which will call the import method in the Cart class. Users will then be prompted to alter the items in their cart until they choose to "pay" with cash or credit. If the user chooses to pay with cash, any outstanding amounts of charge or incomplete payment will show on a new .csv file as their receipt. 

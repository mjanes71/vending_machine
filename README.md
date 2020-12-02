# vending_machine

This application is a Command line program written in Java to mimic the functionality of a vending machine. This was completed as part of a paired-programming exercise as a schoool project. We were given several user stories and asked to create this product. 

Skills that were highlighted by this project include : Inheritance, Utilization of BigDecimal to handle money functions, Text-based data logging, Utilization of Map type data collection, Exception handling.

The program runs from the "Application" class- the only place where you will find a main method. All classes needed to handle the inventory of the machine are found in the "Machine" package, along with the "Vending Machine" class that instantiates all the inventory classes in that folder.

One of the user stories required some logging of inventory to be done and a secret menu to exist on the vending machine to allow a look at current inventory. The "Sales Report" class in the Reports package handles the logic associated with the logging activity of the vending machine.

The View package contains all the logic that drives the menu and the user input. This was not the focus of the project and 90% of this code was given to me.

Project Organization:

Application
-Instances of Vending Machine, Basic Ui, and Application

Vending Machine
-Instances of CashBox, Inventory, and SalesReports


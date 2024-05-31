Restaurant Management System

This Python script implements a simple Restaurant Management System using Tkinter for the graphical user interface and MySQL Connector for database interaction. The system allows users to input customer details and order information, calculate the total cost of the order, reset input fields, exit the application, and save orders to a MySQL database.

Features:

Graphical User Interface (GUI): The system provides an intuitive interface with labels and entry fields for entering customer details and order information.
Total Calculation: Users can input quantities of various food items, and the system calculates the total cost of the order based on predefined item prices.
Database Integration: Orders can be saved to a MySQL database, allowing for easy management and retrieval of order information.
Reset and Exit Options: The system offers functionality to reset all input fields to their initial state and to exit the application.
Usage:

Install Dependencies: Ensure that Python and MySQL are installed on your system. Install required Python libraries using pip install tkinter mysql-connector-python.
Database Setup: Create a MySQL database named "inventory_management" with a table named "db" to store order information. Refer to the provided SQL script for table creation.
Run the Script: Execute the Python script restaurant_management.py. The GUI will appear, allowing users to input order details and perform various actions.
Contributing:

working :
This program uses the tkinter package to create the UI for the billing software dedicated to a Restaurant and uses MYSQL database to store the entered data.

Enter the required values in the feilds and press the "Total" button to generate a total that includes the tax and charges.

Press the "Reset" button to clear the feilds and enter new values.

Press the "Exit" button to exit from the GUI.

Press the "Save" button to store and save the data in a MYSQL database.

![Screenshot 2024-05-31 153800](https://github.com/Saikarthik-T/Restaurant-managements/assets/167961720/95938dd4-8ac0-4a14-bff9-35f9914ffcae)



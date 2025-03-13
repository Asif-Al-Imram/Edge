Restaurant-Management-System

#Objective The goal of this assignment is to build a simple Restaurant Management System using Python. This system will allow:

    Managing the menu (add, remove, or update items).
    Taking customer orders.
    Calculating bills with tax and service charges.
    Handling errors gracefully using exception handling.

Instructions

    Complete the Program Functionality: Implement all features listed below.
    Use Exception Handling: Handle errors like invalid input, unavailable items, and improper menu management.

Requirements Features to Implement

    Menu Management: o Allow the manager to:  Add new menu items with prices.  Remove items from the menu.  Update the price and quantity of existing items.
    Take Orders: o Display the menu to customers. o Allow customers to select items and quantities. o Validate that items exist in the menu.
    Bill Calculation: o Calculate the total cost, including:  10% service charge.  5% tax.
    Error Handling: o Handle invalid inputs (e.g., non-numeric prices, nonexistent menu items).
    Exit System: o Allow users to exit the system gracefully. Sample Output: Restaurant System:
    Manage Menu
    Take Order
    Calculate Bill
    Exit Enter your choice: Menu Management:
    Add Item
    Remove Item
    Update Item Price
    View Menu
    Exit Management Enter your choice: 1 Enter item name: Pasta Enter item price: 12.50 Item added successfully!

Take Orders Menu:

    Burger - $5.99
    Pizza - $8.49
    Salad - $4.99 Enter item name to order: Pizza Enter quantity: 2 Order added: Pizza x 2

Bill Calculation

Order Summary: Pizza x 2 = $16.98 Tax (5%): $0.85 Service Charge (10%): $1.70 Total: $19.53

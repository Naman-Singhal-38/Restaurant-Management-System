# Cafe-Management-System
This C program implements a simple restaurant management system, including table reservations and delivery order handling.

**How the Code works**
1. Table Reservation:
  The program uses structures (struct Table) to represent information about restaurant tables. Tables are categorized into 2-seater, 4-seater, and 6-seater.
  The reserve_table function allows a user to reserve a table by providing the number of members. It checks for available tables of the specified size and reserves   one if available.
2. Table Vacation:
  The vacat_table function allows the user to vacate a table by providing the table number. It sets the table status to "vacant" and clears customer information.
3. Table Status:
  The table_status function checks and prints the status of a specific table based on its number.
4. Checking Table Availability:
  The table_status_check function checks if there is a vacant table of a specific size.
5. Checking Available Tables:
  The tables_available function counts and prints the number of available tables of a given size.
6. Delivery Order Handling:
  The program uses structures (struct DeliveryOrder) to represent delivery orders.
  The delivery_order function allows users to place delivery orders, and delivery_order_cancel cancels an order.
  delivery_order_status prints the status of a specific delivery order.
  delivery_preparing_order simulates the chef preparing the order.
  dispatch_delivery_order simulates dispatching an order to a delivery boy.
7. Delivery Boy Management:
  The program uses structures (struct DeliveryBoy) to represent delivery boys.
  delivery_boy_initialize initializes delivery boys with sample data.
  delivery_boy_unavailable marks a delivery boy as unavailable.
  verify_delivery_boy checks if the provided delivery boy credentials are valid.
  order_delivered marks a delivery order as delivered.
  delivery_boy_available counts the number of available delivery boys.
  assign_delivery_boy assigns an available delivery boy to an order.
8. User Authentication and Main Loop:
  The main function serves as the entry point for the program.
  It includes a login system for managers, delivery boys, and chefs.
  The program runs in a loop, allowing users to choose various actions until they decide to exit.

**How to Run the Code**

perform the actions accordingly
* Manager Login: Use predefined manager credentials (user_id_manager and pass_manager).
* Delivery Boy Login: Use predefined delivery boy credentials.
* Chef Login: Use predefined chef credentials (user_id_cook and pass_cook).
Choose options based on your role and perform actions like table reservations, delivery order handling, and more.

Additional Notes
* Delivery boys and orders are initialized with sample data.
* Tables are initialized as vacant.

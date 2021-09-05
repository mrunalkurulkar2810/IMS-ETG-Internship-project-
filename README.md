# IMS-ETG-Internship-project-
Inventory Management System Project

Student Name : Mrunal Kurulkar

NOTE: Working(OUTPUT) of the program is shown in the IMS_Proj_ETG.ipynb at the bottom.

Features :

1) Code is written using Anaconda Navigator and contains Dictionary, File handling operations performed on .json file, JSON

2)Product attributes used are:
  1)Product code (replacing barcode)
  2)Product ID
  3)Product Name
  4)Product Price
  5)Product Quantity
  6)Net weight

3) It is a Menu driven program :

  1)Add item in the inventory.
    1.a)Adds item in the inventory i.e. (record.json file).
    1.b)Displays the added item.
    
  2)Delete item using product code.
    2.a)Checks whether the product code is present.
    2.b)If product code is present then delete's it, else displays message "Invalid Code".
    2.c)Displays the deleted item.
    
  3)Edit item using product code
    3.a)Checks whether the product code is present.
    3.b)If product code is present then it asks new values for attributes of new item,else displays message "Invalid Code".
    3.c)Displays the edited item.
    
  4)Purchase item using product code and generates bill
    4.a)Checks whether the product code is present.
    4.b)If product code is present then it asks number of quantity and generates bill,else displays message "Invalid Code".
    4.c) If number of quantity is not available it will display a message "SORRY... Total Quantity available is" with the number of quantity available in the inventory.
    4.d)After purchasing, the value of quantity is deducted from the record.json file.
    4.e)Generated bill contains the date and time when the item was purchased.
    4.f)All the purchases made are updated in sale.json file
    
  5)Update Stock
   5.a)Checks whether the product code is present.
   5.b)If product code is present then it asks number of quantity arrived and adds it into the previous quantity,else displays message "Invalid Code".
   
  6)Display all items present in inventory
   6.a)All the changes made while performing adding,deleting,editing,purchasing and updating the item i.e. reflected in the record.json and sale.json is displayed.
   
  7)Exit from the program
   7.a) Exits the terminal after entering the exit value in the menu.
   7.b)It does not exit until the exit value from the menu is entered.

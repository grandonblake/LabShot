# LabShot
A simple C++ Automated Food Stall and Inventory System

This project was a group effort that was submitted on January 19, 2021 as a Final Project requirement during my 1st year in College.

## How to Run
Just put the whole source code in a C++ compiler. Originally, we used onlinegdb.com to compile, debug, and run the program.

## Project Objectives
The  project  focuses  on  developing  an  automated  food  stall  and  inventory  system.  This 
project lessens the time consumption and it helps to keep the record of all the daily sales of a store. 
The objective of the automated food stall is to decrease physical contact while buying sustenance, 
while the intention of having an inventory system is to lessen the caseload of a worker. This project 
can help many laborers in their works.
Specifically,
- To decrease the physical contact.
- To automate the ordering and transaction process
- To track the amount of stocks per item
- To regulate inventory automatically
- To keep records of sales.
- To reduce the cost of labor.
  

## Scope and Delimitations
The system contains the following scope:
The  system  is  written  in  C++  language  using  the  online  compiler  and  debugger  called 
OnlineGDB. The contents of this system focus solely on the software of the automated food stall 
and inventory system - meaning hardware of the said project is not included in this project. 

## Conclusion
The project focused on developing an automated food stall and storage system. This project 
lessened the time consumption and it kept the records of all the daily sales of a store. The objective 
of  the  automated  food  stall  is  to  lessen  the  physical  contact  while  buying  sustenance,  while  the 
intention of having a storage system is to lessen the caseload of a worker. The developers therefore 
conclude that all specified objectives are met based on the system.

## Recommendations
- The developers suggest using a different computer language that can execute the system 
with less memory and faster render.
- The developers suggest using third-party applications or software to improve the overall 
system.
- The developers suggest to not limit the inputs to integers, and floats only. Rather, characters 
can  also  be  inputted  but  it  will  display  that  it  can’t  recognize  character  inputs.  In  other 
words, the program will be more dynamic if inputs can be any data type.
- The developers suggest to fully implement the software online so that many people will 
have access to it.
- The developers suggest to associate the system with a functioning hardware.
- The  developers  suggest  using  a  database  so  there  will  be  a  more  efficient  data  storing 
system and for the data to be stored for a long duration.
- The developers suggest using a compiler that has more memory than the current compiler 
used.

## Program Screenshots
1. **LAUNCH OF PROGRAM & ADMIN LOGIN -** the program will ask the user to either [0] Start Program or [1] Close Program. If they chose option 1, the program will end. If option 0 was selected, it will begin the program and require an admin to login. If any other character was inputted besides 0 & 1, the output will return as invalid and will loop to the start of the program.
<img src="/images/ProgramLaunch.png" width=50% height=50%>

2. **INVENTORY -** After logging in successfully the Inventory Panel will show up and will demand the user to input the amount of the ingredients for the shop to operate and allow orders. If the admin input is a value less than 0, it will show that you cannot proceed with a negative value (since there is no negative value for an item) and will demand the user to input the number of that item again.
<img src="/images/Inventory.png" width=50% height=50%>

3. **MENU PANEL -** It will show 3 categories for the menu and Administrator Panel option and Item List option. If the user chose either “1”,”2” or “3” it will display the food under that category. After choosing what food to order it will ask the quantity or how many does the user want to buy for that item, then it computes the initial value for that food. Next, 4 Options will show, [1] Confirm Order, [2] Buy another item, [3] Edit Quantity/Delete item, [4] Cancel Order. Confirm Order finalizes the order then proceeds to the TRANSACTION PANEL. Buy another item option will loop the MENU PANEL again and will ask the user what item he/she wants to add, edit or remove. Cancel Order option will completely remove all items the user has inputted and will return to the MENU PANEL. [0] Administrator Panel Option returns you to the login interface and will demand for the user and password again. [9] Go to Item List option will display what your current order is.
<img src="/images/Menu.png" width=50% height=50%>

4.	**Edit Quantity Panel -** this section is where the customer can add or decrease the quantity of a certain item in his/her order.
<img src="/images/EditQuantity.png" width=50% height=50%>
<img src="/images/EditQuantity2.png" width=50% height=50%>

5. **TRANSACTION PANEL -** The transaction panel computes the overall price to be paid by the user. It will demand the user to input his/her payment. If the payment is exact or too much, it displays the Receipt that contains the local date and time, the product/s ordered and how much is it, the overall total, the payment and the change. Otherwise, if the payment is less than the value of what he/she needs to pay for, it will display as insufficient payment and demands the user to input the payment again. After the TRANSACTION PANEL, it will loop back again to the MENU PANEL.
<img src="/images/Transaction.png" width=50% height=50%>
<img src="/images/Transaction2.png" width=50% height=50%>

6. **Admin Panel -** this section is where the admin and staff can access the today’s sale panel, and inventory menu. This section also is where the admin and staff can stop the program.
<img src="/images/Admin.png" width=50% height=50%>

7. **TODAY’S SALES PANEL -** Will display the total item sold, the purpose of this panel is to know which product is the most popular and what product is least sold.
<img src="/images/TodaysSales.png" width=50% height=50%>

8. **REPLENISH INVENTORY PANEL -**  Will display how much stock is left. Administrators can also add a quantity of a given item to replenish the stock of it.
<img src="/images/ReplenishInventory.png" width=50% height=50%>
<img src="/images/ReplenishInventory2.png" width=50% height=50%>

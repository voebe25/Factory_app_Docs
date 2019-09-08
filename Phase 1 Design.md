<b>SALES MANAGER : </b>Person placing order on the app.

<b>FACTORY MANAGER : </b>Person fulfilling the order placed on the app.
S.M. and F.M. to have many to many relation.

Once you open the app, it will ask you to login as a Sales Manager or Factory Manager. We can keep google login if it simplifies things.

SCREEN A : 
+-------------------------+
| Login as Sales Manager  |
|                         |
|                         |
+-------------------------+
| Login as Factory Manager|
|                         |
|                         |
+-------------------------+
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
+-------------------------+

LOGIN AS SALES MANAGER : 
> Every Factory Manager will be assigned with a unique ID once they sign up. Sales manager will be asked to input F.M. ID once they sign in to establish a relationship between S.M. and F.M. 
F.M. will be notified that S.M. wants to add them to their list for placing orders and S.M. will need their approval before adding them.

SCREEN B : 
+-------------------------+
|Enter Factory Manager ID |
|________________________ |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
+-------------------------+

> Next screen would provide S.M. to chose frm the 2 options
1) Place Order
2) Get Oder Status
3) Factory Managers

SCREEN C : 
+-------------------------+
| Place Order             |
|                         |
|                         |
+-------------------------+
| Get Order Status        |
|                         |
|                         |
+-------------------------+
| Factory Managers        |
|                         |
|                         |
+-------------------------+
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
+-------------------------+

1) PLACE ORDER
S.M. will have to fill out the below form to place an order requiring to fill the mandatory fields as
  > Order from (fixed)
  > Place of Supply (fixed)
  > Private Mark (fixed)
  > Item
  > Quantity
  > Transport (Fixed)
  > Place of Dispatch (fixed)
  > Rate (optional)
  
  SCREEN D : 
+-------------------------+
| Order from : __________ |
| Place of Supply : ____  |
| Private Mark : _______  |
| Transport : __________  |
| Place of Dispatch : ___ |
| Item : _______________  |
| Qty : ________________  |
| Rate : _______________  |
|                         |
|                         |
+-------------------------+
| Add Item                |
|                         |
+-------------------------+
| Place Order             |
|                         |
+-------------------------+
|                         |
|                         |
|                         |
|                         |
|                         |
+-------------------------+

When Add item is pressed, order from, Transport and place of dispatch should be locked and should be carried over to the next screen. Item, Qty and Rate field should be blanked for the next screen.

PLACE ORDER : 

SCREEN E : (Screen auto rotate)

+------+--------+----+-----+--------+----+---+----+
|ODRDER|PLACE OF|PVT.|TRANS|PLACE OF|ITEM|QTY|RATE|
|FROM  |SUPPLY  |MARK|PORT |DISPATCH|    |   |    |
+------+--------+----+-----+--------+----+---+----+
|      |        |    |     |        |    |   |    |
|      |        |    |     |        |    |   |    |
|      |        |    |     |        |    |   |    |
|      |        |    |     |        |    |   |    |
|      |        |    |     |        |    |   |    |
+------+--------+----+-----+---+----+----+---+----+
| CANCEL ORDER  | EDIT ORDER   | CONFIRM ORDER    |
+---------------+--------------+------------------+

Cancel Order to take you back to screen C without doing anything. Simple navigation.
Edit order you to take you to Screen D with Data populated from the first item.
Confirm Order to Generate Order ID and take you back to Screen C.

GET ORDER STATUS

Screen F : (Screen Auto Rotate)
+------+--------+----+-----+--------+----+---+----+------+
|ODRDER|PLACE OF|PVT.|TRANS|PLACE OF|ITEM|QTY|RATE|ORDER |
|FROM  |SUPPLY  |MARK|PORT |DISPATCH|    |   |    |STATUS|
+------+--------+----+-----+--------+----+---+----+------+
|      |        |    |     |        |    |   |    |      |
|      |        |    |     |        |    |   |    |      |
|      |        |    |     |        |    |   |    |      |
|      |        |    |     |        |    |   |    |      |
|      |        |    |     |        |    |   |    |      |
+------+--------+----+-----+---+----+----+---+----+------+
Order Status  : In Progress, Complete or Cancel can only be modified by F.M. and can be viewed by S.M.


FACTORY MANAGERS : 

Screen G : 
+-------------------------+
| F.M. 1                  |
|                         |
|                         |
+-------------------------+
| F.M. 2                  |
|                         |
|                         |
+-------------------------+
| F.M. 3                  |
|                         |
|                         |
+-------------------------+
| Add F.M.                |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
|                         |
+-------------------------+

You can either select another F.M. to place order to a different F.M. or can add F.M.

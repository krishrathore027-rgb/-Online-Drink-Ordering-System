# -Online-Drink-Ordering-System
The "Online Drink Order System" is a console-based Pythonapplication  designed for TOPRATEEEDDD!. It aims to automate the process of ordering
 beverages by allowing customers to view a menu, select items, calculate their
 bill, and view a final order summary. This project demonstrates the use of
 fundamental programming concepts such as variables, dictionaries, loops,
 conditionals, and list manipulation.

 OBJECTIVE:
 
 1.To create a user-friendly interface for ordering drinks.
 
 2.To replace manual billing with an automated calculation system.
 
 3.To prevent billing errors by using stored price data.
 
 4.To learn and demonstrate Python control structures(While loops, If-Else
 statements).
 
 . SystemRequirements
 
 Hardware: Any computer capable of running Python.
 
 Software: Python 3.x Interpreter, any Code Editor (VS Code, PyCharm, IDLE)
 
 3. Code Explanation & Logic:
 
 The programfollows alinear logical flow:
 
 1.User Greeting: The user iswelcomed and askedfor their
 name.
 
 2.MenuDisplay: Adictionary (menu) stores the itemsand
 their prices. The menu is printed for the user to see.
 
 3.Order Loop: A while loop isin tiated to allowmultiple
 items to be ordered.
 The user inputsan item name.
 The programchecks ifthe item exists in the menu
 dictionary.
 
 4.If found: The price is added to order_total, and the item
 is added to the selected_itemslist.
 
 5.If not found: An error message is displayed prompting
 the user to checkspelling.
 
 6.Termination: The user can type 'done' or answer 'No' to
 the"add another item"prompt to finish ordering.
 
 7.Bill Generation: The program iterates through the
 selected_items list, prints the final receipt, and displays
 the total amount to pay.

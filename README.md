# Supermarket-Billing-System

Supermarket Billing System 🛒
A console-based Java application simulating a supermarket checkout system,
built as a Group Project for Data Structures & Algorithms course (DSA 2025).
Group Members
No.NameResponsibility1[Name]Item.java, Node.java2[Name]ShoppingCart.java (SLL)3[Name]UndoStack.java (Stack)4[Name]CustomerQueue.java (Queue) + BillCalculator.java (Recursive) + Main.java

Data Structures Used
StructureFilePurposeSingly Linked List (SLL)ShoppingCart.javaStore items in cartStackUndoStack.javaUndo last added item (LIFO)QueueCustomerQueue.javaManage checkout line (FIFO)RecursiveBillCalculator.javaCalculate total price by traversing SLLIterativeShoppingCart.javaDisplay all items in cart

Features

Add items to shopping cart
Undo last added item (Stack)
View all items in cart (Iterative)
Join checkout queue (Queue)
Call next customer and print receipt (Queue + Recursive)
Auto-calculate subtotal, VAT 7%, and total


How to Run
bashcd src
javac *.java
java Main

Project Structure
SupermarketSystem/
├── README.md
└── src/
    ├── Item.java           # Item model (name, price, quantity)
    ├── Node.java           # Node for linked list
    ├── ShoppingCart.java   # Singly Linked List — cart storage
    ├── UndoStack.java      # Stack — undo last item
    ├── CustomerQueue.java  # Queue — checkout line
    ├── BillCalculator.java # Recursive — calculate total
    └── Main.java           # Entry point & menu

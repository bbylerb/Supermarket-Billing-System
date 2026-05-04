# Supermarket Billing System 🛒
 
A console-based Java application simulating a supermarket checkout system,
built as a Group Project for Data Structures & Algorithms course (DSA 2025).
 
## Group Members
| No. | Name | Responsibility |
|-----|------|----------------|
| 1 | [Name] | Item.java, Node.java |
| 2 | [Name] | ShoppingCart.java (SLL) |
| 3 | [Name] | UndoStack.java (Stack) |
| 4 | [Name] | CustomerQueue.java (Queue) + BillCalculator.java (Recursive) + Main.java |
 
---
 
## Data Structures Used
 
| Structure | File | Purpose |
|-----------|------|---------|
| **Singly Linked List (SLL)** | `ShoppingCart.java` | Store items in cart |
| **Stack** | `UndoStack.java` | Undo last added item (LIFO) |
| **Queue** | `CustomerQueue.java` | Manage checkout line (FIFO) |
| **Recursive** | `BillCalculator.java` | Calculate total price by traversing SLL |
| **Iterative** | `ShoppingCart.java` | Display all items in cart |
 
---
 
## Features
- Add items to shopping cart
- Undo last added item (Stack)
- View all items in cart (Iterative)
- Join checkout queue (Queue)
- Call next customer and print receipt (Queue + Recursive)
- Auto-calculate subtotal, VAT 7%, and total
---
 
## How to Run
 
```bash
cd src
javac *.java
java Main
```
 
---
 
## Project Structure
 
```
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
```
 

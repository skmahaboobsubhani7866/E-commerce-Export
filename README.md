# 🛒 Shopping Cart System (Java)

A simple **Shopping Cart System** implemented in Java using **Object-Oriented Programming (OOP) concepts** like abstraction, inheritance, interfaces, and polymorphism.

---

## ✨ Features
- Add multiple products (Name, Price, Quantity).
- Calculate total price of the cart.
- Apply discounts:
  - **Festive Discount** → 10% off on total.
  - **Bulk Discount** → 20% off if any product has quantity > 5.
- No discount if invalid type is entered.
- Print product details and final payable amount.
- Showcase of **Abstraction, Interface, and Polymorphism**.

---

## 🛠️ Tech Stack
- **Language:** Java (JDK 8 or higher)
- **Concepts Used:**  
  - Abstraction (`Discount` abstract class)  
  - Inheritance (`FestiveDiscount`, `BulkDiscount`)  
  - Interface (`Payment`)  
  - Polymorphism (Dynamic discount calculation)

---

## 📂 Project Structure
|-- Ecommerce export (ShoppingCartSystem) #java file
|-- README.md                             #documentation


Classes:
- `Product` (Encapsulation of product details)
- `Discount` (Abstract Class)
- `FestiveDiscount` (Subclass)
- `BulkDiscount` (Subclass)
- `Payment` (Interface)
- `OnlinePayment` (Implements Payment)
- `ShoppingCartSystem` (Main Class)

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/shopping-cart-system.git
   cd shopping-cart-system
   javac ShoppingCartSystem.java
   java ShoppingCartSystem

# Author 
-Developed by SK Mahaboob Subhani
-Email : skmahaboobsubhani7866@gmail.com
-GitHub : skmahaboobsubhani7866
# Food Delivery System - Low Level Design (LLD)

A clean and modular Low-Level Design (LLD) implementation of a Food Delivery System, focusing on object-oriented principles, maintainability, and extensibility.

## 📌 Overview

This project models the core workflow of a food delivery platform similar to Zomato/Swiggy. It includes restaurant management, menu handling, order processing, delivery assignment, and user interactions—designed with clear separation of concerns and reusable components.

## 🏗️ Architecture

The system follows a layered architecture:

* **Models / Entities**: Core domain objects such as User, Restaurant, MenuItem, Cart, Order, DeliveryAgent.
* **Services**: Business logic for ordering, restaurant operations, delivery assignment, and tracking.
* **Repositories**: Abstraction for data storage (in-memory / extendable to databases).
* **Utils & Exceptions**: Shared utilities and custom exception handling.

## 🎯 Features

* User registration and restaurant onboarding
* Menu listing and item selection
* Cart management
* Order placement & tracking
* Delivery agent assignment
* Status updates for orders and deliveries
* Extensible design for adding payment, ratings, and notifications

## 🧩 Design Principles Used

* Object-Oriented Programming (OOP)
* SOLID principles
* Strategy Pattern (extendable pricing/delivery logic)
* Factory/Builder Patterns (for complex object creation)
* Interface-driven development

## 📂 Folder Structure (Example)

```
src
└── main
    └── java
        ├── models
        ├── services
        ├── repository
        ├── exceptions
        ├── utils
        └── Main.java
```

## 🚀 How to Run

1. Clone the repository.

   ```bash
   git clone <repo-url>
   ```
2. Open in your Java IDE (IntelliJ/Eclipse) or compile with:

   ```bash
   javac Main.java
   java Main
   ```
3. Explore the service classes to simulate ordering workflows.

## 🔧 Future Enhancements

* Integrate Firestore or SQL for persistent storage
* Add REST API layer using Spring Boot
* Implement payment gateway module
* Add real-time delivery tracking
* UI layer (web/mobile) integration

## 📄 License

This project is for learning and demonstration purposes.

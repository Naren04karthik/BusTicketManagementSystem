# Bus Ticket Management System

## Project Overview
The **Bus Ticket Management System** is a console-based application built using **Object-Oriented Programming (OOP) principles in Java**. This system allows users to manage bus tickets, passengers, and bookings efficiently. It incorporates OOP concepts like **classes, objects, inheritance, encapsulation, polymorphism, and exception handling** to provide a modular, maintainable, and scalable solution.

---

## Features
- **Bus Management**
  - Add, update, and view buses.
  - Track available seats in real-time.

- **Passenger Management**
  - Add new passengers, including regular and senior citizens.
  - Maintain passenger details with proper validation.

- **Ticket Management**
  - Book tickets for passengers.
  - Prevent duplicate bookings with custom exceptions.
  - Cancel tickets and update availability.
  - Generate unique ticket numbers automatically.

- **Exception Handling**
  - Custom exceptions for invalid bus operations, duplicate tickets, and non-existent tickets.

- **Interactive Console Interface**
  - Simple menu-driven interface to perform all operations.
  - Handles invalid inputs gracefully.

---

## OOP Concepts Implemented
- **Classes and Objects**: Each entity (Bus, Passenger, Ticket) is implemented as a separate class.  
- **Encapsulation**: Private data members with public getter and setter methods.  
- **Inheritance**: SeniorCitizen class inherits from Passenger to handle discounts.  
- **Polymorphism**: Method overloading and overriding for ticket generation and bus operations.  
- **Exception Handling**: Custom exceptions like `InvalidBusException`, `TicketAlreadyExistException`, `TicketDoesNotPresentException`.  
- **Modularity**: Each class resides in separate packages (`Service`, `Exceptions`, `Utility`) for better organization.

---

## Folder Structure

# Car Rental System

A simple console-based **Car Rental System** developed in **C++** using Object-Oriented Programming (OOP) concepts. The project manages customers, employees, managers, and cars while storing data in CSV files for persistence.

## Features

* User authentication for Customers, Employees, and Managers
* Rent and return cars
* View available and rented cars
* Fine and dues management
* Rental history tracking
* Manager access to add, update, and remove users and cars
* Data stored using CSV files without requiring an external database

---

## Project Structure

```
Car_Rental_System
│
├── DB/
│   ├── customer.csv
│   ├── employee.csv
│   ├── manager.csv
│   └── car.csv
│
├── Model.hpp
├── Car.cpp
├── Customer.cpp
├── Employee.cpp
├── Manager.cpp
├── DB_Manager.cpp
└── main.cpp
```

### Main Classes

* **User** : Base class containing common user details.
* **Customer** : Handles customer-related operations.
* **Employee** : Handles employee-related operations.
* **Manager** : Manages users and cars.
* **Car** : Stores car details and rental information.
* **DB Manager Classes** : Read from and write to CSV files.

---

## Functionalities

### Customer / Employee

* Login
* Rent a car
* Return a car
* View dues
* View rental details

### Manager

* Add, update, and delete users
* Add, update, and delete cars
* View all users and cars

### Car Management

* Check available cars
* Check rented cars
* Calculate rental dues and fines

---

## Data Storage

The project uses four CSV files to store:

* Customer details
* Employee details
* Manager details
* Car details

This allows data to remain available even after the program is closed.

---

## OOP Concepts Used

* Classes and Objects
* Encapsulation
* Inheritance
* Polymorphism
* Modular Design

---

## Assumptions

* A user can rent a limited number of cars based on their record.
* Cars currently rented cannot be modified by the manager.
* Deleting a user automatically returns rented cars.
* Car condition and user records are updated after returns.
* Rental duration has an upper limit.

---

## How to Run

1. Clone the repository.
2. Compile the source files using any C++ compiler.
3. Run the executable.
4. Follow the menu options to manage users and cars.

---

## Future Improvements

* Graphical User Interface (GUI)
* SQL database integration
* Online booking support
* Search and filtering options
* Better error handling and validation

---

## Technologies Used

* C++
* Object-Oriented Programming
* File Handling
* CSV Storage
* Standard Template Library (STL)

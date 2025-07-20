# 🏨 Hotel Reservation Management System

## 1. Background  
You are a Java developer working for a hotel chain that manages room bookings, guest check-ins, and reservation priorities. This project builds a simplified Hotel Reservation Management System showcasing **method overloading** and **method overriding** in the booking process.

## 2. Task Description

**🏗️ Class Structure**

- `Reservation` — Base class with overloaded methods to book rooms using guest name and VIP status
- `OnlineReservation` — Inherits from `Reservation`, overrides methods to simulate online room booking
- `WalkInReservation` — Inherits from `Reservation`, overrides method to simulate walk-in booking
- `Main` — Driver class to create and test all reservation types using method overloading and overriding

---

## 3. Concepts Covered

- **Method Overloading** (same method name, different parameters in the same class)
- **Method Overriding** (subclass modifies inherited method)
- **Inheritance** (OnlineReservation and WalkInReservation inherit from Reservation)
- **Polymorphism** (different behaviors for the same method name)
# 🚗 Transport Simulator

## 1. Background  
You are a Java developer creating a transport simulation system that models different types of vehicles. This project demonstrates **runtime polymorphism** and **abstract classes** by showing how each vehicle behaves differently through overridden methods.

## 2. Task Description

### 🏗️ Class Structure

- `Vehicle` — Abstract base class with common attributes (`name`, `fuelType`) and abstract methods for honking and journeys
- `Car` — Inherits from `Vehicle`, overrides methods to simulate car-specific behavior
- `Bus` — Inherits from `Vehicle`, overrides methods to simulate bus-specific behavior
- `ElectricScooter` — Inherits from `Vehicle`, overrides methods and adds `rechargeBattery()` for electric functionality
- `TransportSimulator` — Driver class that uses an `ArrayList` to store vehicles and demonstrates polymorphism using a loop and `instanceof`

## 3. Concepts Covered

- **Abstract Classes** (Vehicle defines abstract methods for subclasses to implement)
- **Method Overriding** (each subclass provides specific implementations of `honk()`, `startJourney()`, `stopJourney()`)
- **Runtime Polymorphism** (superclass references call subclass methods at runtime)
- **Downcasting with `instanceof`** (calls ElectricScooter-specific method `rechargeBattery()`)
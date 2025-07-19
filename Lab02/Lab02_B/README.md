# 📚 User Management in a Library System

## 1.1 Background

The goal of this project is to model a `User` class for a library management system that handles user registration, profile updates, and account management.

---

## 1.2 Task Description

- Develop a `User` class to represent individuals who interact with the library (e.g., students, faculty, guests).
- Each user has the following attributes:
  - **User ID** – Unique identifier for the user
  - **Name** – Full name of the user
  - **Phone Number** – Contact number
  - **Membership Type** – Category (Student, Faculty, Guest)
  - **Account Status** – Indicates if the account is active or inactive

- Implement the following functionalities:
  - ✅ **Register User** – Create a new user account with all required details
  - ✅ **Update Profile** – Modify user information such as name or phone number
  - ✅ **Deactivate Account** – Mark a user's account as inactive
  - ✅ **Get Profile Information** – Retrieve and display user details

---

## 1.3 Implementation Steps

- Create a `User` class with attributes and constructors.
- Write getter and setter methods for each attribute.
- Implement methods for:
  - Registering a new user
  - Updating user profile
  - Deactivating the account
  - Getting user profile information

- Create a `UserTest` class to:
  - Create and test `User` objects
  - Demonstrate all functionalities

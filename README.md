# 🏨 Hotel Management System | C++

A C++ based Hotel Management System developed using Object-Oriented Programming (OOP) concepts as part of the Programming Language Laboratory course (2021) at the Institute of Space Technology (IST), Islamabad.

The application simulates essential hotel management operations, including room reservations, customer information management, booking modifications, cancellation, billing, and complaint handling. It demonstrates the practical application of C++ programming concepts through a modular and function-oriented software design.

---

## 📌 Project Overview

The Hotel Management System provides a simplified digital solution for managing hotel operations and customer records. It allows customers to browse room categories, make reservations, enter personal information, modify existing records, and cancel bookings.

The system also provides administrative functionalities for retrieving customer records, displaying stored information, generating bills, and receiving customer complaints.

Customer information is stored in text files, allowing records to be maintained and retrieved through the application.

## ✨ Key Features

### 🛏️ 1. Room Booking
- Displays available hotel room categories.
- Allows customers to select a room according to their preferences.
- Provides room information to help customers make booking decisions.

### 👤 2. Customer Registration and Information Storage
- Collects customer information during the booking process.
- Records customer name, identification card number, mobile number, check-in date, and check-out date.
- Stores customer information in text files for future retrieval.

### 🔍 3. Customer Search
- Allows users to search for specific customer records.
- Retrieves customer information using the room number.

### ✏️ 4. Customer Information Modification
- Enables customers to modify previously entered information.
- Helps correct errors in customer registration details.

### 📋 5. Display Customer Records
- Provides password-protected access to stored information.
- Displays customer and room-related records.

### ❌ 6. Booking Cancellation
- Allows customers to cancel an existing room reservation.

### 🧾 7. Bill Generation
- Generates customer bills based on the selected room category.
- Calculates charges according to the number of days spent at the hotel.

### 💬 8. Complaint Management
- Allows customers to submit complaints regarding hotel staff and services.
- Provides a basic mechanism for collecting customer feedback.

---

## 🛠️ Technologies and Programming Concepts

| Category | Technologies / Concepts |
|---|---|
| Programming Language | C++ |
| Programming Approach | Object-Oriented Programming |
| Data Organization | Classes and Structures |
| Program Design | User-Defined Functions |
| Decision Making | Conditional Statements |
| Control Flow | Switch Statements |
| Built-in Operations | Predefined Functions |
| Data Persistence | Text File Handling |

### 💡 Programming Concepts Applied

- **Classes and Objects:** Organizing the program around structured data and related operations.
- **Structures:** Grouping related customer and hotel information.
- **User-Defined Functions:** Dividing hotel operations into independent functional modules.
- **Conditional Statements:** Implementing decision-making logic for different operations.
- **Switch Statements:** Managing menu-based choices and application navigation.
- **Predefined Functions:** Utilizing built-in C++ functions for common programming operations.
- **File Handling:** Saving customer information in text files for persistent storage.

---

## ⚙️ System Modules and Functional Workflow

The application is organized into the following functional modules:

| Function / Module | Description |
|---|---|
| `room_booking()` | Displays room categories and allows customers to select a room. |
| `save_customer()` | Collects customer information and stores it in a text file. |
| `search_customer()` | Searches for customer records using the room number. |
| `modify_info()` | Allows modification of previously stored customer information. |
| `display_info()` | Displays stored customer and room information after password verification. |
| `cancel_booking()` | Handles cancellation of existing room reservations. |
| `bill_generation()` | Generates bills based on room category and duration of stay. |
| `complains()` | Provides an interface for submitting customer complaints. |

---

## 🔄 Application Workflow

The general workflow of the Hotel Management System can be represented as:

1. Start the application.
2. Display the available hotel management operations.
3. Select the desired operation.
4. For room booking, display room categories and collect customer details.
5. Save customer information in text files.
6. Allow subsequent operations such as searching, modifying, displaying, or cancelling reservations.
7. Generate the customer bill according to room category and length of stay.
8. Accept customer complaints when required.
9. Exit the application.

---

## 🖥️ Application Interface

The running application can be opened on CLI.

| Application Screen | Description |
|---|---|
| Main Menu | Main application interface and available operations |
| Room Booking | Room categories and reservation options |
| Customer Registration | Customer information entry |
| Customer Records | Displaying stored customer information |
| Bill Generation | Customer billing interface |

---

## 🚀 Getting Started

### Prerequisites

- A C++ compiler (GCC, MinGW, or equivalent).
- A C++ development environment or code editor.

### Installation and Execution

1. Clone the repository:

   ```bash
   git clone YOUR_REPOSITORY_URL
   ```

2. Navigate to the project directory:

   ```bash
   cd Hotel-Management-System
   ```

3. Compile the source code:

   ```bash
   g++ main.cpp -o HotelManagement
   ```

4. Run the application:

   **Windows:**
   ```bash
   HotelManagement.exe
   ```

   **Linux / macOS:**
   ```bash
   ./HotelManagement
   ```

---

## 📂 Repository Structure

```text
Hotel-Management-System/
│
├── src/
│   └── main.cpp
│
├── docs
│   └── Project-Proposal.pdf
│   
└── README.md
```

---

## 🎯 Project Objectives

- Apply C++ programming language concepts to a practical software development problem.
- Understand the application of Object-Oriented Programming in developing structured applications.
- Implement modular programming through user-defined functions.
- Develop a system for managing customer information and hotel reservations.
- Explore text-file-based data storage and retrieval.
- Gain practical experience in designing and implementing a multi-functional software application.

---

## 🎓 Academic Information

| Detail | Information |
|---|---|
| Project Title | Hotel Management System |
| Institution | Institute of Space Technology (IST), Islamabad |
| Department | Electrical Engineering |
| Course | Programming Language Laboratory |
| Programming Language | C++ |
| Project Type | Academic Software Development Project |

---

## 📚 Project Scope

This project demonstrates the fundamental concepts involved in developing a hotel management application. Its modular structure provides a foundation for further development, including additional reservation options, enhanced customer record management, improved data security, and expanded hotel administration functionalities.

---

⭐ **Academic Project | C++ | Object-Oriented Programming | Hotel Management System**

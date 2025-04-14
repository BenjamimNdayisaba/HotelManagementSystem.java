# 🏨 Hotel Management System

A simple command-line based Hotel Management System built in Java. This project allows users to view available rooms, make reservations, complete payments, and view existing bookings—all via a text-based interface.

## 📜 Features

- View available rooms
- Make room reservations
- Track reservation details
- Complete payments for bookings
- Simple, menu-driven CLI interface

## 🛠️ Technologies Used

- Java (Standard Edition)
- Java Collections Framework (List, Scanner)
- Object-Oriented Programming principles

## 🧾 Class Overview

### `Room`

Represents a hotel room with:
- `roomNumber`: Unique ID for the room
- `category`: Type of room (Standard, Deluxe, Suite)
- `price`: Cost per night
- `isAvailable`: Availability status

### `Reservation`

Represents a reservation with:
- `reservationId`: Unique booking ID
- `guestName`: Name of the guest
- `room`: The booked room
- `paymentCompleted`: Tracks payment status

### `HotelManagementSystem`

Main driver class handling:
- Room initialization
- Booking and payment logic
- User interaction loop (menu system)

## 🚀 Getting Started

### Prerequisites

- Java 8 or higher installed

### How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/hotel-management-system.git
   cd hotel-management-system
   ```

2. Compile and run the Java program:

   ```bash
   javac HotelManagementSystem.java
   java com.mycompany.hotelmanagementsystem.HotelManagementSystem
   ```

> Make sure your file structure matches the package declaration, or remove the `package` line if running in a single file.

## 📸 Sample Menu

```
Hotel Reservation System
1. View Available Rooms
2. Make a Reservation
3. View Reservations
4. Complete Payment
5. Exit
```

## 📌 Notes

- Reservations are stored in memory (no database persistence).
- Room availability updates dynamically based on bookings.
- Each reservation gets a unique, auto-incremented ID.

## 🧠 Future Enhancements (Ideas)

- Add file/database persistence for room/reservation data
- Implement user authentication
- Include check-in/check-out date logic
- Add cancellation and refund handling


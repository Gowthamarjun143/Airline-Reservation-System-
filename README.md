# Airline Reservation System (VB.NET)

## 📌 Project Overview

The **Airline Reservation System** is a desktop-based application developed using **VB.NET** that automates airline ticket booking and reservation processes. The system is designed to manage flight schedules, passenger details, seat availability, and ticket reservations efficiently. It aims to reduce manual workload and improve accuracy, speed, and reliability in airline operations.

This project is suitable for **academic purposes**, **mini-projects**, and **learning Windows-based application development using VB.NET**.

---

## 🎯 Objectives

* Automate airline ticket booking and reservation
* Maintain passenger and flight records securely
* Reduce human errors in reservation handling
* Provide a user-friendly graphical interface
* Enable quick search and booking of flights

---

## 🛠️ Technology Stack

| Component            | Technology                |
| -------------------- | ------------------------- |
| Programming Language | VB.NET                    |
| Framework            | .NET Framework            |
| IDE                  | Microsoft Visual Studio   |
| Database             | MS SQL Server / MS Access |
| UI                   | Windows Forms             |

---

## ✨ Features

### Admin Module

* Add, update, and delete flight details
* Manage flight schedules and routes
* View all reservations
* Manage seat availability

### User Module

* Search available flights
* Book airline tickets
* Enter passenger details
* View booking confirmation

### System Features

* Secure data handling
* Real-time seat availability
* Error validation and alerts
* Easy navigation and clean UI

---

## 🗂️ System Modules

1. **Login Module**

   * Authentication for admin and users

2. **Flight Management Module**

   * Flight ID, source, destination, date, time, and fare

3. **Passenger Module**

   * Passenger name, age, gender, contact details

4. **Reservation Module**

   * Ticket booking, seat allocation, and confirmation

5. **Database Module**

   * Handles all CRUD operations

---

## 🧩 Database Design (Sample Tables)

### Flights Table

* FlightID (Primary Key)
* Source
* Destination
* DepartureTime
* ArrivalTime
* Fare
* AvailableSeats

### Passengers Table

* PassengerID (Primary Key)
* Name
* Age
* Gender
* ContactNumber

### Reservations Table

* ReservationID (Primary Key)
* FlightID (Foreign Key)
* PassengerID (Foreign Key)
* SeatNumber
* BookingDate

---

## ⚙️ Installation & Setup

1. Install **Microsoft Visual Studio** with .NET Framework support
2. Clone or download the project repository
3. Open the project using Visual Studio (`.sln` file)
4. Configure the database connection string in `App.config`
5. Import the database (`.sql` or `.mdb` file)
6. Build and run the project

---

## ▶️ How to Run the Application

* Launch the application
* Login as Admin or User
* Perform booking or management operations
* Exit safely after completion

---

## 🧪 Testing

* Unit testing for booking logic
* Input validation testing
* Database connectivity testing
* UI navigation testing

---

## 🚀 Future Enhancements

* Online payment gateway integration
* Email/SMS ticket confirmation
* Seat selection layout
* Web-based version
* Multi-airline support

---

## 📚 Learning Outcomes

* Hands-on experience with VB.NET
* Windows Forms UI development
* Database connectivity using ADO.NET
* CRUD operations and validation
* Real-world application design

---

## 👤 Author

**Gowtham arjun**
Department of Computer Science

---

## 📄 License

This project is developed for **educational purposes only**.

---


⭐ *If you find this project helpful, consider giving it a star!*

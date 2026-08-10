# Smart Parking System

## 📌 Description

The **Smart Parking System** is a Java-based application designed to manage parking spaces efficiently.

Users can register their vehicles, view available parking slots, reserve a parking slot, check parking details, calculate parking fees, and release parking slots after completing their parking.

This project demonstrates Java Object-Oriented Programming, collections, methods, loops, conditional statements, and user input handling.

## ✨ Features

* 🚗 Vehicle Registration
* 🅿️ View Parking Slots
* 🔎 Check Slot Availability
* 📌 Reserve Parking Slot
* 🕐 Record Parking Time
* 💰 Calculate Parking Fee
* 📋 View Parking Records
* 🚪 Release Parking Slot
* 🔄 Update Slot Status

## 🛠️ Technologies Used

* **Programming Language:** Java
* **Concepts:** Object-Oriented Programming (OOP)
* **Collections:** ArrayList
* **Input Handling:** Scanner
* **Data Storage:** In-memory collections
* **IDE:** VS Code / Eclipse / IntelliJ IDEA

## 📂 Project Structure

```text
smart-parking-system/
│
├── Vehicle.java
├── ParkingSlot.java
├── ParkingRecord.java
├── ParkingManager.java
├── SmartParkingSystem.java
└── README.md
```

## ▶️ How to Run

1. Install Java JDK.
2. Clone or download this repository.
3. Open the project in VS Code, Eclipse, or IntelliJ IDEA.
4. Open `SmartParkingSystem.java`.
5. Compile the Java program.
6. Run the `SmartParkingSystem` class.
7. Register a vehicle.
8. View available parking slots.
9. Reserve a slot.
10. Release the slot when parking is completed.

## 🔍 How It Works

The application follows these steps:

1. Vehicle owner registers their vehicle.
2. Available parking slots are displayed.
3. User selects an available parking slot.
4. Vehicle is assigned to the selected slot.
5. The system records the parking details.
6. Parking fee is calculated based on parking duration.
7. User releases the parking slot.
8. The slot becomes available again.

### Example

```text
===== SMART PARKING SYSTEM =====

1. Register Vehicle
2. View Parking Slots
3. Park Vehicle
4. View Parking Records
5. Calculate Parking Fee
6. Release Parking Slot
7. Exit

Enter your choice: 3

Enter Vehicle Number: AP02AB1234
Enter Vehicle Type: Car
Enter Parking Slot: 5
Enter Parking Hours: 3

Vehicle parked successfully!

Slot Number: 5
Vehicle: AP02AB1234
Parking Hours: 3
Parking Fee: ₹150
Status: Occupied
```

## 💰 Parking Fee Calculation

The system calculates the parking fee based on the number of hours.

```text
Parking Fee = Parking Hours × Price Per Hour
```

Example:

```text
Parking Hours = 3
Price Per Hour = ₹50

Parking Fee = 3 × 50
            = ₹150
```

## 🅿️ Parking Slot Status

```text
Available
    ↓
Reserved
    ↓
Occupied
    ↓
Released
    ↓
Available
```

## 🎯 Objectives

* To develop a simple smart parking management application.
* To practice Java Object-Oriented Programming.
* To manage parking slots and vehicle records.
* To check parking slot availability.
* To calculate parking fees automatically.
* To implement parking and slot release functionality.
* To improve Java programming and problem-solving skills.

## 🚀 Future Enhancements

* Add MySQL database connectivity.
* Add user login and authentication.
* Add automatic number plate recognition.
* Add real-time parking slot sensors.
* Add QR code-based parking.
* Add online payment functionality.
* Add parking reservation notifications.
* Add admin dashboard.
* Add graphical user interface.
* Develop a web or mobile version.

## ⚠️ Note

This is a **console-based educational project**. It does not use real parking sensors, GPS, cameras, or online payment services.

## 👩‍💻 Author

Bhavana

B.Tech – Computer Science and Engineering

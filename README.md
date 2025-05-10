# Vehicle_Management_System
# 🚗 Vehicle Management System

A Python-based desktop application using **Tkinter** to manage a collection of vehicles, including **Cars**, **Trucks**, and **Bikes**. Data is stored in a local `JSON` file for simplicity and persistence.

## ✨ Features

- Add new vehicles (Car, Truck, Bike)
- Remove vehicles by ID
- Display all saved vehicles in a GUI
- Data saved persistently in `vehicles.json`
- Object-oriented design with inheritance

## 📦 Requirements

- Python 3.x

This project uses only standard Python libraries:
- `tkinter` (for GUI)
- `json` (for data storage)
- `os` (for file handling)

## 📁 File Structure
vehicle_management/
│
├── vehicles.json # JSON file for storing vehicle data
├── main.py # Main application code (provided above)
└── README.md # Project documentation (this file)

bash
Copy
Edit

🛠️ Vehicle Types and Inputs
Type	Additional Info Field
Car	Number of Doors (integer)
Truck	Payload Capacity in Tons (float)
Bike	Engine Capacity in CC (integer)

Ensure the vehicle type field is entered as Car, Truck, or Bike.

🧰 Example
Adding a Car:

ID: C001

Brand: Toyota

Model: Corolla

Year: 2020

Type: Car

Additional Info: 4 (number of doors)

📌 Notes
The app will automatically create a vehicles.json file if it doesn't exist.

All entries are saved persistently, even after closing the app.

🧑‍💻 Author
Created by [Your Name]


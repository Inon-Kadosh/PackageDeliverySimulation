# PackageDeliverySimulation

# 📦 Package Delivery Simulation

A Java-based simulation of a **package delivery company**, built as part of an Object-Oriented Programming course.  
The system models **branches, trucks, and packages** — each running as independent threads — and simulates their lifecycle from creation to delivery.

---

## 🧠 Overview

This project demonstrates key OOP principles and multi-threading concepts in Java.  
It visually represents how packages are created, transferred, stored, and delivered within a network of branches and trucks.

The simulation includes:
- **Real-time tracking** of packages
- **GUI visualization** of truck movement and package flow
- **Thread-based** model for branches and trucks
- **Comprehensive event logging** for all package lifecycle stages

---

## 🚀 Features

- 🏢 **Branch management:** handles storage and transportation of packages  
- 🚛 **Truck simulation:** each truck runs as a thread, performing deliveries  
- 📦 **Package lifecycle:** from creation → collection → hub → delivery  
- 🎨 **Graphical UI:** real-time animation of trucks and packages  
- 📜 **Tracking log:** textual tracking of every package status (`tracking.txt`)

---

## 🛠️ Technologies Used

- **Language:** Java  
- **Paradigm:** Object-Oriented Programming (Inheritance, Polymorphism, Encapsulation)  
- **Concurrency:** Multi-threading (Thread class & synchronization)  
- **GUI:** Swing / AWT  
- **Tools:** IntelliJ IDEA, GitHub  

---

## 🧩 Class Structure

| Component | Description |
|------------|-------------|
| `MainOffice` | Manages system initialization and simulation ticks |
| `Branch` | Stores packages and dispatches trucks |
| `Truck` | Base class for all truck types |
| `Van`, `StandardTruck`, `NonStandardTruck` | Specialized trucks with unique delivery behavior |
| `Package` | Abstract base class for all package types |
| `SmallPackage`, `StandardPackage`, `NonStandardPackage` | Specific package implementations |
| `Tracking` | Manages status history of each package |
| `Point` | Represents coordinates for truck movement |

---
![Simulation Screenshot 1](https://github.com/user-attachments/assets/ee876923-900d-4e13-a8bc-feddf8542108)
![Simulation Screenshot 2](https://github.com/user-attachments/assets/689c38c7-27f3-41b2-80b1-61838c7e71d9)
![Simulation Screenshot 3](https://github.com/user-attachments/assets/6b16843f-04c8-48f5-8855-8f4feb76ceed)


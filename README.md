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
## 🖼️ Simulation Gallery

<p align="center">
  <img src="assets/guu1" width="700"><br>
  <em>Main system initialization interface</em>
</p>

<p align="center">
  <img src="assets/gui2" width="700"><br>
  <em>Package tracking window (real-time view)</em>
</p>

<p align="center">
  <img src="assets/gui3" width="700"><br>
  <em>Package data table showing delivery statuses</em>
</p>


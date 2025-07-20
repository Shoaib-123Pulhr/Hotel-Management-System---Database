# 🏨 Hotel Management System – SQL Database Project

## 📘 Overview
The **Hotel Management System** is a relational database project designed to streamline and organize hotel operations such as guest registration, room booking, check-in/check-out, billing, and payments. This system ensures data accuracy, improves efficiency, and supports real-time reporting for hotel management.

---

## 🎯 Objective
To build a robust and scalable SQL database that allows hotel staff to:
- Manage guest information
- Track room availability
- Handle booking and reservation processes
- Process payments and generate bills
- Generate reports for analysis

---

## 🧱 Database Schema

### 📂 Tables Included:
- **`guests`** – Stores guest information (name, contact, address)
- **`room_types`** – Room category definitions (e.g., Single, Double, Suite)
- **`rooms`** – Individual rooms with status and type
- **`bookings`** – Booking information including guest, room, and date range
- **`payments`** – Payment records with method and amount

### 📌 Entity Relationships:
- One guest → Many bookings
- One room_type → Many rooms
- One room → Many bookings
- One booking → Many payments

---

## 💡 Features

✅ Guest registration and tracking  
✅ Real-time room availability  
✅ Booking lifecycle: Check-in and Check-out  
✅ Billing system with total cost calculation  
✅ Payment recording (Cash, Card, etc.)  
✅ Revenue and occupancy reporting

---

## ⚙️ Technologies Used
- **Database:** MySQL (can be adapted to PostgreSQL or SQLite)
- **Language:** SQL
- **Tools:** MySQL Workbench, DBeaver, or any SQL client
- **Optional:** PHP, Python (Flask), or Django for frontend integration

---


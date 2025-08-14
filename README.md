# 💊 Pharmacy Management System

A simple **Pharmacy Management System** built using **PHP** and **MySQL** (XAMPP).  
This system allows retail/wholesale medical shop owners to manage medicines, inventory, and sales efficiently.

---

## 📌 Features

- **Medicine Management**
  - Add new medicines
  - Edit/update medicine details
  - Delete medicines
  - Track expiry dates

- **Sales Management**
  - Create sales bills
  - Automatic stock deduction after sales
  - Store customer name and phone number during checkout

- **Inventory Alerts**
  - Low stock alerts
  - Expired medicines tracking

- **User-Friendly**
  - Simple PHP & MySQL
  - No frameworks like Laravel
  - Easy to run on XAMPP

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP (Core PHP, no frameworks)
- **Database:** MySQL
- **Server:** Apache (XAMPP)

---

## 📂 Project Structure
pharmacyms/
│
├── db.php # Database connection file
├── index.php # Homepage / Dashboard
│
├── src/
│ ├── medicines/
│ │ ├── add.php # Add medicine
│ │ ├── edit.php # Edit medicine
│ │ ├── delete.php # Delete medicine
│ │ └── list.php # List all medicines
│ │
│ ├── sales/
│ │ ├── cart.php # Sales cart system
│ │ ├── checkout.php # Final checkout (stores customer name & phone)
│ │ └── history.php # Sales history
│
└── assets/
├── css/ # Stylesheets
└── js/ # JavaScript files


---

## 📥 Installation & Setup

### 1️⃣ Install XAMPP
- Download and install [XAMPP](https://www.apachefriends.org/).
- Start **Apache** and **MySQL**.

### 2️⃣ Clone the Repository
```bash
cd C:\xampp\htdocs\
git clone https://github.com/yourusername/pharmacyms.git



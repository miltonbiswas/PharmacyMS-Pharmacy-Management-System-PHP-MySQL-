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

pharmacyms/
├── 📁 assets/ # CSS, JS, and images
│ ├── style.css # Main stylesheet
│ ├── script.js # Main JavaScript file
│ └── logo.png # App logo
│
├── 📁 includes/ # Reusable PHP includes
│ ├── db.php # Database connection
│ ├── header.php # Common header
│ ├── footer.php # Common footer
│
├── 📁 screenshots/ # App screenshots for README
│ ├── login_page.png
│ ├── billing_page.png
│ └── inventory_page.png
│
├── 📁 sql/ # Database exports
│ └── pharmacyms.sql # SQL dump file
│
├── index.php # Login page
├── dashboard.php # Dashboard page
├── billing.php # Billing system
├── checkout.php # Checkout & store customer info
├── inventory.php # Inventory management
├── add_product.php # Add new medicine
├── edit_product.php # Edit medicine details
├── delete_product.php # Delete medicine
│
├── README.md # Project documentation
└── LICENSE # License file
---

## 📥 Installation & Setup

### 1️⃣ Install XAMPP
- Download and install [XAMPP](https://www.apachefriends.org/).
- Start **Apache** and **MySQL**.

### 2️⃣ Clone the Repository
```bash
cd C:\xampp\htdocs\
git clone https://github.com/yourusername/pharmacyms.git



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

## 📥 Installation & Setup

### 1️⃣ Install XAMPP
- Download and install [XAMPP](https://www.apachefriends.org/).
- Start **Apache** and **MySQL**.

### 2️⃣ Clone the Repository
```bash
cd C:\xampp\htdocs\
git clone https://github.com/yourusername/pharmacyms.git

3️⃣ Import the Database

Open phpMyAdmin in your browser:
http://localhost/phpmyadmin

Create a new database: pharmacyms

Import the provided pharmacyms.sql file from the project folder.

4️⃣ Configure Database Connection

Open db.php and update MySQL username/password if needed:
$host = "localhost";
$user = "root";
$pass = "";
$dbname = "pharmacyms";

5️⃣ Run the Application

Visit:
http://localhost/pharmacyms

🧑‍💻 Usage
Adding Medicine
Go to Medicines → Add
Fill in details like Name, Batch No., Expiry Date, Quantity, Price.
Selling Medicines
Go to Sales → Cart
Add medicines to the cart
Click Checkout
Enter Customer Name and Phone Number
Bill will be generated, and stock will be updated automatically.

📜 License

This project is licensed under the MIT License - you can use, modify, and distribute it freely.

Author

Milton Biswas
📧 Email: miltonbiswasdev@gmail.com
💼 GitHub: miltonbiswas


🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss what you would like to change.

⭐ Support

If you find this project useful, please star the repository to show your support!

---

If you want, I can now also prepare:  
1. **SQL dump file (`pharmacyms.sql`)**  
2. **Screenshot pack** with neatly named PNGs for each page  

so the repo is **completely ready to upload** without extra work.  
Do you want me to prepare those now?

# Pharmacy Management System

This is a PHP-based Pharmacy Management System designed to manage
medicines, customers, stock, and billing in a small-scale or medium-sized pharmacy.

## 🛠️ Technologies Used

- PHP (Core PHP, no frameworks)
- MySQL (Database)
- HTML, CSS, JavaScript (Frontend)
- Bootstrap (for responsive UI)
- XAMPP (for local development)

## 📁 Project Structure

Pharmacy-Management/
├── index.php
├── login.php
├── dashboard.php
├── add_medicine.php
├── manage_customers.php
├── manage_stock.php
├── billing.php
├── bootstrap/
│ ├── css/
│ ├── js/
│ └── fonts/
├── includes/
│ ├── db.php
│ ├── header.php
│ └── footer.php
├── assets/
│ ├── images/
│ └── styles/
├── pharmacy.sql
└── README.md


## 💻 How to Run the Project

1. **Install XAMPP** from [https://www.apachefriends.org/](https://www.apachefriends.org/).
2. Start **Apache** and **MySQL** from the XAMPP Control Panel.
3. Place the project folder inside `htdocs` (e.g., `C:\xampp\htdocs\Pharmacy-Management`).
4. Import the database:
   - Open **phpMyAdmin** (`http://localhost/phpmyadmin`)
   - Create a new database (e.g., `pharmacy.db`)
   - Import `pharmacy.sql` file inside it
5. Access the system in browser:  
   `http://localhost/Pharmacy-Management`

## 🔐 Admin Login

> Add admin login credentials in the `login.php` file or database as required.
> User Name: admin
> Password:admin123

## 📌 Features

- Add/Edit/Delete Medicines
- Manage Customers
- Handle Billing & Invoices
- View Stock Details
- Responsive UI using Bootstrap

## 📂 Database

- MySQL database structure is provided in `pharmacy.sql`.

## 📃 License

This project is for educational purposes only.



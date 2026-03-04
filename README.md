# 📚 Library Management System (AWS Deployed)

A web-based Library Management System built using **PHP and MySQL**, deployed on **AWS EC2 with Amazon RDS** for scalable cloud-based database management.

---

# 🚀 Features

• Manage books and library inventory
• Add and manage library members
• Track book loans and returns
• Identify overdue books
• Dashboard with real-time statistics
• Responsive user-friendly interface

---

# ☁️ Cloud Architecture

This project is deployed using a LAMP-based cloud architecture.

```
User Browser
      │
      ▼
EC2 (Ubuntu Server)
Apache + PHP
      │
      ▼
Amazon RDS
MySQL Database
```

---

# 🛠 Tech Stack

Frontend

* HTML
* CSS
* Bootstrap
* FontAwesome

Backend

* PHP

Database

* MySQL

Cloud Infrastructure

* AWS EC2 (Ubuntu)
* Amazon RDS
* Apache Web Server

Version Control

* Git & GitHub

---

# ⚙️ Deployment Steps

1️⃣ Launch EC2 instance (Ubuntu)

2️⃣ Install LAMP stack

```
sudo apt update
sudo apt install apache2 php php-mysql mysql-client -y
```

3️⃣ Clone repository

```
git clone https://github.com/YOUR_USERNAME/library-management-system.git
```

4️⃣ Move files to web directory

```
sudo mv * /var/www/html/
```

5️⃣ Configure database connection

Update `config.php` with your **RDS endpoint**.

6️⃣ Import database

```
mysql -h RDS-ENDPOINT -u admin -p library_management < library_management.sql
```

---

# 📷 Screenshots

Add screenshots of:

* Dashboard
* Books management
* Members page
* Loans page

---

# 📈 Learning Outcomes

• Deploying applications on AWS EC2
• Connecting EC2 with Amazon RDS
• Managing cloud infrastructure
• Hosting PHP applications on Apache
• Using GitHub for version control

---

# 👨‍💻 Author

Developed by 77atul

If you like this project ⭐ the repository.

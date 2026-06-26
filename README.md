# 💻 Mobadratna Core Engine

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:7c3aed&height=160&section=header&text=Mobadratna%20Core%20Engine&fontSize=42&fontColor=ffffff&fontFamily=Outfit" width="100%" />
</div>

<div align="center">
  ![PHP](https://img.shields.io/badge/PHP-v8-blue?logo=php&style=for-the-badge) ![MySQL](https://img.shields.io/badge/MySQL-v8-blue?logo=mysql&style=for-the-badge) ![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
</div>

---

## 📌 Project Overview (Description)
Secure, high-performance RESTful API engine built with raw PHP and MySQL to manage authentication, activity configurations, volunteer tracking, and administrative analytics.

This codebase represents professional software development practices, clean database integrations, and secure backend coding standards.

---

## ⚡ The Engineering Challenge

### 🔴 Problem
Building secure database-driven APIs requires careful management of connection states, prevention of security flaws like SQL injections, and managing custom sessions without third-party frameworks.

### 🟢 Solution
This project implements:
* **PDO Database Protection**: Prepared statements to fully eliminate SQL injection vectors.
* **HTTP Sessions Security**: Customized session handling wrapper keeping access state protected.
* **REST Routing Protocol**: Native handlers to manage JSON requests and response formatting safely.

---

## 🧬 System Architecture
The internal layout structures are separated logically:
```text
mobadratna-core-engine/
├── admin/               # Administrative backend panels
├── uploads/             # Server file upload storage
├── api.php              # API Endpoint entry routing point
├── config.php           # Core global configuration parameters
├── database.php         # PDO connection pooling initializer
├── database.sql         # SQL scheme migration script
└── helpers.php          # Utility methods for validations
```

---

## 🛠️ Technology Stack

| Technology | Purpose |
| :--- | :--- |
| PHP | Scripting language for backend logic |
| MySQL | Relational database storage |

---

## 🚀 Local Developer Setup & Run

### 📋 Prerequisites
* PHP v8.0+ and MySQL database (e.g., Apache/MySQL inside XAMPP)

### ⚙️ Quick Start Steps
```bash
git clone https://github.com/Mobadratna-Org/mobadratna-core-engine.git
cd mobadratna-core-engine
# Import database.sql inside MySQL database
# Set database parameters inside config.php / database.php
# Host directory on Apache root directory (htdocs) and access it
```

---

## 🔮 Future Improvements
* [ ] Migrate database schemas to Laravel Eloquent ORM.
* [ ] Integrate JWT tokens for API stateless authentication.

---

## 👥 Contributors
* **Sayed Herzallah** - Lead Developer & Systems Architect

---

## 📄 License
Licensed under the **MIT License**.

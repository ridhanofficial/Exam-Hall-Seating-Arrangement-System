<div align="center">

# 🎓 Exam Hall Seating Arrangement System

[![PHP](https://img.shields.io/badge/PHP-7.4+-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://php.net)
[![MySQL](https://img.shields.io/badge/MySQL-5.7+-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://mysql.com)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-4.5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)


**Automated exam hall seating arrangement system for educational institutions.**

[🌐 **Live Demo**](https://pi-tech.likesyou.org/) • [🚀 **Install**](#-installation)

---

</div>

## ✨ Features

- **Admin Panel**: Manage students, rooms, subjects & seat allocation
- **Student Portal**: View seat assignments & exam schedules  
- **Automation**: Smart seat allocation algorithms
- **Reports**: PDF generation for seating charts
- **Security**: Role-based access with session management


## 🛠️ Tech Stack

- **Backend**: PHP 7.4+, MySQL
- **Frontend**: Bootstrap 4, HTML5, CSS3
- **Reports**: FPDF Library

## 🌐 Live Demo

<div align="center">

### 🖥️ **Try the System Live**

[![Demo](https://img.shields.io/badge/🌐_Live_Demo-Available-success?style=for-the-badge)](https://pi-tech.likesyou.org/)

**🔗 Demo URL**: [https://pi-tech.likesyou.org/](https://pi-tech.likesyou.org/)

</div>

### 🎯 Demo Access Credentials

| Role | Login | Password | Access |
|------|-------|----------|---------|
| **👨‍💼 Admin** | `Admin1002` | `root12` | Full system management |


## 🚀 Installation

1. **Clone & Setup**
   ```bash
   git clone https://github.com/ridhanofficial/Exam-Hall-Seating-Arrangement-System
   cd exam-seating-system
   ```

2. **Database**
   ```sql
   CREATE DATABASE seating;
   mysql -u username -p seating < seating.sql
   ```

3. **Configure** - Edit `db.php` with your database credentials

4. **Install FPDF** - Run `yoursite.com/install_fpdf.php` or download from [fpdf.org](http://www.fpdf.org)


## 📖 Usage

**Admin**: Login → Manage students/rooms → Allocate seats → Generate reports  
**Student**: Login → View seat assignment → Check schedule


## 🔒 Security

Input validation • SQL injection prevention • Session management • Role-based access

---

<div align="center">

**Built with ❤️ for Educational Excellence** | [License](LICENSE)

</div>


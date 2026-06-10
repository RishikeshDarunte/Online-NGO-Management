# 🌐 Online NGO Management System

> A centralized web platform for NGO verification, donor management, donation tracking, and administrative oversight — built to bring transparency and accountability to non-profit operations.

![ASP.NET](https://img.shields.io/badge/ASP.NET-Web_Forms-512BD4?style=flat-square&logo=dotnet)
![CSharp](https://img.shields.io/badge/C%23-.NET_Framework-239120?style=flat-square&logo=csharp)
![SQL Server](https://img.shields.io/badge/Database-SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver)
![Visual Studio](https://img.shields.io/badge/IDE-Visual_Studio_2022-5C2D91?style=flat-square&logo=visualstudio)
![License](https://img.shields.io/badge/License-Academic-orange?style=flat-square)

---

## 📌 Overview

The **Online NGO Management System** is a web-based application developed using **ASP.NET Web Forms**, **C#**, and **SQL Server**. It provides a centralized platform for:

- ✅ NGO registration and administrator verification
- ✅ Donor registration, login, and donation management
- ✅ Transparent donation tracking and history
- ✅ Volunteer registration management
- ✅ Admin monitoring, reporting, and system control

The system bridges the gap between NGOs and donors by ensuring that only **verified NGOs** can receive donations, improving trust, transparency, and accountability across the board.

---

## ✨ Features

### 🏢 NGO Module
| Feature | Description |
|---|---|
| NGO Registration | NGOs can create and register their organization profile |
| Profile Management | Update and maintain NGO details |
| Verification Request | Submit verification requests to the administrator |
| View Verification Status | Track the current approval status in real time |

### 🙋 Donor Module
| Feature | Description |
|---|---|
| Registration & Login | Secure donor account creation and authentication |
| Profile Management | Manage personal and donation preferences |
| Browse Verified NGOs | Discover and explore administrator-approved NGOs |
| Make Donations | Donate directly to a chosen verified NGO |
| Donation History | View complete record of past donations |

### 🛡️ Admin Module
| Feature | Description |
|---|---|
| Secure Login | Protected administrator access |
| NGO Verification | Review, approve, or reject NGO verification requests |
| Manage NGOs & Donors | Full CRUD control over registered entities |
| Monitor Donations | Track all donation transactions in the system |
| Generate Reports | Export and view system-wide reports |
| System Management | Oversee platform settings and user management |

### 💰 Donation Management
- End-to-end **donation tracking**
- Comprehensive **donation records** management
- **Transaction monitoring** for administrators
- **Full donation history** accessible to donors

### 🔒 Security Features
- User **Authentication** (login/logout)
- **Role-Based Access Control** (Admin / NGO / Donor)
- Secure **Data Management** with validation
- Input **Validation and Verification** across all forms

---

## 🛠️ Technology Stack

| Layer | Technology |
|---|---|
| **Frontend** | ASP.NET Web Forms, HTML, CSS, JavaScript |
| **Backend** | C# (.NET Framework) |
| **Database** | SQL Server (SSMS) |
| **IDE** | Visual Studio 2022 |
| **Version Control** | Git & GitHub |

---

## 🗂️ System Modules

```
Online NGO Management System
│
├── 1. NGO Registration and Verification
├── 2. Donor Management
├── 3. Donation Management
├── 4. Volunteer Management
├── 5. Admin Dashboard
└── 6. Reporting and Monitoring
```

---

## 🎯 Project Objectives

- 📂 **Digitize** NGO management processes to eliminate manual paperwork
- 🔍 **Provide transparency** in the donation platform
- ✅ **Enable NGO verification** before accepting any donations
- 🤝 **Improve donor trust** and organizational accountability
- 📉 **Reduce manual record-keeping** through centralized data management

---

## ⚙️ Installation

### Prerequisites

Make sure the following are installed on your system:

- [Visual Studio 2022](https://visualstudio.microsoft.com/)
- [.NET Framework](https://dotnet.microsoft.com/)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)

### Setup Steps

**1. Clone the repository**
```bash
git clone https://github.com/RishikeshDarunte/Online-NGO-Management.git
```

**2. Open the solution in Visual Studio**
```
File → Open → Project/Solution → select the .sln file
```

**3. Create the database in SSMS**
```sql
CREATE DATABASE ngo_management;
```

**4. Import the database script**
```
Open the provided .sql script in SSMS and execute it to create all required tables and seed data.
```

**5. Update the connection string**

Open `Web.config` and update the connection string:
```xml
<connectionStrings>
  <add name="NGOConnectionString"
       connectionString="Data Source=localhost;Initial Catalog=ngo_management;Integrated Security=True;"
       providerName="System.Data.SqlClient" />
</connectionStrings>
```

> **Note:** If using SQL Server Authentication instead of Windows Authentication, use:
> ```
> Data Source=localhost;Initial Catalog=ngo_management;User Id=sa;Password=yourpassword;
> ```

**6. Build and run the project**
```
Build → Build Solution (Ctrl + Shift + B)
Debug → Start (F5)
```

---

## 📸 Screenshots

### 🏠 Home Page
<img width="1920" height="1080" alt="Home" src="https://github.com/user-attachments/assets/f6e9a7e8-4957-4ebe-b130-7ee1f3e0f4a4" />

### 📝 NGO Registration
<img width="1920" height="1080" alt="Registration" src="https://github.com/user-attachments/assets/9d3e08a4-4775-43ae-b389-36ea3d85941a" />

### 🔑 Login Page
<img width="1920" height="1080" alt="Login" src="https://github.com/user-attachments/assets/45383bfc-d6aa-4106-ad8f-2c89294328b7" />

### 🛡️ Admin Dashboard
<img width="1920" height="1080" alt="Admin" src="https://github.com/user-attachments/assets/dd44312e-dcb0-4fb7-b711-ae4b0ac540b5" />

### 📊 Donor Dashboard
<img width="1920" height="1080" alt="NGO Dashboard" src="https://github.com/user-attachments/assets/d13c96c2-fd76-4952-b1ed-3091bbe34d5a" />

### 💳 Donation Page
<img width="1920" height="1080" alt="Donation Page" src="https://github.com/user-attachments/assets/738dbd38-6d5b-4f3e-a27c-2886f7ae33f8" />


---

## 🚀 Future Enhancements

| Enhancement | Description |
|---|---|
| 💳 Online Payment Gateway | Integrate Razorpay / PayPal for real-time online payments |
| 📩 Email & SMS Notifications | Automated alerts for donations, verification status, and updates |
| 📱 Mobile Application | Native Android/iOS companion app |
| 📈 Advanced Analytics Dashboard | Visual charts and metrics for admins and NGOs |
| 📡 Real-Time Donation Tracking | Live donation feeds and progress bars |
| 📋 NGO Performance Reports | Impact reports and outcome summaries per NGO |

---

## 👨‍💻 Author

**Rishikesh Darunte**

[![GitHub](https://img.shields.io/badge/GitHub-RishikeshDarunte-181717?style=flat-square&logo=github)](https://github.com/RishikeshDarunte)

---

## 📄 License

This project is developed for **academic and educational purposes** as part of the DBATU curriculum.

---

> *"Transparency builds trust. Technology enables transparency."*

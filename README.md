# 🗂️ Employee Management System

A full-stack web application built with **ASP.NET Core MVC** for managing 500+ employee records with complete lifecycle support — from onboarding to role management and attendance tracking.

---

## 🚀 Live Demo

> _Coming soon / Run locally using the steps below_

---

## 📌 Features

- ✅ Employee onboarding & offboarding
- ✅ Department assignment & role management
- ✅ Attendance tracking
- ✅ RESTful APIs with ASP.NET Web API
- ✅ N-Tier architecture (Controller → Service → Repository)
- ✅ Entity Framework ORM with SQL Server
- ✅ Responsive UI with Bootstrap 5

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | ASP.NET Core MVC, ASP.NET Web API, C# |
| ORM | Entity Framework Core |
| Database | SQL Server (T-SQL, Stored Procedures, Indexing) |
| Frontend | Bootstrap 5, JavaScript, AJAX, HTML5, CSS3 |
| Tools | Visual Studio, Git, GitHub, Postman, SSMS |

---

## 🏗️ Architecture

```
EMS.Client          → MVC Controllers & Views (UI Layer)
EMS.BusinessService → Business Logic / Service Layer
EMS.IServices       → Service Interfaces
EMS.DataAccess      → Repository Pattern (EF Core)
EMS.DataAccess.ADO  → ADO.NET Data Access
EMS.IDataAccess     → Repository Interfaces
EMS.Models          → Entity & DTO Models
EMS.DB              → SQL Scripts & Database Schema
EMS.Web             → Web Entry Point
EMS.Test1           → Unit Tests
```

**Design Patterns Used:** MVC, Repository Pattern, Service Layer, N-Tier Architecture, OOP Principles

---

## ⚙️ How to Run Locally

### Prerequisites
- Visual Studio 2022+
- SQL Server / SQL Server Express
- .NET 6 or later

### Steps

**1. Clone the repository**
```bash
git clone https://github.com/SakethiConnect/EmployeeManagementSystem.git
cd EmployeeManagementSystem
```

**2. Set up the database**
- Open **SSMS** (SQL Server Management Studio)
- Run the SQL scripts located in the `/EMS.DB` folder to create the database and tables

**3. Update connection string**

In `EMS.Client/appsettings.json` (or `EMS.Web/appsettings.json`):
```json
"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER_NAME;Database=EMS_DB;Trusted_Connection=True;TrustServerCertificate=True;"
}
```

**4. Open & Run**
- Open `EMS.sln` in **Visual Studio**
- Set `EMS.Client` or `EMS.Web` as the startup project
- Press **F5** to run

---

## 📊 Key Highlights

- 📉 Reduced code duplication by **~30–40%** using N-Tier architecture and MVC design patterns
- 👥 Manages **500+ employee records** with full lifecycle support
- 🔗 RESTful APIs with proper routing, request-response cycles, and data serialization
- 🌿 Structured Git workflow — branching strategy, meaningful commits, and pull request flows
- 🧪 Unit testing included in `EMS.Test1`

---

## 📁 Project Structure

```
EmployeeManagementSystem/
├── EMS.Client/              # MVC Views & Controllers
├── EMS.BusinessService/     # Business Logic Layer
├── EMS.IServices/           # Service Interfaces
├── EMS.DataAccess/          # EF Core Repository
├── EMS.DataAccess.ADO/      # ADO.NET Repository
├── EMS.IDataAccess/         # Repository Interfaces
├── EMS.Models/              # Models & DTOs
├── EMS.Services/            # Service Implementations
├── EMS.DB/                  # SQL Scripts
├── EMS.Web/                 # Web Entry Point
├── EMS.Test1/               # Unit Tests
└── EMS.sln                  # Solution File
```

---

## 👨‍💻 Author

**Gangishetty Saketh Sai**  
Junior .NET Developer | Full Stack .NET Developer  
📧 g.sakethsai2723@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/gangishetty-saketh-sai-27643927a) | [GitHub](https://github.com/GSakethSai)

---

## 📄 License

This project was developed during an internship at **iConnect Tech Solutions**.  
All rights reserved © 2025 iConnect Tech Solutions.

# Company Administration MVC

🎯 This is a multi-layered ASP.NET Core MVC web application designed for managing employees, departments, and user roles with full authentication and authorization using Identity.

---

## 📌 Features

- ✅ **User Management**: Sign up, Sign in, reset password, manage roles and permissions.
- 🏢 **Department Module**: Create, update, delete, and view departments.
- 👨‍💼 **Employee Module**: CRUD operations for employees with department assignment.
- 🔐 **Role-based Authorization**: Secure access to pages based on user roles.
- 🗂️ **Unit of Work & Repository Pattern**: Clean separation of data access logic.
- ✉️ **Email Configuration**: Forgot password functionality using email.
- 🧪 **Data Validation**: Both client-side and server-side.
- 🧭 **Partial Views**: For better UI reusability.
- 🗃️ **Entity Framework Core** with Code First & Migrations.

---

## 🧱 Project Structure

- `CompanyAminstrationMVC.PL` → Presentation Layer (Controllers, Views)
- `CompanyAminstrationMVC.BLL` → Business Logic Layer (Interfaces, Services)
- `CompanyAminstrationMVC.DAL` → Data Access Layer (DbContext, Models, Repositories)

---

## 🛠️ Technologies Used

- ASP.NET Core MVC (.NET 8)
- Entity Framework Core
- SQL Server
- Identity for Authentication & Authorization
- Bootstrap 
- LINQ 

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Omar-Ahm-ed/CompanyAminstrationMVC.git

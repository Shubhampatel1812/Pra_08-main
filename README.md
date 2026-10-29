# .NET Practical 8 – Product Management System

A web application developed using **ASP.NET MVC, C#, and Razor Views** as part of .NET Practical 8. The project follows the Model–View–Controller (MVC) architecture and includes a Products section with views for creating, viewing, editing, and deleting product records.

## 📌 Project Overview

The project demonstrates the structure and implementation of an ASP.NET MVC web application. It separates application logic, data models, and user interface components into different folders, making the code easier to organize and maintain.

## ✨ Features

- **Product Listing:** Display product records.
- **Create Product:** Provide a page to add a product.
- **Edit Product:** Provide a page to modify product details.
- **Delete Product:** Provide a page for deleting a product.
- **MVC Architecture:** Separate models, controllers, and views.
- **Razor Views:** Use `.cshtml` files to build dynamic web pages.

*Note: The listed features are based on the visible project structure; actual functionality depends on the implemented code.*

## 🛠️ Technologies Used

- **Language:** C#
- **Framework:** ASP.NET MVC
- **Frontend:** HTML, CSS, JavaScript
- **View Engine:** Razor
- **IDE:** Visual Studio
- **Configuration:** Web.config and packages.config

## 📂 Project Structure

```text
.NET_PRACTICAL_8/
├── packages/
└── Pr_8/
    ├── App_Start/
    ├── Content/
    ├── Controllers/
    ├── Models/
    ├── Properties/
    ├── Scripts/
    ├── Views/
    │   ├── Products/
    │   │   ├── create.cshtml
    │   │   ├── edit.cshtml
    │   │   ├── delete.cshtml
    │   │   └── index.cshtml
    │   ├── _ViewStart.cshtml
    │   └── Web.config
    ├── Global.asax
    ├── Global.asax.cs
    ├── Web.config
    ├── Web.Debug.config
    ├── Web.Release.config
    ├── packages.config
    ├── Pr_8.csproj
    └── Pr_8.sln
```

## ⚙️ Installation and Setup

### Prerequisites

- Windows operating system
- Visual Studio with ASP.NET and web development support
- The .NET Framework version required by the project

### Steps to Run the Project

1. **Clone the repository**

   ```bash
   git clone YOUR_GITHUB_REPOSITORY_URL
   ```

2. **Open the project**

   Open Visual Studio and select `Pr_8.sln`.

3. **Restore NuGet packages**

   Right-click the solution in Solution Explorer and select **Restore NuGet Packages**.

4. **Build the project**

   Select **Build → Build Solution** or press `Ctrl + Shift + B`.

5. **Run the application**

   Press `F5` to run with debugging or `Ctrl + F5` to run without debugging.

6. **Open the Products section**

   Navigate to the Products page using the application's configured routes.

## 📖 Learning Objectives

- Understand the fundamentals of ASP.NET MVC.
- Learn how Models, Views, and Controllers work together.
- Create Razor `.cshtml` pages.
- Organize a web application using the MVC folder structure.
- Practice basic product management operations.

## 🎓 Academic Information

- **Practical:** 8
- **Subject:** .NET Programming
- **Project Name:** Pr_8
- **Application Type:** ASP.NET MVC Web Application

## 👨‍💻 Author

**Student Project – .NET Practical 8**

---

*This project is intended for educational purposes and practical learning in ASP.NET MVC development.*

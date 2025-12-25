# 🍔 CraveHub - Food Delivery Management System

<div align="center">

![Logo](https://conservative-tomato-x2brtwp1ot-yqs6hbw4bj.edgeone.dev/Screenshot%202025-12-24%20204418.png)

> **"Your favorite food, delivered fresh—because great taste enhances every moment."**

</div>

---

**CraveHub** is a robust, full-stack web application designed to streamline the food ordering and delivery process. Built with **Spring Boot** and **Thymeleaf**, it provides a seamless experience for customers to order food and a powerful dashboard for administrators to manage products and users.

---

## 🚀 Features

### 👤 User Module
* **User Authentication:** Secure Login and Registration functionality.
* **Interactive Menu:** Browse food items by categories (Biryani, Chinese, North Indian, etc.).
* **Smart Search:** Search functionality to find specific dishes quickly.
* **Cart Management:** Add items to the cart and review the total bill.
* **Order Placement:** Seamless checkout process with payment simulation (`Payment.html`).
* **Order Tracking:** "Locate Us" feature with map integration.
* **Responsive Design:** Fully responsive UI for Mobile and Desktop.

### 🛠 Admin Module
* **Dashboard:** Specialized Admin Dashboard (`Admin_Page.html`).
* **Product Management:** Add, Update, and Delete food items dynamically.
* **User Management:** Admins can manage other admins and users.
* **Secure Access:** Role-based access control to protect administrative routes.

---

## 💻 Tech Stack

| Component | Technology |
| :--- | :--- |
| **Backend** | Java, Spring Boot (MVC, JPA, Web) |
| **Frontend** | HTML5, CSS3, JavaScript, Thymeleaf (Template Engine) |
| **Database** | MySQL (Relational Database) |
| **Build Tool** | Maven |
| **IDE** | Eclipse / IntelliJ IDEA / VS Code |

---

## 📂 Project Structure

```bash
CraveHub
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com.example.demo
│   │   │       ├── controllers      # Handles routing (Admin, User, Product, Home)
│   │   │       ├── entities         # Database Models (User, Product, Orders, Admin)
│   │   │       ├── repositories     # JPA Interfaces for DB operations
│   │   │       ├── services         # Business Logic
│   │   │       └── loginCredentials # Auth Logic
│   │   └── resources
│   │       ├── static               # CSS, JS, and Images
│   │       ├── templates            # HTML Views (Home, Login, Admin, etc.)
│   │       └── application.properties # Database Configuration
├── pom.xml                          # Maven Dependencies
└── README.md                        # Project Documentation
```

### ⚙️ Installation & Setup
Follow these steps to run the project locally:
## 1. PrerequisitesJava Development Kit (JDK):
Version 17 or higher.Maven: For building the project.MySQL Server: Ensure it is installed and running.

## 2. Database ConfigurationOpen MySQL Workbench or Command Line and create a database: 
 				CREATE DATABASE CraveHub;
 
Note: Check src/main/resources/application.properties to ensure the database name matches (cravehub) and update your MySQL username and password.

## 3. Clone & BuildBash# Clone the repository
git clone (https://github.com/tiwariGagans/CraveHub.git)

# Navigate to directory
    cd CraveHub

# Build the project
    mvn clean install

##4. Run the ApplicationYou can run it via your IDE (Right-click CraveHubApplication.java -> Run) or terminal:

        mvn spring-boot:run

## 5. Access the AppOpen your browser and go to:http://localhost:8080/

# 📸 Screenshots
![Admin](https://conservative-tomato-x2brtwp1ot-yqs6hbw4bj.edgeone.dev/Screenshot%202025-12-24%20204506.png)

---
![Admin](https://conservative-tomato-x2brtwp1ot-yqs6hbw4bj.edgeone.dev/Screenshot%202025-12-24%20204536.png)

---
![Admin](https://conservative-tomato-x2brtwp1ot-yqs6hbw4bj.edgeone.dev/Screenshot%202025-12-24%20204554.png)

---
![Admin](https://conservative-tomato-x2brtwp1ot-yqs6hbw4bj.edgeone.dev/Screenshot%202025-12-24%20204626.png)

---
![Admin](https://conservative-tomato-x2brtwp1ot-yqs6hbw4bj.edgeone.dev/Screenshot%202025-12-24%20204656.png)

---
![Admin](https://conservative-tomato-x2brtwp1ot-yqs6hbw4bj.edgeone.dev/Screenshot%202025-12-24%20204731.png)

---
![Admin](https://conservative-tomato-x2brtwp1ot-yqs6hbw4bj.edgeone.dev/Screenshot%202025-12-24%20204837.png)

---
![Admin](https://conservative-tomato-x2brtwp1ot-yqs6hbw4bj.edgeone.dev/Screenshot%202025-12-24%20204905.png)

---			

## 📧 ContactDeveloper: 
```bash
    [GAGAN TIWARI and PRIYANSHU KUMAR]
    Email: tgagan368@gmail.com
```
Project Link: https://github.com/your-username/

CraveHub© 2025 CraveHub. All Rights Reserved❤️.


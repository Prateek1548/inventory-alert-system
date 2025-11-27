# 📦 Inventory Alert System API

A backend **RESTful API** built for **Mechanical Engineering Inventory Management**.  
It manages product stock levels, supplier records, purchase orders, and generates **automatic low-stock alerts**.  
Includes **JWT authentication**, **role-based access**, detailed reports, and clean modular architecture.

---

## 🚀 Features

### 🔐 Authentication & Security
- User Registration & Login  
- JWT-based Authentication  
- Role-based Access Control (Admin/User)  
- Password hashing using bcrypt  
- Fully protected API routes  

### 📦 Inventory Management
- CRUD for **Products**, **Suppliers**, and **Purchase Orders**  
- Automatic stock updates when purchase orders are marked *completed*  
- Alerts when product quantity drops below **reorder threshold**  
- Stock status & shortage reports  

### ⚙️ Developer-Friendly Features
- Centralized error handling  
- Input validation  
- Well-structured modular architecture  
- Test cases using Jest + Supertest  
- Optional Docker support  

---

## 🛠 Tech Stack

| Component | Technology |
|----------|------------|
| Runtime | Node.js |
| Framework | Express.js |
| Database | MongoDB + Mongoose |
| Authentication | JWT & bcrypt |
| Testing | Jest & Supertest |
| Deployment | Docker (Optional) |

---

## 📋 Requirements

Make sure the following are installed:

- Node.js **v18+**
- npm **v9+**
- MongoDB (local or Atlas)
- Docker (optional)

---

## 🔧 Installation Guide

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/inventory-alert-system.git
cd inventory-alert-system

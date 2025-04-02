# 📦 inventory-web-aws

A scalable, full-featured inventory management backend built with **Node.js**, **Express**, and **Prisma ORM**. Designed for easy deployment on AWS, this server provides powerful endpoints for managing products, users, sales, purchases, and expense data — ideal for inventory dashboards and business insights.

---


## 🛠 Tech Stack

- ⚙️ Node.js + Express
- 🔗 RESTful API
- 🔎 Prisma ORM with PostgreSQL (or MySQL)
- 📊 Dashboard Metrics
- 🔐 CORS, Helmet, Body Parser
- 🧪 Seed script for sample data
- 🚀 Deployable to AWS / Docker-compatible

---
## 🚀 Features

### 📊 Dashboard API
- Popular products (by stock)
- Latest sales, purchases, and expenses
- Expense summary by category

### 🧾 Product Management
- Search products by name
- Add new products

### 👤 User Management
- Fetch all registered users

### 💸 Expense Tracking
- Get all categorized expense entries

---

## 🧪 Available Endpoints

| Method | Endpoint                  | Description                          |
|--------|---------------------------|--------------------------------------|
| GET    | `/dashboard`              | Returns dashboard metrics            |
| GET    | `/products?search=`       | Get all or filtered products         |
| POST   | `/products`               | Create a new product                 |
| GET    | `/users`                  | List all users                       |
| GET    | `/expenses`               | Get all categorized expenses         |

---

## 🔐 Security Middleware

helmet for setting secure HTTP headers

cors for handling cross-origin requests

body-parser for JSON and URL-encoded body parsing

morgan for logging requests




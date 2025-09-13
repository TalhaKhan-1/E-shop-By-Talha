# 🛒 E-Commerce Web Application (JSP + Servlet + MySQL)

This is a simple *E-Commerce web application* built using *Java (JSP/Servlets), **MySQL, and **Tomcat*.  
It allows users to register, login, browse products, add to cart, place orders, and view their order history.  
Admins can manage products, users, and orders from an admin dashboard.

---

## 🚀 Features

### 👤 User
- Register and Login
- Browse Products by category
- Add / Remove / Update Cart Items
- Checkout and Place Orders
- View Order History
- Logout

### 🛠 Admin
- Dashboard with statistics
- Manage Products (Add, Delete)
- Manage Users (Delete)
- Manage Orders (Update status)

---

## 🛠 Tech Stack
- *Frontend:* JSP, JSTL, HTML, CSS (basic styling)
- *Backend:* Java Servlets
- *Database:* MySQL 8+
- *Server:* Apache Tomcat 8.5 / 9
- *IDE:* NetBeans / Eclipse

---

## 📂 Project Structure

Ecommerce/
│── src/java/
│ ├── DB/ # Database helper classes (UserDB, ProductDB, CartDB, OrderDB, DBconnection)
│ ├── model/ # POJOs (User, Product, Cart, CartItem, Order, OrderItem)
│ └── servlet/ # Servlets (ProductServlet, CartServlet, CheckoutServlet, OrderServlet, AdminServlet)
│ └── Auth/ # Auth Servlets (LoginServlet, RegisterServlet, LogoutServlet)
│
│── web/
│ ├── index.jsp # Home Page
│ ├── login.jsp # User Login
│ ├── register.jsp # User Registration
│ ├── products.jsp # Product Listing
│ ├── cart.jsp # Shopping Cart
│ ├── checkout.jsp # Checkout
│ ├── orders.jsp # My Orders
│ └── admin/ # Admin JSPs (dashboard.jsp, manageProducts.jsp, manageUsers.jsp, manageOrders.jsp)
│
└── pom.xml (if using Maven) / Project Properties (NetBeans)

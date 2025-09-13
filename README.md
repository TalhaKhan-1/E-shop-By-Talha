
# 🛒 E-Commerce Web Application (JSP + Servlet + MySQL)

This project is a lightweight **E-Commerce platform** developed using **Java technologies (JSP/Servlets)**, backed by **MySQL** and deployed on **Apache Tomcat**.  
It enables users to create accounts, explore products, manage their shopping cart, place orders, and track their purchases.  
Administrators have access to a control panel to oversee product listings, user accounts, and order statuses.

---

## 🚀 Key Functionalities

### 👤 User Module
- Account Registration and Authentication  
- Product Browsing by Category  
- Cart Management (Add, Edit, Remove Items)  
- Order Placement and Checkout  
- View Past Orders  
- Secure Logout

### 🛠 Admin Module
- Overview Dashboard with Key Metrics  
- Product Management (Add/Delete Products)  
- User Management (Remove Users)  
- Order Tracking and Status Updates

---

## 🧰 Technology Stack
- **Frontend:** JSP, JSTL, HTML, CSS (minimal styling)  
- **Backend:** Java Servlets  
- **Database:** MySQL 8+  
- **Server:** Apache Tomcat 8.5 / 9  
- **IDE:** NetBeans or Eclipse

---

## 📁 Project Layout

```
Ecommerce/
│── src/java/
│   ├── DB/           # Database access classes (UserDB, ProductDB, CartDB, OrderDB, DBconnection)
│   ├── model/        # Java Beans (User, Product, Cart, CartItem, Order, OrderItem)
│   ├── servlet/      # Core Servlets (ProductServlet, CartServlet, CheckoutServlet, OrderServlet, AdminServlet)
│   └── Auth/         # Authentication Servlets (LoginServlet, RegisterServlet, LogoutServlet)
│
│── web/
│   ├── index.jsp         # Landing Page
│   ├── login.jsp         # Login Interface
│   ├── register.jsp      # Sign-Up Page
│   ├── products.jsp      # Product Display
│   ├── cart.jsp          # Cart Overview
│   ├── checkout.jsp      # Finalize Purchase
│   ├── orders.jsp        # User Order History
│   └── admin/            # Admin Pages (dashboard.jsp, manageProducts.jsp, manageUsers.jsp, manageOrders.jsp)
│
└── pom.xml / Project Properties (NetBeans)

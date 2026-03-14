# Inventory Management System

A full-stack **Inventory Management System** built using the **MERN Stack (MongoDB, Express.js, React, Node.js)** with **Vite and Tailwind CSS** for a fast and responsive frontend.

The system helps organizations efficiently manage products, suppliers, categories, users, and orders through a centralized dashboard. It provides secure authentication, structured data management, and a modern admin interface for monitoring inventory operations.

---

## Features

### Authentication & Security
- Secure user authentication
- Protected routes
- Authentication state management using Context API
- Middleware-based backend authorization

### Dashboard
- Centralized admin dashboard
- Inventory summary and statistics
- Overview of orders, products, and users

### Product Management
- Add, update, delete, and view products
- Categorize products for better organization
- Inventory tracking

### Category Management
- Create and manage product categories
- Organize inventory systematically

### Supplier Management
- Add and manage suppliers
- Maintain supplier information

### Order Management
- Track inventory orders
- Manage order history and records

### User Management
- Manage system users
- User profile management

### Modern UI
- Responsive design
- Tailwind CSS styling
- Component-based React architecture

---

## Tech Stack

### Frontend
- React
- Vite
- Tailwind CSS
- React Router
- Context API

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication

### Tools
- ESLint
- PostCSS
- Git & GitHub

---

## Project Structure

```
inventory-management-system
│
├── frontend
│   ├── public
│   │   └── bg.jfif
│   │
│   ├── src
│   │   ├── components
│   │   │   ├── Categories.jsx
│   │   │   ├── EmployeeProducts.jsx
│   │   │   ├── Logout.jsx
│   │   │   ├── Orders.jsx
│   │   │   ├── Products.jsx
│   │   │   ├── Profile.jsx
│   │   │   ├── Sidebar.jsx
│   │   │   ├── Summary.jsx
│   │   │   ├── Suppliers.jsx
│   │   │   └── Users.jsx
│   │   │
│   │   ├── context
│   │   │   └── AuthContext.jsx
│   │   │
│   │   ├── pages
│   │   │   ├── Dashboard.jsx
│   │   │   └── Login.jsx
│   │   │
│   │   ├── utils
│   │   │   └── ProtectedRoute.jsx
│   │   │
│   │   ├── Root.jsx
│   │   ├── api.jsx
│   │   ├── App.jsx
│   │   ├── index.css
│   │   ├── main.jsx
│   │
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── eslint.config.js
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   └── vite.config.js
│
├── server
│   ├── controllers
│   │   ├── authController.js
│   │   ├── categoryController.js
│   │   ├── dashboardController.js
│   │   ├── orderController.js
│   │   ├── productController.js
│   │   ├── supplierController.js
│   │   └── userController.js
│   │
│   ├── db
│   │   └── connectToMongoDB.js
│   │
│   ├── middleware
│   │   └── authMiddleware.js
│   │
│   ├── models
│   │   ├── Category.js
│   │   ├── Order.js
│   │   ├── Product.js
│   │   ├── Supplier.js
│   │   └── User.js
│   │
│   ├── routes
│   │   ├── auth.js
│   │   ├── category.js
│   │   ├── dashboard.js
│   │   ├── order.js
│   │   ├── product.js
│   │   ├── supplier.js
│   │   └── user.js
│   │
│   ├── seed.js
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
├── .gitignore
└── README.md
```

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/inventory-management-system.git
```

```
cd inventory-management-system
```

---

## Backend Setup

```
cd server
npm install
```

Create a `.env` file inside the **server** directory:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run the backend server:

```
npm start
```

---

## Frontend Setup

```
cd frontend
npm install
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

---

## API Modules

The backend follows **MVC architecture** with separate routes, controllers, and models.

Main API modules include:

- Authentication
- Users
- Products
- Categories
- Suppliers
- Orders
- Dashboard Analytics

---

## Future Improvements

- Role-based access control
- Inventory low-stock alerts
- Data export and reports
- Advanced dashboard analytics
- Email notifications
- Docker deployment

---

## Author

**Ayush Singh**

Full Stack Developer | MERN Stack Developer

# E-commerce Website for Grocery Products -RBAC

## Project Overview

This project is a fully functional **e-commerce platform for grocery products**, featuring a user-friendly interface for customers and a robust admin dashboard for managing products, orders, and users. The platform enables seamless product browsing, cart management, secure payments, and efficient order handling.

---

## Features

### User Features
- **Product Browsing**:
  - View products with detailed descriptions, prices, and images.
  - Filter products by categories such as fruits, vegetables, dairy, etc.
  - Search functionality for quickly finding products by name.
- **Cart Management**:
  - Add, update, and remove items in the cart.
  - View a summary of the cart, including total price.
- **Order Placement**:
  - Proceed to checkout with shipping details.
  - Secure payment integration via **PayPal**.
- **User Dashboard**:
  - View order history with details such as product names, quantities, and status.
  - Update profile information.

### Admin Dashboard
- **Product Management**:
  - Add, edit, and delete products.
  - View all products in an organized table with options for filtering and sorting.
- **Order Management**:
  - View a list of all customer orders.
  - Update order statuses (e.g., Pending, Shipped, Delivered).
- **User Management**:
  - View a list of registered users.
  - Manage user accounts, including activation or deactivation.

### Common Features
- **Authentication**:
  - User and admin login with role-based access control (RBAC).
  - Secure password storage using bcrypt hashing.
- **Responsive Design**:
  - Fully responsive layout, ensuring compatibility across all devices.
- **Notifications**:
  - Alerts for successful actions like adding products, completing orders, etc.

---

## Technologies Used

### Frontend
- **React.js**:
  - Component-based UI development.
- **React Router**:
  - For navigation between pages.
- **Material UI**:
  - Pre-built components for styling and responsiveness.

### Backend
- **Node.js**:
  - JavaScript runtime for server-side logic.
- **Express.js**:
  - Web framework for handling routes and APIs.

### Database
- **MongoDB**:
  - Document-oriented NoSQL database for storing user, product, and order data.

### APIs
- **PayPal API**:
  - For secure online payments.

---

## Setup Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local instance or MongoDB Atlas)
- PayPal developer account for API integration

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Aravindh2003/GroTrix-Frontend.git
   cd GroTrix-Frontend


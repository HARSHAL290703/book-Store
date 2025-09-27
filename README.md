# 📚 Book Store Management App

The **Book Store Management App** is a full-stack MERN application designed to streamline book management, customer interactions, and order processing. It features secure role-based access for both administrators and customers, ensuring a seamless and efficient experience.

---

## 🚀 Features

* **Role-Based Access Control**

  * 👨‍💼 **Admins**: Manage books, update order statuses, oversee system
  * 👤 **Customers**: Browse, order, and favorite books
* **Admin Panel**

  * Add/Delete books from 
  * Update order statuses (*Ordered, Cancelled, etc.*) inventory and manage orders
* **Secure Authentication**

  * Login/Logout functionality for Admins and Customers
  * Role-specific dashboards
* **Customer Features**

  * Browse and search for books
  * Add to cart 
  * Favorite books for quick access

---

## 🛠️ Tech Stack

* **Frontend:** React.js, Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** JWT (JSON Web Token), bcrypt.js

---

## 📊 Workflow

1. User authentication (Admin/Customer)
2. Role-specific dashboards
3. Admin adds or removes books, manages order statuses
4. Customers browse, add to cart, order, and favorite books
5. Real-time updates ensure smooth order and inventory management

---

## 📌 How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/HARSHAL290703/book-Store.git
   ```
2. Navigate to the project folder:

   ```bash
   cd book-store-app
   ```
3. Install dependencies for both frontend and backend:

   ```bash
   npm install
   ```
4. Set up environment variables (`.env`):

   * MongoDB connection URI
   * JWT Secret Key
5. Run backend server:

   ```bash
   npm run server
   ```
6. Run frontend:

   ```bash
   npm start
   ```



---

---

# Supply Chain Management Platform

Welcome to our comprehensive *Supply Chain Management Platform! This platform is designed to simplify e-commerce interactions for customers, streamline operations for admins, and optimize logistics for truck drivers. Built using **Node.js, **React, **Flutter, and enhanced with tools like **Material UI, **Tailwind CSS, and **EmailJS*, our platform delivers a powerful and flexible system for managing orders, inventory, shipments, and employee progress.

## 🚀 Features

### 1. E-commerce Platform for Customers
   - *Product Browsing & Searching*: Customers can view, filter, and search for products by categories.
   - *Seamless Ordering Process*: Users can add items to their cart and proceed with a smooth checkout experience.
   - *Route Selection*: Suggested routes are provided to optimize delivery productivity.
   - *User-friendly Interface*: Built with React and styled with Material UI and Tailwind CSS for a clean, responsive design.
   - *EmailJS*: Connects the platform with customers and the company via email for notifications and updates.

### 2. Admin Panel for Store & Central Hub Managers
   - *Order Analysis*: View detailed metrics on orders, including sales volume, revenue, and inventory trends.
   - *Employee Progress Tracking*: Monitor and evaluate employee performance for both store and hub management.
   - *Dashboard Insights*: An intuitive dashboard with data visualization provides admins with real-time insights and strategic foresight into daily and monthly operations.
   - *Inventory Management*: Easily update inventory, track stock levels, and manage incoming/outgoing shipments.

### 3. Mobile App for Truck Drivers
   - *Shipment Assignment*: Drivers receive assigned shipments directly in their app, including trial assignments.
   - *Shipment Updates*: Real-time updates on shipment status.

## 🛠 Technologies

### Backend
- *Node.js & Express*: Manages data processing, order handling, and inventory management for smooth performance.
- *Database*: Our backend supports SQL/NoSQL databases to ensure scalable and secure data management.

### Frontend
- *React*: User interface for customers and admin dashboard, providing a seamless and interactive experience.
- *Material UI* & *Tailwind CSS*: Streamlines the design with responsive components and elegant styles.

### Mobile App
- *Flutter*: Cross-platform app for truck drivers, designed for both iOS and Android.

### Additional Libraries & Tools
- *Axios*: For efficient API communication.
- *Redux*: State management across complex UI components.
- *React Router*: Enables smooth navigation throughout the platform.
- *EmailJS*: Used for automated emails, providing real-time order confirmation, shipment updates, and notifications.

## 📦 Installation

To set up the Supply Chain Management Platform locally, follow these steps:

1. *Database Setup*:
   - Go to SCMS-API/utilities/database/definition_files.
   - Run all of the .ddl files in the specified order to set up the database schema.

2. *Backend Setup*:
   - Navigate to SCMS-API/.
   - Run npm install to install the necessary backend dependencies.
   - Run npm run initialise-database to populate the database with initial data.
   - Start the backend server:
     bash
     npm start
     
   - Start the truck scheduler daemon:
     bash
     npm run truck-scheduler
     

3. *Frontend Setup*:
   - *Customer UI*:
     - Navigate to E-Commerce-platform.
     - Run:
       bash
       npm install
       npm start
       
   - *Admin UI*:
     - Navigate to Admin Dashboard.
     - Run:
       bash
       npm install
       npm start
       

4. *Login Credentials*:
   - Usernames can be found in the *Employee* and *Customer* tables.
   - Default passwords are:
     - *Employee - Driver*: Password@Driver
     - *Admin*: Password@Admin
     - *Store Manager*: Password@StoreManager
     - *Customer*: Password@Customer

5. *Simulate Orders* (Optional):
   - To simulate orders, navigate to SCMS-API/ and run:
     bash
     npm run simulate-orders

6. .env format for SCMS-API

    MYSQL_HOST=
    MYSQL_USER=
    MYSQL_PASSWORD=
    MYSQL_DATABASE=scms
    PORT=
    HASH_COUNT=10
    JWT_SECRET=
     

---

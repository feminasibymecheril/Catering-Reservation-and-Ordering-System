# Catering-Reservation-and-Ordering-System

# 🍽️ Rural Roots Catering Platform

## 📌 Project Description
Rural Roots is a **web-based catering management system** that connects users with traditional rural food services.

It allows customers to browse menu items, place orders, and track order status, while admins can manage menu items and monitor orders.

This project simulates a **real-world food ordering system** using frontend technologies and local storage.

---

## 🚀 Features

### 👤 User Features
- Register and login system
- Browse catering menu
- Add items to cart
- Place orders
- View order history
- Track order status

### 🛠️ Admin Features
- Add new menu items
- View all products
- Manage customer orders
- Update order status:
  - Pending
  - Preparing
  - Completed
  - Cancelled

### 🛒 Cart System
- Add/remove items
- Calculate total price
- Dynamic cart updates

### 🔐 Authentication System
- Role-based login:
  - Customer
  - Admin
- Session stored using LocalStorage

### 💾 Data Persistence
- Uses LocalStorage as a database
- Stores:
  - Users
  - Products
  - Orders

### 🎨 UI/UX
- Clean modern UI
- Responsive layout
- Smooth animations
- Toast notifications

---

## 🛠️ Technologies Used
- **HTML5**
- **CSS3 (Flexbox + Grid + Animations)**
- **JavaScript (Vanilla JS)**
- **Local Storage API**

---

## 📂 Project Structure



---

## ▶️ How to Run
1. Download or clone the repository  
2. Open `index.html` in your browser  

---

## 🧠 Core Functionalities

### Authentication
- `handleRegister()` → Register users  
- `handleLogin()` → Login users  
- `logout()` → End session  

### Product Management
- `handleAddProduct()` → Add menu items  
- `renderAdminProducts()` → Display products  

### Orders
- `renderUserOrders()` → Show user orders  
- `renderAdminOrders()` → Show all orders  
- Status update system  

### Cart
- Add to cart  
- Remove items  
- Checkout system  

---

## 📱 Responsive Design
- Works on mobile, tablet, and desktop  
- Flexible grid layout  

---

## 🔮 Future Improvements
- Backend integration (Node.js + Database)
- Payment gateway integration
- Real-time order tracking
- Notifications system
- Image upload for food items

---

## 🙋‍♀️ Author
**Femina Siby Mecheril**

---

## ⭐ Highlights
- Role-based system (Admin & User)
- Full application flow (login → order → manage)
- LocalStorage as database simulation
- Real-world use case project

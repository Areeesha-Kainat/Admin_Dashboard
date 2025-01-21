# Rental E-Commerce Car Renting Website Admin Dashboard 🚗

Welcome to the **Rental E-Commerce Car Renting Website Admin Dashboard**! This project is a fully functional web application designed to provide users with a seamless experience for renting cars online. Built with **Next.js**, **Tailwind CSS**, and **TypeScript**, this website is modern, responsive, and easy to use. The **Admin Dashboard** empowers administrators to manage cars, bookings, users, and promotions efficiently, while the **User Dashboard** allows customers to browse, book, and review cars.


## 🌟 **Live Demo**
Check out the live version of the website deployed on Vercel:  
👉 [Rental E-Commerce Car Renting Website](https://rentalcarecommerce.vercel.app)  
👉 [Admin Dashboard](https://rentalcarecommerce.vercel.app/AdminDashboard)


## 🚀 **Key Features**
Here are the main functionalities and features of the website:

### **1. User-Friendly Interface**
- Clean and intuitive design for easy navigation.
- Responsive layout for seamless use on all devices (desktop, tablet, mobile).

### **2. Authentication System**
- **Signup:** Users can create an account by providing their email and password.
- **Signin:** Users and admins can log in to access their respective dashboards.
  - Admins can log in directly using predefined credentials (`areesha@gmail.com` and `12345678`).
  - Users must sign up first before they can log in.

### **3. Admin Dashboard**
- **Cars Management:** Add, edit, or remove cars.
- **Bookings Management:** View and manage all bookings.
- **Users Management:** View and manage user accounts.
- **Promotions Management:** Create and manage promotions (e.g., discounts, coupons).

### **4. User Dashboard**
- **Car Listings:** Browse and filter cars by type, capacity, and price.
- **Booking System:** Book a car for a specific duration.
- **Wishlist:** Save favorite cars for easy access later.
- **Reviews and Ratings:** Leave feedback for rented cars.

### **5. Secure Authentication**
- Passwords are stored securely in **localStorage** for this example.
- Admins can log in directly without needing to sign up.


## 🛠️ **Technologies Used**
- **Frontend:**
  - Next.js (React framework for server-side rendering).
  - Tailwind CSS (utility-first CSS framework).
  - TypeScript (for type-safe JavaScript).
- **Deployment:**
  - Vercel (for hosting and continuous deployment).


## 🚗 **Functionality Breakdown**
Here’s a detailed breakdown of the website’s functionality:

### **1. Signup Page**
- Users can create an account by providing their email and password.
- Passwords are validated to ensure they match.
- User credentials are stored in **localStorage**.

### **2. Signin Page**
- **Admins:** Can log in directly using predefined credentials
- **Users:** Must sign up first before they can log in.
- Redirects to the appropriate dashboard based on user role:
  - Admins are redirected to the **AdminDashboard**.
  - Users are redirected to the **UserDashboard**.

### **3. Admin Dashboard**
- **Cars Management:** Add, edit, or remove cars.
- **Bookings Management:** View and manage all bookings.
- **Users Management:** View and manage user accounts.
- **Promotions Management:** Create and manage promotions.

### **4. User Dashboard**
- **Car Listings:** Browse and filter cars by type, capacity, and price.
- **Booking System:** Book a car for a specific duration.
- **Wishlist:** Save favorite cars for easy access later.
- **Reviews and Ratings:** Leave feedback for rented cars.

# Online Bus Booking System

A backend-driven platform for seamless bus ticket booking, real-time availability tracking, route management, and secure user interaction.

---

## 📌 Project Overview

The *Online Bus Booking System* is a backend-focused application designed to manage the core functionalities of a modern bus reservation platform. It supports *seat booking, **route and schedule management, **user authentication, and **payment processing, all integrated with a **real-time database*.

---

## ✅ Key Features

•⁠  ⁠🪑 *Seat Booking System*  
  Allows users to view and reserve available seats on desired routes.

•⁠  ⁠🛣️ *Route & Schedule Management*  
  Admins can create, update, and manage routes, stops, timings, and pricing.

•⁠  ⁠🔒 *User Authentication*  
  Secure login and signup features with password hashing and JWT sessions.

•⁠  ⁠💳 *Payment Integration*  
  Dummy payment processing (Stripe/PayPal-ready structure for expansion).

•⁠  ⁠🗃️ *Database-Driven Scheduling*  
  Dynamically fetches and updates routes, availability, and user bookings.

•⁠  ⁠📆 *Real-Time Availability Check*  
  Users can view up-to-date seat availability for every route and time.

---

## 🛠️ Tech Stack

### 🔹 Backend
•⁠  ⁠Python with Flask / FastAPI
•⁠  ⁠SQLAlchemy for ORM
•⁠  ⁠SQLite / MySQL Database
•⁠  ⁠JWT for Authentication
•⁠  ⁠Bcrypt for Password Hashing

### 🔹 Tools & Services
•⁠  ⁠Postman (API testing)
•⁠  ⁠Stripe/PayPal mock (for future payment gateway support)

---

## Sample Outputs
![Bus 1](https://raw.githubusercontent.com/Bhavanaviswanath/Online-Bus-Booking-System/6ce6e7875bf3e8d23d2d69f3d85538eff8f26e41/bus1.png)

![Bus 2](https://raw.githubusercontent.com/Bhavanaviswanath/Online-Bus-Booking-System/6ce6e7875bf3e8d23d2d69f3d85538eff8f26e41/bus2.png)

![Bus 3](https://raw.githubusercontent.com/Bhavanaviswanath/Online-Bus-Booking-System/6ce6e7875bf3e8d23d2d69f3d85538eff8f26e41/bus3.png)

![Bus 4](https://raw.githubusercontent.com/Bhavanaviswanath/Online-Bus-Booking-System/6ce6e7875bf3e8d23d2d69f3d85538eff8f26e41/bus4.png)

![Bus 5](https://raw.githubusercontent.com/Bhavanaviswanath/Online-Bus-Booking-System/6ce6e7875bf3e8d23d2d69f3d85538eff8f26e41/bus5.png)


## 🚀 Setup Instructions

### ✅ Prerequisites
•⁠  ⁠Python 3.8+
•⁠  ⁠VS Code
•⁠  ⁠Postman for testing (optional)

---

### 🔧 Backend Setup
cd backend

python -m venv venv

source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

uvicorn main:app --reload  # For FastAPI
# or
python main.py  # For Flask

## 📚 How It Works
User Registration & Login

Secure account creation and session handling via JWT.

Route Management

Admins can manage routes, buses, stops, and schedules.

Booking Process

User selects route → views seat availability → books ticket.

Payment Module

Payment interface (mock/dummy structure with future gateway integration).

Real-Time Updates

##   Seat availability and schedules update after each booking.API Testing
Use Postman or Swagger UI to test endpoints:

/auth/register – Signup

/auth/login – Login

/routes/ – List all routes

/bookings/ – View/Create bookings

/payments/ – Payment handling

## 👩‍💻 Author
Natuva Bhavana
📧 Email: natuvabhavana@gmail.com

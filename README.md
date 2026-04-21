# 🚗 Parking Management System

A full-stack web application designed to efficiently manage parking slots, vehicle entry/exit, and billing. This system helps reduce congestion, optimize parking space utilization, and provide a seamless user experience.

---

## 🌍 SDG Alignment

This project aligns with:

* **SDG 11: Sustainable Cities and Communities**
* **SDG 9: Industry, Innovation and Infrastructure**
* **SDG 13: Climate Action**

---

## 📌 Application Domain

Smart Transportation and Urban Mobility Systems (Smart City Solutions)

---

## 🛠️ Tech Stack

### Frontend:

* React.js (Vite)
* Axios
* HTML, CSS, JavaScript

### Backend:

* Java
* Spring Boot
* Spring Security
* JWT Authentication

### Database:

* MySQL

### Tools:

* Maven
* Git & GitHub
* Postman

---

## ✨ Features

* 🔐 User Authentication (JWT-based Login/Register)
* 🅿️ Parking Slot Management (CRUD operations)
* 🚘 Slot Booking System
* ⏱ Entry and Exit Time Tracking
* 💰 Time-based Billing System
* 📊 Dashboard with Slot Availability
* 🧾 Booking History

---

## 📂 Project Structure

```
parking-management-system/
│
├── backend/        # Spring Boot Application
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── model/
│   └── security/
│
├── frontend/       # React Application
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.jsx
```

---

## ⚙️ Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/shrutijadhav2809/parking-management-system.git
cd parking-management-system
```

---

### 2. Setup Database

```sql
CREATE DATABASE parking_db;
```

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/parking_db
spring.datasource.username=root
spring.datasource.password=root
spring.jpa.hibernate.ddl-auto=update
```

---

### 3. Run Backend

```bash
cd backend
mvn spring-boot:run
```

---

### 4. Run Frontend

```bash
cd frontend
npm install
npm run dev
```

---

### 5. Access Application

Frontend:

```
http://localhost:5174
```

Backend:

```
http://localhost:8080
```

---

## 🔗 API Endpoints

### Authentication

* POST `/api/auth/register`
* POST `/api/auth/login`

### Slots

* GET `/api/slots`
* POST `/api/slots`
* PUT `/api/slots/{id}`
* DELETE `/api/slots/{id}`

### Bookings

* POST `/api/bookings`
* GET `/api/bookings`
* POST `/api/bookings/exit/{id}`

---

## 🚀 Future Enhancements

* Real-time slot updates
* Online payment integration
* Mobile app support
* Advanced analytics dashboard

---

## 👩‍💻 Author

Shruti Jadhav

---

## 📄 License

This project is for educational purposes only.

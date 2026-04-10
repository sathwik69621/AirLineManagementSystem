# ✈️ Airline Management System (Java)

## 📌 Overview

The **Airline Management System** is a Java-based backend application designed to manage airline operations such as flight scheduling, passenger reservations, ticket booking, and administrative control.
It demonstrates core concepts of **object-oriented programming, database integration, and modular system design**.

---

## 🚀 Features

### 👨‍💼 Admin Module

* Add / update / delete flight details
* Manage airline schedules
* View all bookings and passenger data

### 🧑‍✈️ User Module

* Search available flights
* Book tickets
* Cancel reservations
* View booking history

### 📊 System Features

* Real-time seat availability tracking
* Unique booking ID generation
* Input validation and error handling
* Database-driven architecture

---

## 🛠️ Tech Stack

* **Language:** Java (JDK 8+)
* **Database:** MySQL
* **Connectivity:** JDBC
* **IDE:** IntelliJ IDEA / Eclipse
* **Build Tool:** (Optional) Maven

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/sathwik69621/AirLineManagementSystem.git
cd AirLineManagementSystem
```

### 2️⃣ Setup Database

* Install MySQL
* Create a database:

```sql
CREATE DATABASE airline_db;
```

* Import `schema.sql`

### 3️⃣ Configure Database Connection

Update credentials in:

```
util/DBConnection.java
```

```java
String url = "jdbc:mysql://localhost:3306/airline_db";
String user = "root";
String password = "your_password";
```

### 4️⃣ Run the Application

* Open project in IDE
* Run `Main.java`

---

## 🧪 Sample Functional Flow

1. Admin adds flight details
2. User searches for flights
3. User books ticket
4. System generates booking ID
5. User can cancel or view booking

---

## 📸 Screenshots (Optional)

*Add screenshots of UI or console output here*

---

## 🔐 Future Enhancements

* Web-based UI using Spring Boot
* Authentication & authorization (JWT)
* Payment gateway integration
* REST API development
* Docker deployment

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit pull requests.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👤 Author

**Sathwik**
Aspiring Backend Developer

---

# XarxaLlibres Lite 📚

![Status](https://img.shields.io/badge/status-in%20development-yellow)
![Java](https://img.shields.io/badge/Java-17-blue)
![Kotlin](https://img.shields.io/badge/Kotlin-1.9-blueviolet)
![Android](https://img.shields.io/badge/Android-Jetpack%20Compose-brightgreen)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue)
![Architecture](https://img.shields.io/badge/Architecture-Client--Server-informational)

Intermodular project developed within the  
**Higher Vocational Training Degree in Multiplatform Application Development (DAM)**.

---

## 📌 Project Overview

**XarxaLlibres Lite** is a multiplatform application designed to facilitate the
management and consultation of textbooks within an educational community.

The system allows users to authenticate, browse a book catalog, add new book entries,
and view detailed information for each item.  
The project follows a **client–server architecture** and is structured into
independent modules to ensure scalability and maintainability.

---

## 🧩 System Architecture

The project is divided into the following components:

- **Database (PostgreSQL)**  
  Data model design and database management.

- **Mobile Application (Android)**  
  Developed in **Kotlin** using **Jetpack Compose**.

- **Desktop Application (Java)**  
  Desktop client acting as an administrative tool for managing the application database.

The database is deployed in the cloud using **Firestore Database**.

---

## 👥 Development Team

This project is developed by a **3-member team**, with clearly defined responsibilities:

- **Gema** → Database design and management (PostgreSQL, SQL scripts)
- **Santiago** → Desktop application (Java + JavaFX)
- **Eneko** → Android mobile application (Kotlin + Jetpack Compose)

---

## 📱 Mobile Application (Android)

### Technologies
- **Language:** Kotlin  
- **UI Framework:** Jetpack Compose  
- **Architecture:** MVVM  
- **Navigation:** Navigation Compose  
- **State Management:** `State`, `remember`, `mutableStateOf`

---

## 🗄️ Database

- **DBMS:** PostgreSQL  
- **Normalized relational design**  
- **Cloud-hosted** (free-tier service)

---

## 📄 License

This project has been developed for **educational purposes** as part of the  
**Intermodular Project** of the DAM

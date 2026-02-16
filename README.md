# 🐾 PlayFetch

PlayFetch is a full-stack dog playdate scheduling platform that enables owners to discover compatible dogs, filter by personality and location, and manage structured play sessions through a unified dashboard.

The system is designed around behavioral compatibility, location-aware discovery, and structured scheduling to support safe, real-world social interactions.

---

## 📸 Screenshots

* Home
* Search & Filter
* Playdate Dashboard
* Mobile View

---

## ✨ Features

* Secure user registration and authentication
* Dog profile creation with breed, age, and behavioral attributes
* Personality and play-style based compatibility filtering
* Location-based discovery of nearby playdates
* Advanced search filtering by personality and geographic region
* Structured scheduling and management of play sessions
* Playdate status tracking (pending, confirmed, canceled)
* Responsive design optimized for desktop and mobile devices

---

## 🛠 Tech Stack

| Layer    | Technology       | Responsibility                              |
| -------- | ---------------- | ------------------------------------------- |
| Frontend | React            | Component-based UI architecture             |
| Frontend | HTML5            | Semantic structure                          |
| Frontend | CSS3             | Responsive layout and visual styling        |
| Frontend | JavaScript (ES6) | Client-side logic and state management      |
| Backend  | Java             | Core domain and business logic              |
| Backend  | Spring Boot      | REST API, routing, and server configuration |
| Database | PostgreSQL       | Relational data persistence                 |
| Tooling  | Git & GitHub     | Version control and project management      |

---

## 🏗 Architecture

PlayFetch follows a layered full-stack architecture:

* React frontend consuming RESTful APIs
* Spring Boot backend handling business rules and validation
* PostgreSQL for structured relational data storage
* Clear separation between presentation, service, and data layers

The system emphasizes maintainability, modular design, and clean separation of concerns.

---

## 🚀 Running the Application

```bash
git remote add origin https://github.com/IbrahimQaar/PlayFetch.git
```

### Frontend

```bash
cd frontend
npm install
npm start
```

### Backend

```bash
cd backend
./mvnw spring-boot:run
```

Configure PostgreSQL credentials in `application.properties` before starting the backend.

---

## 👨‍💻 Author

**Ibrahim Qaar**
Full-Stack Java & React Developer

-

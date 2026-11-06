# 🍽️ Restaurant Explorer
### Discover Restaurants. Explore Food. Find Your Way.

**Restaurant Explorer** is a full-stack mobile application designed to make restaurant discovery easier and more convenient. It allows users to explore restaurants, search for food products, discover places that serve their preferred items, and navigate to restaurant locations through interactive Google Maps integration.

The application consists of a **Flutter mobile frontend** and a **Spring Boot backend**, communicating through RESTful APIs to provide a seamless user experience.

---

## ✨ Key Features

### 🔐 Authentication & User Management
- User authentication with input validation.
- Form validation to ensure accurate user input.
- Integration with backend authentication APIs.

### 🔎 Smart Food Search
- Search for food products.
- Retrieve available products and restaurants through backend APIs.
- Discover restaurants based on selected food products.
- Display relevant search results dynamically.

### 🍴 Restaurant Discovery
- Browse restaurants and their available information.
- Explore restaurants serving specific food products.
- Retrieve and display restaurant data from the Spring Boot backend.

### 📍 Maps & Navigation
- Integrated Google Maps for interactive location visualization.
- Display restaurant locations on the map.
- Calculate the distance between the user and selected restaurants.
- Get directions and navigate to restaurants using Google Maps.

### ⚡ Reactive State Management
- Manage asynchronous operations using RxDart.
- Handle API responses and application state reactively.
- Provide dynamic UI updates based on application data.

---

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Mobile Development | Flutter, Dart |
| Backend Development | Java, Spring Boot |
| API Communication | RESTful APIs |
| Reactive Programming | RxDart |
| Maps & Location | Google Maps API |
| Build & Dependency Management | Maven |
| Version Control | Git & GitHub |

---

## 🏗️ Project Architecture

The project follows a separated frontend/backend architecture, where the Flutter application communicates with the Spring Boot backend through RESTful APIs.

```text
Restaurant-Explorer/
│
├── backend/
│   └── Spring Boot Application
│       ├── src/
│       ├── .mvn/
│       ├── pom.xml
│       ├── mvnw
│       └── mvnw.cmd
│
├── frontend/
│   └── Flutter Application
│       ├── lib/
│       ├── android/
│       ├── ios/
│       ├── web/
│       ├── test/
│       └── pubspec.yaml
│
└── README.md
```

### How It Works

1. Users interact with the Flutter mobile application.
2. The frontend sends HTTP requests to the Spring Boot REST APIs.
3. The backend processes requests and retrieves the required data.
4. API responses are returned to the Flutter application.
5. RxDart manages asynchronous data streams and reactive state updates.
6. Google Maps provides location visualization, distance calculation, and navigation.

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

Make sure you have the following installed:

- Flutter SDK
- Dart SDK
- Java Development Kit (JDK)
- Maven (or use the included Maven Wrapper)
- Android Studio or Visual Studio Code
- Google Maps API Key

### 1. Clone the Repository

```bash
git clone https://github.com/yasmin401/Restaurant-Explorer.git
cd Restaurant-Explorer
```

### 2. Set Up the Backend

Navigate to the backend directory:

```bash
cd backend
```

Run the Spring Boot application:

**Windows:**
```bash
mvnw.cmd spring-boot:run
```

**Linux / macOS:**
```bash
./mvnw spring-boot:run
```

Make sure the required backend configuration and database settings are properly configured before running the application.

### 3. Set Up the Frontend

Navigate to the Flutter project:

```bash
cd frontend
```

Install the required dependencies:

```bash
flutter pub get
```

Configure your Google Maps API Key and backend API base URL.

Run the application:

```bash
flutter run
```

---

## 🔑 Configuration

Before running the application, make sure to configure:

- **Backend API URL:** Set the correct backend base URL in the Flutter application.
- **Google Maps API Key:** Configure the API key for the required Android, iOS, or other supported platforms.
- **Backend Environment:** Configure the required database connection and application properties.

Avoid committing private credentials, API secrets, or sensitive configuration values to the public repository.

---

## 🔮 Future Improvements

- Save and manage favorite restaurants.
- Add restaurant reviews and ratings.
- Enhance personalized restaurant recommendations.
- Improve search and filtering capabilities.
- Introduce offline-friendly features.

---

⭐ If you find this project interesting, feel free to explore the repository!

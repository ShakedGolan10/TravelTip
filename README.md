# 🚀 GIS-Based Travel Planner Application

## 🎯 Project Overview

The **GIS-Based Travel Planner** is a comprehensive, full-stack web application aimed at providing users with an intuitive, interactive map-driven interface for trip planning. It leverages advanced Geographic Information Systems (GIS) technology combined with modern web development techniques. Users can seamlessly discover, select, organize, and manage travel destinations through a visually engaging Kanban-style planning tool.

---

## 📌 Key Features

### 🌐 Frontend Features

- **Interactive Map Interface:**
  - Clickable map points providing detailed location information.
  - Seamless addition of locations directly from map pop-ups to Kanban boards.

- **Kanban Planner:**
  - Categorization of selected places: `Interested`, `Want to Visit`, `Scheduled`.
  - Drag-and-drop support to move locations between categories.

- **Search & Filtering:**
  - Real-time place search with instant filtering of map locations.
  - Dynamic search integration to quickly pinpoint attractions.

---

### 🛠️ Backend Features

- **GIS Data Management:**
  - Efficient retrieval and persistence of geographic data.
  - Advanced spatial queries for optimized location-based searches.

- **External APIs Integration:**
  - Robust integration with **OpenTripMap API** for detailed location data.
  - API key management, secure storage, and rate-limiting practices.

- **GraphQL API:**
  - Modern and efficient data fetching using GraphQL queries and mutations.

---

## ⚙️ Detailed Technology Stack

### 🖥️ Frontend Stack

- **Framework:**
  - **Angular 17**
    - Angular CDK (for Drag-and-Drop)
    - Angular Signals (for state management)
    - RxJS (for reactive programming)

- **Mapping:**
  - **MapLibre GL JS**
    - MapTiler OpenStreetMap tiles integration
    - Dynamic markers, pop-ups, and location clustering

- **GraphQL Client:**
  - **Apollo Client** (GraphQL state management and queries)

- **Styling & UI Components:**
  - SCSS (structured and modular styling)
  - Angular Material (responsive UI components: buttons, modals, cards, forms)

- **Dependency Management & Development Tools:**
  - npm (package management)
  - Angular CLI (application scaffolding and build)
  - VS Code IDE (development environment)

---

### 📡 Backend Stack (Java)

- **Framework:**
  - **Spring Boot 3** (rapid application development, simplified configuration)

- **GraphQL Server:**
  - **Spring GraphQL** (optimized queries and mutations handling)

- **HTTP Client:**
  - **Spring WebClient** (asynchronous calls to external APIs)

- **Spatial Data Management:**
  - **Hibernate Spatial** (spatial queries, geographic data persistence)
  - **PostGIS** (advanced GIS capabilities)

- **Database:**
  - **PostgreSQL** (relational database)
  - **PostGIS Extension** (enhanced GIS data support)

- **Security & Management:**
  - **Spring Security** (authentication, authorization - optional future expansion)
  - Secure management of sensitive data (API keys)

- **Dependency Management & Development Tools:**
  - Maven (dependency management)
  - IntelliJ IDEA / VS Code with Java plugins (development environment)
  - Docker (containerization, local database setup)

---

## 📁 Project Structure

### 🎨 Frontend (Angular)

```sh
src/
├── app/
│   ├── components/
│   │   ├── map/
│   │   ├── kanban/
│   │   └── search/
│   ├── services/
│   │   ├── places.service.ts
│   │   └── graphql.service.ts
│   ├── models/
│   │   └── place.model.ts
│   └── state/
│       └── places.store.ts
```

### 🔧 Backend (Spring Boot)

```sh
src/main/java/
├── com/example/tripplanner/
│   ├── controller/
│   │   └── GraphQLController.java
│   ├── service/
│   │   ├── PlaceService.java
│   │   └── ExternalApiService.java
│   ├── repository/
│   │   └── PlaceRepository.java
│   ├── model/
│   │   └── Place.java
│   ├── config/
│   │   └── GraphQLConfig.java
│   └── TripPlannerApplication.java
```

---

## 🌍 API & External Integrations

- **OpenTripMap API** (comprehensive place data)
- **MapTiler OpenStreetMap Tiles** (free map tiles for visual representation)

---

## 🚧 Development Workflow

- **Frontend:**
  - Development via Angular CLI and npm
  - Continuous testing and deployment pipelines (GitHub Actions)

- **Backend:**
  - Managed through Maven builds
  - Local database environment setup using Docker (PostgreSQL + PostGIS)
  - Potential CI/CD integrations with GitHub Actions or Jenkins

---

## 🚀 Deployment (Future Consideration)

- Cloud deployment strategies (AWS, Google Cloud, Azure)
- Docker-based container orchestration (Docker Compose, Kubernetes)

---

## 🛡️ Security Considerations

- Secure storage and rotation of API keys
- Future implementation of OAuth 2.0 or JWT-based authentication

---

## 📝 Documentation & Support

- Clear and comprehensive inline code documentation
- Readable API documentation (Swagger or GraphQL introspection)
- Continuous user feedback integration for feature improvement

---

🎉 **Happy coding!** 🎉


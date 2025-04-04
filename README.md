# 🚀 GIS-Based Travel Planner Application

## 🎯 Project Overview

The **GIS-Based Travel Planner** is a comprehensive, full-stack web application aimed at providing users with an intuitive, interactive map-driven interface for trip planning. It leverages advanced Geographic Information Systems (GIS) technology combined with modern web development. Users can discover, select, organize, and manage travel destinations through a visually engaging Kanban-style planning tool.

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

- **REST API:**
  - Modern RESTful endpoints for data fetching and manipulation.

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
  - **Spring Web** (RESTful controllers, HTTP endpoints)

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
  - Gradle (dependency management)
  - IntelliJ IDEA / VS Code with Java plugins (development environment)
  - Docker (containerization, local database setup)

---

## 🌍 API & External Integrations

- **OpenTripMap API** (comprehensive place data)
- **MapTiler OpenStreetMap Tiles** (free map tiles for visual representation)

---

## 🚧 Development Workflow

- **Frontend:**
  - Development via Angular CLI and npm

- **Backend:**
  - Managed through Gradle builds
  - Local database environment setup using Docker (PostgreSQL + PostGIS)

---

## 🛡️ Security

- Secure storage and rotation of API keys
- OAuth 2.0 with JWT-based authentication

---
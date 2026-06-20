# 📘 Four-Tier Diagnostic Test — Technical Design Documentation

Selamat datang di pusat dokumentasi teknis **Four-Tier Diagnostic Test (FT-Mitrack)**.

Repositori ini berfungsi sebagai sumber dokumentasi resmi untuk seluruh ekosistem FT-Mitrack, mulai dari arsitektur sistem, desain database, spesifikasi API, hingga implementasi frontend.

Dokumentasi disusun agar mudah dinavigasi oleh developer, system analyst, QA engineer, maupun maintainer proyek.

---

# 🏗️ Arsitektur Repositori

Ekosistem FT-Mitrack terdiri dari tiga repositori utama:

| Repository              | Deskripsi                                                                                                     |
| ----------------------- | ------------------------------------------------------------------------------------------------------------- |
| **ft-mitrack-frontend** | Single Page Application (SPA) untuk pelaksanaan dan pengelolaan ujian diagnostik Four-Tier menggunakan Vue 3. |
| **ft-mitrack-backend**  | REST API berbasis Golang yang menangani autentikasi, manajemen soal, ujian, hasil, dan pelaporan.             |
| **ft-mitrack-docs**     | Dokumentasi teknis, standar pengembangan, desain sistem, dan referensi proyek.                                |

---

# 📦 Project Overview

FT-Mitrack merupakan platform ujian diagnostik berbasis metode **Four-Tier Diagnostic Test** yang dirancang untuk:

* Mengidentifikasi pemahaman konsep peserta didik
* Mendeteksi miskonsepsi secara lebih akurat
* Mengukur tingkat keyakinan jawaban dan alasan
* Menyediakan analisis hasil secara terstruktur

---

# 🧩 Technology Stack

## Frontend

* Vue 3.5+
* Vite 8
* Pinia
* Vue Router
* Tailwind CSS v4
* KaTeX
* Axios

## Backend

* Go 1.22+
* Gorilla Mux
* SQLX
* PostgreSQL
* JWT Authentication
* RESTful API

## Documentation

* Markdown
* Mermaid Diagram
* OpenAPI Specification
* Kiro Steering Documents

---

# 📑 Dokumentasi Utama

Dokumentasi dibagi menjadi dua pilar utama:

## Backend Documentation

### Architecture

* System Architecture
* Layered Architecture
* Request Flow
* Service Design

### Database

* ERD (Entity Relationship Diagram)
* Database Schema
* Migration Strategy
* Indexing & Optimization

### API

* Authentication API
* User Management API
* Exam Management API
* Question Bank API
* Result & Analytics API

### Security

* JWT Authentication
* Authorization Flow
* Password Management
* Audit Logging

---

## Frontend Documentation

### Application Architecture

* Project Structure
* Routing Strategy
* State Management (Pinia)
* API Integration

### UI & Design System

* Design Tokens
* Components Library
* Layout System
* Responsive Design

### Assessment Module

* Exam Workflow
* Four-Tier Question Rendering
* Confidence Level Input
* Result Visualization

### Performance

* Code Splitting
* Lazy Loading
* Asset Optimization
* Caching Strategy

---

# 🔄 System Flow

```text
User
 │
 ▼
Frontend (Vue SPA)
 │
 ▼
REST API (Go)
 │
 ▼
PostgreSQL
 │
 ▼
Analytics & Reporting
```

---

# 📚 Additional References

* API Reference
* Coding Standards
* Git Workflow
* Release Notes
* Deployment Guide
* Testing Guide
* Kiro Steering Documents

---

# 🚀 Quick Start

## Clone Repository

```bash
git clone <repository-url>
```

## Open Documentation

```bash
cd ft-mitrack-docs
```

## Browse Documentation

Mulailah dari dokumen berikut:

```text
docs/
├── backend/
├── frontend/
├── architecture/
├── database/
├── api/
├── deployment/
└── release-notes/
```

---

# 📄 License

Internal Project — FT-Mitrack

Hak cipta dan penggunaan dokumentasi mengikuti kebijakan proyek yang berlaku.

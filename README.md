# 📘 Technical Design Document — Four-Tier Diagnostic Test

Selamat datang di pusat dokumentasi teknis sistem **Four-Tier Diagnostic Test**. Repositori ini berisi pedoman arsitektur, database, API, hingga panduan frontend secara komprehensif.

Semua dokumen di bawah ini saling terhubung untuk memudahkan navigasi. Silakan mulai eksplorasi melalui **Daftar Isi** berikut.

---

## 📑 Daftar Isi Utama

Dokumentasi dibagi menjadi dua pilar utama: **Backend** (Golang + PostgreSQL) dan **Frontend** (Vue 3 + Tailwind CSS v4).

### 🖥️ 1. Backend Documentation
Pedoman lengkap pengembangan sisi server, API, dan skema database.
*Indeks lengkap dapat dilihat di [Backend/README.md](./Backend/README.md).*

| No | Dokumen | Deskripsi | Link |
|----|---------|-----------|------|
| 1 | **Arsitektur Sistem** | Tech stack, Clean Architecture, project structure, middleware | [📄 Buka](./Backend/01-arsitektur-sistem.md) |
| 2 | **Database Schema** | PostgreSQL DDL, 7 tabel, indexes, constraints, seed data | [📄 Buka](./Backend/02-database-schema.md) |
| 3 | **API Auth** | Login, Register, Logout, JWT token specification | [📄 Buka](./Backend/03-api-auth.md) |
| 4 | **API Dosen** | 15 endpoints: CRUD matkul, soal, ujian, hasil, export | [📄 Buka](./Backend/04-api-dosen.md) |
| 5 | **API Mahasiswa** | 8 endpoints: token, soal, submit, hasil, history detail | [📄 Buka](./Backend/05-api-mahasiswa.md) |
| 6 | **Scoring Engine** | Go implementation, 16-combination map, score calc | [📄 Buka](./Backend/06-scoring-engine.md) |
| 7 | **Error Handling** | Error codes, HTTP status mapping, validation format | [📄 Buka](./Backend/07-error-handling.md) |
| 8 | **Data Dummy** | Seed data untuk keperluan testing dan development | [📄 Buka](./Backend/08-data-dummy.md) |
| 9 | **Perhitungan & Nilai**| Formula dan logika komputasi nilai secara mendalam | [📄 Buka](./Backend/09-perhitungan-dan-nilai.md) |
| 10 | **Developer Guide** | Panduan setup, running, Makefile, testing, dsb. | [📄 Buka](./Backend/10-developer-guide.md) |
| 11 | **Tech Stack** | Detail stack backend (Golang, Migrate, dsb) | [📄 Buka](./Backend/11-tech-stack.md) |
| 12 | **API Documentation** | Dokumentasi payload dan respons API lengkap | [📄 Buka](./Backend/12-api-documentation-full.md) |
| 13 | **DB Documentation** | Detail relasional dan kamus data PostgreSQL | [📄 Buka](./Backend/13-database-documentation.md) |

---

### 🎨 2. Frontend Documentation
Pedoman pengembangan antarmuka, routing, state management, dan komponen Vue 3.
*Indeks lengkap dapat dilihat di [Frontend/README.md](./Frontend/README.md).*

| No | Dokumen | Deskripsi | Link |
|----|---------|-----------|------|
| 1 | **Aturan & Konvensi** | Standar coding, penamaan, struktur project, styling | [📄 Buka](./Frontend/01-aturan-dan-konvensi.md) |
| 2 | **Halaman & Komponen**| Hierarki komponen, state sharing, reusable cards/modals | [📄 Buka](./Frontend/02-halaman-dan-komponen.md) |
| 3 | **Flow & Navigasi** | Penjelasan Vue Router, Route guards, alur navigasi user | [📄 Buka](./Frontend/03-flow-dan-navigasi.md) |
| 4 | **Setup & Instalasi** | Panduan inisialisasi frontend, instalasi dependency | [📄 Buka](./Frontend/04-setup-dan-instalasi.md) |
| 5 | **Tech Stack** | Detail spesifik frontend (Vue 3, Tailwind v4, Vite, Pinia) | [📄 Buka](./Frontend/05-tech-stack.md) |
| 6 | **Flow User Diagram** | Diagram arsitektural Mermaid untuk visualisasi proses | [📄 Buka](./Frontend/06-flow-user-diagram.md) |
| 7 | **Implementation Plan** | Rencana teknis dan fase implementasi frontend | [📄 Buka](./Frontend/07-implementation-plan.md) |
| 8 | **Progres Implementasi** | Catatan progres implementasi frontend (checklist) | [📄 Buka](./Frontend/08-progres-implementasi.md) |
| 9 | **Hasil Evaluasi** | Hasil evaluasi kesesuaian implementasi dengan PRD | [📄 Buka](./Frontend/09-hasil-evaluasi.md) |

---

## 🏗️ Quick Start & Setup Codebase

Jika Anda baru dalam proyek ini, metode tercepat untuk menjalankannya adalah:

1. **Backend Server**:  
   Kunjungi [Backend Developer Guide](./Backend/10-developer-guide.md) untuk instruksi mendirikan PostgreSQL server dan Go API.

2. **Frontend App**:  
   Lihat [Frontend Setup & Instalasi](./Frontend/04-setup-dan-instalasi.md) untuk panduan menjalankan Vite server.

---
*Dokumentasi ini otomatis dikurasi pada 22 Maret 2026. Harap diperbarui seiring dengan perkembangan kode (living document).*

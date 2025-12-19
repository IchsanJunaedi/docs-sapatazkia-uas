# SAPA-TAZKIA: AI-Powered RAG Chatbot
> **Dokumentasi Terpadu Proyek Akhir Pengembangan Aplikasi Web**

Repositori ini disusun secara sistematis untuk memenuhi seluruh deliverable dari Fase 1 hingga Fase 4 sesuai silabus manajemen proyek.

---

## Daftar Deliverable Proyek

### Fase 1: Inisiasi & Perencanaan

| Minggu | Deliverable | Deskripsi & Kriteria |
| :--- | :--- | :--- |
| **1** | **Pembentukan Tim & Ide** | Pembentukan tim **SAPA-TAZKIA**. Ide proyek berfokus pada solusi Chatbot RAG untuk mempermudah akses informasi akademik kampus Tazkia. |
| **2** | **Project Charter & WBS** | Perencanaan jadwal 16 minggu dan struktur kerja (WBS) yang realistis untuk pengembangan Frontend, Backend, dan Integrasi AI. |
| **3** | **Spesifikasi Kebutuhan (SKP)** | Dokumen hasil identifikasi kebutuhan pengguna: fitur login, akurasi jawaban AI, dan kecepatan akses informasi. |
| **4** | **Perancangan Sistem (UML)** | Dokumentasi diagram Use Case, Activity, dan Class serta ERD Database yang menjadi cetak biru pengembangan kode. |

---

### Fase 2: Analisis & Perancangan

| Minggu | Deliverable | Deskripsi & Kriteria |
| :--- | :--- | :--- |
| **5** | **Arsitektur & Basis Data** | Desain skema database menggunakan **Prisma ORM**. Arsitektur aplikasi dipisah (Decoupled) antara React (Frontend) dan Express (Backend). |
| **6** | **Desain UI/UX (Mockup)** | Desain antarmuka yang intuitif dan ergonomis. Implementasi komponen global di folder `src/components/common` untuk konsistensi UI. |
| **7** | **Presentasi UTS** | Pemaparan kesiapan desain dan arsitektur sebelum masuk ke fase implementasi penuh. |

---

### Fase 3: Implementasi & Pengembangan

| Minggu | Deliverable | Deskripsi & Kriteria |
| :--- | :--- | :--- |
| **8 & 10** | **Implementasi OOP & Git** | Pengembangan modul fungsional menggunakan prinsip **OOP**. Log perubahan terpantau melalui *Git Commit History* yang konsisten. |
| **9** | **Dokumentasi Teknis** | Dokumentasi lengkap mengenai alur data RAG, konfigurasi `.env`, dan panduan instalasi bagi pengembang lain. |
| **11** | **Integrasi DB & Deployment** | Koneksi penuh ke database SQL via Prisma. Aplikasi sudah dapat diakses daring (Online) dengan fitur CRUD user yang stabil. |
| **12** | **Analisis Risiko & Refactor** | Implementasi `rateLimitMiddleware.js` untuk mitigasi risiko biaya API dan catatan perbaikan struktur kode (Refactoring). |

---

### Fase 4: Pengujian, Evaluasi, & Finalisasi

| Minggu | Deliverable | Deskripsi & Kriteria |
| :--- | :--- | :--- |
| **13** | **Laporan Pengujian** | Hasil pengujian fungsional (Chat/Auth) dan non-fungsional (Keamanan/Performance) dengan status **PASSED**. |
| **14** | **Evaluasi UX (Skor SUS)** | Pengujian subjektif pengguna menggunakan metode **System Usability Scale**. Target skor: **>70 (Acceptable)**. |
| **15** | **Dokumen Proyek Akhir** | Bundel final yang berisi proposal, desain teknis, source code, dan panduan penggunaan aplikasi secara lengkap. |
| **16** | **Presentasi UAS** | Demonstrasi produk final (Live Demo) dan pertanggungjawaban teknis di hadapan tim penguji. |

---

## Ringkasan Teknologi (Stack)

- **Frontend:** React.js, Tailwind CSS, Axios.
- **Backend:** Node.js, Express.js.
- **Database:** PostgreSQL/MySQL via **Prisma ORM**.
- **AI/ML:** OpenAI API (GPT-4/3.5) dengan metode **RAG**.
- **Caching & Security:** Redis & Rate Limiter.

  ## **. Team Member**

1. **Muhammad Ichsan Junaedi (Project Manager, Frontend Developer, and Backend Developer)**  
   [LinkedIn – Muhammad Ichsan Junaedi](https://www.linkedin.com/in/muhammad-ichsan-junaedi-74039b288/)

2. **Rahmawati (Business Analyst)**  
   [LinkedIn – Rahmawati](https://www.linkedin.com/in/rahmawati-269732281/)

3. **Rafly Ariel Hidayat (Backend Developer)**  
   [LinkedIn – Rafly Ariel Hidayat](https://www.linkedin.com/in/rafly-ariel-hidayat-794406392/)

4. **Nabila Nurul Haq (UI/UX Designer)**  
   [LinkedIn – Nabila Nurul Haq](https://www.linkedin.com/in/nabila-nurul-haq-1b0694343/)


© 2024 SAPA-TAZKIA Team - Project Management & Web Development.

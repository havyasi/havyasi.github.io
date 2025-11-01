---
title: "Pertemuan 6: API Testing"
date: 2025-11-01
categories: [API Testing]
tags: [API, Postman, SoapUI, Request, Response, Status Code]
---

# Rangkuman Pertemuan 6: API Testing

Materi ini, yang dibawakan oleh Kelompok 6, membahas pengujian pada *Application Programming Interface* (API).

## Poin Utama

* **Definisi API Testing:** Proses pengujian yang dilakukan pada API untuk memastikan API berfungsi sesuai spesifikasi, dapat menangani berbagai skenario, dan menghasilkan *output* yang benar.
* **Keunggulan/Pentingnya API Testing:**
    * Memastikan API berfungsi sesuai spesifikasi.
    * Meningkatkan keandalan sistem dengan deteksi *bug* lebih awal.
    * Menjamin keamanan API dari akses tidak sah.
    * Mengukur performa API di bawah beban.
    * Mempercepat siklus pengembangan.
* **Anatomi Request & Response:**
    * **Request API:** Permintaan dari klien ke server. Komponen utamanya:
        * **Method (HTTP Verb):** Aksi yang diinginkan (GET, POST, PUT, DELETE).
        * **URL (Endpoint):** Alamat dari *resource* yang dituju.
    * **Response API:** Balasan dari server ke klien. Komponen utamanya:
        * **Status Code:** Kode numerik yang menandakan hasil eksekusi (misal: 200 OK, 404 Not Found, 401 Unauthorized).
* **Tools API Testing:**
    * **Postman:** Tools populer yang *user-friendly* , mendukung berbagai metode HTTP , dan memiliki fitur *collection* , *environment* , dan *testing* otomatis.
    * **SoapUI:** Tools yang kuat untuk SOAP (berbasis XML) dan REST API. Mendukung *functional*, *security*, dan *load testing*.

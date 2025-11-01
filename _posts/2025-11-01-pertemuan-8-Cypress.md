---
title: "Pertemuan 8: Pengantar Cypress"
date: 2025-11-01
categories: [Automation Testing]
tags: [Cypress, End-to-End Testing, E2E, Test Runner]
---

# Rangkuman Pertemuan 8: Pengantar Cypress

Materi ini, yang dibawakan oleh Kelompok 8, memberikan pengantar mengenai *framework* Cypress.

## Poin Utama

* **Apa itu Cypress?**
    * Cypress adalah *framework* **end-to-end (E2E) testing** modern.
    * Digunakan untuk menguji aplikasi web modern (React, Vue, Angular, dll.).
    * Posisinya berada di level E2E, namun juga bisa untuk *Integration* dan *Component Testing*.
* **Perbedaan Utama (Keunggulan Cypress):**
    Berbeda dengan Selenium, Cypress memiliki beberapa keunggulan:
    * **Arsitektur Modern:** Berjalan di *event loop* yang sama dengan aplikasi, membuatnya lebih cepat dan stabil.
    * **Test Runner Interaktif:** Memungkinkan kita melihat perintah berjalan secara *real-time* dan men-debug secara visual.
    * **Time Travel:** Kita bisa melihat *snapshot* aplikasi pada setiap langkah perintah, memudahkan *debugging*.
    * **Automatic Waits:** Cypress secara otomatis menunggu elemen muncul atau perintah selesai, menghilangkan kebutuhan *wait* manual yang sering ada di Selenium.
* **Perintah Dasar:**
    * `cy.visit('URL')`: Membuka halaman web.
    * `cy.get('selector')`: Mengambil elemen berdasarkan *selector* (seperti ID atau class).
    * `cy.contains('text')`: Mencari elemen berdasarkan teks di dalamnya.
    * `cy.click()`: Melakukan klik pada elemen.
    * `cy.type('text')`: Mengetik ke dalam *input field*.
* **Studi Kasus (SauceDemo):**
    Presentasi ini juga menggunakan "saucedemo.com"  untuk mendemonstrasikan *test case* login, seperti login valid , login dengan password salah , dan login dengan *username* kosong.

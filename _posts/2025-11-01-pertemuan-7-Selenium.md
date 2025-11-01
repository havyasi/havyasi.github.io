---
title: "Pertemuan 7: Pengantar Selenium"
date: 2025-11-01
categories: [Automation Testing]
tags: [Selenium, WebDriver, Browser Automation, SauceDemo]
---

# Rangkuman Pertemuan 7: Pengantar Selenium

Materi ini, yang dibawakan oleh Kelompok 7, berfokus pada *framework* automasi Selenium.

## Poin Utama

* **Apa itu Selenium?**
    * Selenium adalah *framework* **open-source** untuk **automasi browser**.
    * Umumnya digunakan untuk menguji aplikasi web.
    * Mendukung banyak browser (Chrome, Firefox, Edge, Safari) dan berbagai bahasa pemrograman (Python, Java, C#, JS).
    * Dapat diintegrasikan dengan *framework testing* lain seperti Pytest, JUnit, atau TestNG.
* **Selenium WebDriver:**
    * WebDriver adalah **komponen inti** dari Selenium.
    * Berfungsi sebagai **penghubung** (jembatan) antara kode skrip pengujian kita dengan *browser* yang dituju.
    * WebDriver-lah yang bertugas memberi perintah ke *browser* untuk melakukan aksi (klik, input teks, navigasi).
* **Test Scenario & Test Case (Contoh: SauceDemo):**
    * Presentasi ini menggunakan studi kasus pengujian pada situs "SauceDemo".
    * **Test Scenario :** Mencakup skenario seperti "Login berhasil" , "Login gagal" , dan "Menambahkan produk ke keranjang".
    * **Test Case, 56:** Mendetailkan skenario tersebut.
        * **TC-001 (Login sukses):** Input `standard_user` & `secret_sauce`, klik Login. Hasil: Masuk ke halaman *inventory*.
        * **TC-002 (Login gagal):** Input *user* salah, klik Login. Hasil: Muncul pesan *error*.

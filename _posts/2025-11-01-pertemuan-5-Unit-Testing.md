---
title: "Pertemuan 5: Pengantar Unit Testing"
date: 2025-11-01
categories: [Unit Testing]
tags: [JUnit, Pytest, Jest, AAA, Arrange Act Assert]
---

# Rangkuman Pertemuan 5: Pengantar Unit Testing

Materi ini, yang dibawakan oleh Kelompok 5, memberikan pengantar mengenai *Unit Testing*.

## Poin Utama

* **Definisi Unit Testing:** Jenis pengujian yang berfokus pada **unit-unit terkecil** dalam perangkat lunak, seperti *function*, *method*, atau *class*. Ini adalah level pengujian paling awal , tercepat, dan termurah.
* **Pentingnya Unit Testing:**
    * Mendeteksi *bug* lebih awal.
    * Mempermudah perubahan dan *refactoring* kode.
    * Menjadi "dokumentasi hidup" yang menjelaskan cara kerja kode.
    * Menghemat waktu dan biaya perbaikan di tahap akhir.
* **Pola Arrange-Act-Assert (AAA):**
    Ini adalah pola standar dalam penulisan *unit test*:
    1.  **Arrange:** Menyiapkan kondisi awal dan *input* yang diperlukan    
    2.  **Act:** Menjalankan *function* atau *method* yang akan diuji .
    3.  **Assert:** Memverifikasi (mengecek) apakah hasil dari *Act* sesuai dengan yang diharapkan (*expectation*)  .
* **Framework Populer:**
    * **JUnit 5 (Java):** Pelopor *unit testing* di Java, berbasis anotasi .
    * **Jest (JavaScript):** Dibuat oleh Meta, populer untuk React dan Node.js, dengan konfigurasi minimal  .
    * **Pytest (Python):** Dikenal sederhana, mudah dibaca, dan memiliki fitur *fixtures* yang kuat  .
* **Contoh Kode:** Presentasi mencakup *live coding* menggunakan Pytest (untuk *shopping cart*)  dan JUnit 5 (untuk *bank account*).

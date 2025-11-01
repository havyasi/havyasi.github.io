---
title: "Pertemuan 1: Strategi Testing"
date: 2025-06-01
categories: [Strategi Testing]
tags: [SDLC, STLC, Klasifikasi Testing, Black Box, White Box]
---

# Rangkuman Pertemuan 1: Strategi Testing

Materi ini, yang dibawakan oleh Kelompok 1, membahas dasar-dasar dan strategi dalam *software testing*.

## Poin Utama

* **Definisi Testing:** Testing adalah proses mengevaluasi perangkat lunak untuk menemukan cacat (*bug*) dan memastikan produk bekerja sesuai kebutuhan fungsional maupun non-fungsional. Tujuannya adalah menemukan kesalahan dan menjamin kualitas sebelum rilis.
* **Software Development Life Cycle (SDLC):** Perangkat lunak dikembangkan melalui siklus hidup (SDLC) yang mencakup tahapan: Planning, Analysis, Design, Implementation, Testing & Integration, dan Maintenance.
* **Software Testing Life Cycle (STLC):** Testing memiliki siklus hidupnya sendiri (STLC) yang merupakan proses sistematis, dimulai dari **Test Planning** (membuat strategi, mengidentifikasi lingkungan, memperkirakan waktu dan biaya) dan **Test Design** (mengidentifikasi dan menulis *test case*).
* **Klasifikasi Testing:**
    * **Berdasarkan Abstraksi:** Dimulai dari level terkecil yaitu **Unit Testing** (menguji fungsi/kelas), **Integration Testing** (interaksi antar unit), **System Testing** (menguji sistem secara keseluruhan), dan **Acceptance Testing** (validasi oleh pengguna akhir).
    * **Berdasarkan Struktur (Knowledge):**
        * **Black-Box Testing:** Menguji fungsionalitas tanpa mengetahui struktur kode internal.
        * **White-Box Testing:** Menguji berdasarkan pengetahuan tentang struktur kode internal dan logika program.
    * **Berdasarkan Fungsi:** Menguji **Fungsional** (apakah fitur bekerja sesuai syarat) dan **Non-Fungsional** (bagaimana sistem bekerja, misal: performa, keamanan, reliabilitas).
    * **Berdasarkan Domain:** Mencakup **Performance Testing** (kecepatan/stabilitas), **Security Testing** (celah keamanan), dan **Usability Testing** (kemudahan penggunaan).

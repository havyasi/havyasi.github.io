---
title: "Pertemuan 4: Test Scenario, Test Case, dan Bug Report"
date: 2025-11-01
categories: [Testing Artifacts]
tags: [Test Scenario, Test Case, Bug Report, Severity, Priority]
---

# Rangkuman Pertemuan 4: Test Scenario, Test Case, dan Bug Report

Materi ini, yang dibawakan oleh Kelompok 4 fokus pada tiga elemen penting dalam dokumentasi pengujian.

## Poin Utama

* **Test Scenario:**
    * **Definisi:** Gambaran umum tentang **apa yang harus diuji**. Fokusnya pada satu fungsionalitas.
    * **Contoh:** "Periksa hasil perhitungan dan klasifikasi BMI".

* **Test Case:**
    * **Definisi:** Langkah-langkah detail tentang **bagaimana melakukan pengujian**.
    * **Komponen:** Mencakup ID, Deskripsi, *Precondition* (kondisi awal), *Test Steps* (langkah-langkah), *Test Data*, *Expected Result* (hasil yang diharapkan), *Actual Result* (hasil aktual), dan Status (Pass/Fail).
    * **Contoh:** Verifikasi hasil BMI untuk kategori "Normal" dengan data Tinggi = 165cm dan Berat = 60kg, diharapkan menampilkan BMI 25.95 dan kategori "Normal"tatan: *Terdapat kesalahan ketik di slide, seharusnya BMI 22.04 dan kategori "Normal"*

* **Bug Report:**
    * **Definisi:** Laporan formal yang mendokumentasikan kesalahan atau masalah yang ditemukan di aplikasi.
    * **Tingkat Keparahan (Severity)engukur dampak bug pada fungsionalitas.
        * **Critical:** Menyebabkan kegagalan total, aplikasi tidak dapat digunakan     * **Major (High):** Fungsionalitas utama tidak bekerja, tapi sistem tidak *crash*     * **Minor (Medium):** Tidak memengaruhi fungsionalitas utama, tapi mengganggu kenyamanan     * **Low:** Bug kosmetik atau tidak merusak * **Prioritas (Priority)enentukan urgensi perbaikan bug.
        * **P1 (Urgent/Critical):** Harus segera diperbaiki     * **P2 (High):** Penting, diperbaiki secepatnya     * **P3 (Medium):** Diperbaiki di siklus rilis berikutnya     * **P4 (Low):** Diperbaiki kapan saja

# Manual Testing Portfolio – Login Feature Testing

## Deskripsi Project

Project ini merupakan latihan **manual testing** yang dilakukan pada fitur login dari website **the-internet.herokuapp.com**.
Tujuan dari pengujian ini adalah untuk memastikan bahwa fitur login berfungsi dengan benar ketika menggunakan kredensial yang valid maupun tidak valid.

## Aplikasi yang Diuji

URL: https://the-internet.herokuapp.com/login

## Ruang Lingkup Pengujian

Pengujian difokuskan pada **fitur login**, dengan beberapa skenario pengujian seperti:

* Login menggunakan username dan password yang valid
* Login dengan password yang salah
* Login dengan username yang tidak terdaftar
* Login dengan field username atau password kosong
* Pengujian perilaku sistem terhadap navigasi browser (back button)
* Pengujian batas input (input yang sangat panjang)

## Dokumen Pengujian

Repository ini berisi beberapa artefak pengujian, yaitu:

* **Test Plan**
  Menjelaskan tujuan pengujian, ruang lingkup, serta environment yang digunakan.

* **Test Scenario**
  Berisi daftar skenario pengujian yang akan dilakukan pada fitur login.

* **Test Case**
  Berisi langkah-langkah detail pengujian beserta expected result dan actual result.

* **Bug Report**
  Dokumentasi bug yang ditemukan selama proses pengujian.

* **Bug Evidence**
  Screenshot yang menunjukkan bukti terjadinya bug.

## Tools yang Digunakan

* Google Sheets
* Web Browser (Google Chrome)
* Manual Testing Technique

## Metode Pengujian
* Functional Testing
* Negative Testing
* Exploratory Testing

## Temuan Bug

Selama proses pengujian ditemukan satu anomali pada sistem:

**BUG01 – Halaman secure masih dapat diakses setelah logout ketika tombol back pada browser ditekan.**

Bug ini berkaitan dengan kemungkinan **browser caching atau session handling** pada aplikasi.

## Tester

Aji Nugroho
Mahasiswa Informatika
Latihan Manual QA Testing

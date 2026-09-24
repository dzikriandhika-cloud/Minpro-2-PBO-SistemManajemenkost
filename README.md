# Sistem Manajemen Data Kost

## Deskripsi
Program ini merupakan aplikasi berbasis Java untuk mengelola data kost. 
Aplikasi dibuat untuk memenuhi tugas Mini Project 2 mata kuliah Pemrograman Berorientasi Objek (PBO).

## Fitur
- Menampilkan data penghuni kost
- Mengelola data mahasiswa dan karyawan
- Implementasi konsep Object Oriented Programming (OOP)
- Encapsulation menggunakan getter dan setter
- Inheritance menggunakan class turunan
- Override method

## Konsep PBO yang Digunakan
- Class dan Object
- Constructor
- Encapsulation
- Inheritance
- Polymorphism

## Teknologi
- Java
- NetBeans IDE
- Maven

## Struktur Class
- PenghuniKost.java (Superclass)
- Mahasiswa.java (Subclass)
- Karyawan.java (Subclass)
- Minpro2PBOSistemManajemenDataKost.java (Main Class)

  ## Alur Program

Program dimulai dari class Minpro2PBOSistemManajemenDataKost sebagai main class.
Pada saat program dijalankan, sistem membuat objek dari class Mahasiswa dan Karyawan yang merupakan turunan dari class PenghuniKost.
Data penghuni kemudian ditampilkan menggunakan method tampilData().

## Penerapan Encapsulation

Konsep encapsulation diterapkan pada class PenghuniKost dengan menggunakan modifier private pada atribut dan menyediakan method getter serta setter untuk mengakses dan mengubah data.

## Penerapan Inheritance

Konsep inheritance diterapkan dengan membuat class Mahasiswa dan Karyawan sebagai subclass dari class PenghuniKost.
Subclass tersebut mewarisi atribut dan method dari superclass PenghuniKost.

## Penerapan Polymorphism

Polymorphism diterapkan menggunakan method overriding pada method tampilData().
Class Mahasiswa dan Karyawan memiliki implementasi tampilData() yang berbeda dari class PenghuniKost.

## Author
Dzikri Andhika

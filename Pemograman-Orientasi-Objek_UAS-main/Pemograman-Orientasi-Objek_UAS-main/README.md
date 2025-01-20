# UAS-OOP: CRUD Mahasiswa dengan Java (MVC dan MySQL)

Proyek ini adalah aplikasi **CRUD Mahasiswa** yang dibangun menggunakan **Java**, dengan menerapkan arsitektur **MVC (Model-View-Controller)**. Program ini juga terhubung dengan **MySQL** sebagai sistem manajemen basis data untuk menyimpan dan memanipulasi data mahasiswa dan nilai mereka.

## Identitas Proyek

- **Nama:** Wishnu Aqbil Ramadani
- **NIM:** 312310591
- **Kelas:** TI.23.A6  
- **Mata Kuliah:** Pemrograman Berorientasi Objek  
- **Dosen:** Agung Nugroho, S.Kom., M.Kom.

## Deskripsi Proyek

Proyek ini dibuat untuk memenuhi tugas akhir mata kuliah **Pemrograman Berorientasi Objek (OOP)** dengan menerapkan konsep dasar **CRUD** (Create, Read, Update, Delete). CRUD digunakan untuk mengelola data mahasiswa melalui antarmuka berbasis Java yang terhubung dengan MySQL untuk penyimpanan data. Program ini memanfaatkan pola desain **MVC** untuk memisahkan antara tampilan pengguna, logika bisnis, dan pengelolaan data.

## Arsitektur MVC

Arsitektur **MVC** digunakan untuk memisahkan tugas dan tanggung jawab dalam aplikasi ini. Pembagian ini membuat pengembangan dan pemeliharaan program menjadi lebih terstruktur. Berikut adalah penjelasan setiap komponen MVC:

- **Model:** Komponen ini bertanggung jawab untuk mengelola data aplikasi. Model mengakses database dan melakukan operasi CRUD, seperti menambahkan, mengedit, atau menghapus data mahasiswa.
  
- **View:** Bagian ini berfungsi sebagai antarmuka pengguna. View menampilkan informasi kepada pengguna dan menerima input dari mereka. Antarmuka ini dapat berupa form-form untuk input data mahasiswa dan nilai.

- **Controller:** Controller berfungsi untuk menghubungkan Model dan View. Ia menangani interaksi pengguna, memproses data yang dimasukkan, dan memerintahkan Model untuk melakukan operasi tertentu (seperti menambah, memperbarui, atau menghapus data). Setelah itu, Controller memberi perintah kepada View untuk menampilkan hasilnya.

## Alur Kerja Program

Berikut adalah langkah-langkah alur kerja dari program ini:

1. **Menjalankan Program:** Program dimulai dengan menjalankan file `Main.java`, yang menjadi titik awal eksekusi.
2. **Instansiasi View dan Controller:** Instance dari **View** dan **Controller** akan dibuat untuk memulai proses interaksi dengan pengguna.
3. **Inisialisasi Model:** **Controller** akan menginisialisasi **Model** yang akan bertugas dalam manipulasi data.
4. **Interaksi Pengguna:** **View** akan menampilkan antarmuka kepada pengguna untuk memasukkan data mahasiswa dan nilai.
5. **Proses Input:** Pengguna akan memasukkan data melalui form yang disediakan oleh **View**.
6. **Pemrosesan Data:** **Controller** akan memproses data yang dimasukkan dan memberikan perintah kepada **Model**.
7. **Operasi Database:** **Model** akan berinteraksi dengan MySQL untuk melakukan operasi sesuai perintah (misalnya menambah atau menghapus data).
8. **Menampilkan Hasil:** Setelah operasi selesai, **View** akan menampilkan hasilnya kembali kepada pengguna.

## Fitur Program

Program ini menyediakan beberapa fitur utama untuk pengelolaan data mahasiswa dan nilai mereka, antara lain:

- **Create:** Menambahkan data mahasiswa dan nilai baru ke dalam database.
- **Read:** Menampilkan data mahasiswa dan nilai yang sudah ada dalam database.
- **Update:** Memperbarui data mahasiswa atau nilai yang sudah ada.
- **Delete:** Menghapus data mahasiswa atau nilai yang dipilih dari database.

## Dokumentasi Output

Berikut adalah beberapa tampilan output dari program ini:

1. **Form Mahasiswa:** Form untuk memasukkan data mahasiswa yang mencakup informasi seperti nama, NIM, jurusan, dan lainnya.
2. **Form Nilai:** Form untuk memasukkan nilai mata kuliah mahasiswa yang mencakup kolom untuk kode mata kuliah, nilai, dan lainnya.
3. **Create Nilai:** Tampilan form untuk menambahkan nilai baru bagi mahasiswa.
4. **Update Nilai:** Tampilan form untuk memperbarui nilai yang sudah ada untuk mahasiswa tertentu.

## Video Penjelasan

Untuk pemahaman lebih mendalam tentang pembuatan dan implementasi proyek ini, Anda bisa menonton penjelasan lengkap melalui video berikut:  
[Klik di sini untuk menontonnya di YouTube](https://youtu.be/g4Mn3V7_nk4?si=85ZQwCqEIhx6pXOt)

---


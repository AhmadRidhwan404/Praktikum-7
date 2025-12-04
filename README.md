Program Daftar Nilai Mahasiswa (OOP Python)

Program ini dibuat menggunakan Python dengan pendekatan Object-Oriented Programming (OOP) untuk mengelola daftar nilai mahasiswa.
Program menyediakan menu interaktif untuk menambah, menampilkan, mengubah, dan menghapus data mahasiswa.

## Diagram kelas
        +--------------------------------------------------------+
        |                DaftarNilaiMahasiswa                    |
        +--------------------------------------------------------+
        | - mahasiswa : dict                                     |
        +--------------------------------------------------------+
        | + __init__()                                           |
        | + find_key(nama)                                       |
        | + tambah()                                             |
        | + tampilkan()                                          |
        | + hapus(nama)                                          |
        | + ubah(nama)                                           |
        +--------------------------------------------------------+
Fitur program 
Menambah data mahasiswa
- Input nama mahasiswa
- Input nilai
- Jika nama sudah ada → nilai diperbarui otomatis
  
+ Menampilkan seluruh data mahasiswa
+ Tersusun dari nilai tertinggi ke terendah
+ Menampilkan statistik:
+ Total mahasiswa
+ Nilai tertinggi
+ Nilai terendah
+ Rata-rata nilai
+ Mengubah nilai mahasiswa
+ Menghapus data mahasiswa
+ Menu interaktif
+ Pengguna dapat memilih fitur berulang kali hingga memilih keluar.

## Metode & Penjelasan 
     | Method           | Fungsi                                                |
     | ---------------- | ----------------------------------------------------- |
     | `__init__()`     | Menginisialisasi atribut dictionary kosong            |
     | `find_key(nama)` | Mencari nama mahasiswa (tanpa peka huruf besar-kecil) |
     | `tambah()`       | Menambah atau memperbarui nilai mahasiswa             |
     | `tampilkan()`    | Menampilkan seluruh data + statistik nilai            |
     | `hapus(nama)`    | Menghapus data mahasiswa dari dictionary              |
     | `ubah(nama)`     | Mengubah nilai mahasiswa berdasarkan nama             |

## Contoh output program 
    ==================================================
             MENU DAFTAR NILAI MAHASISWA
    ==================================================
     1. Tambah data mahasiswa
     2. Tampilkan data mahasiswa
     3. Hapus data mahasiswa
     4. Ubah data mahasiswa
     5. Keluar
    ==================================================
    Pilih menu (1-5):

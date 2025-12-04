**##Diagram Kelas**
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

**##Program Daftar Nilai Mahasiswa**

Program ini dibuat menggunakan Python dengan pendekatan Object-Oriented Programming (OOP). Program berfungsi untuk mengelola data nilai mahasiswa, seperti menambah, menampilkan, mengubah, dan menghapus data nilai mahasiswa.

Seluruh data disimpan dalam dictionary (dict) yang berada di dalam class.

**Fitur Program**
Program menyediakan beberapa fitur utama:

Menambah data mahasiswa
Input nama mahasiswa
Input nilai
Jika nama sudah ada, nilai akan otomatis diperbarui
Menampilkan daftar nilai mahasiswa
Ditampilkan dalam bentuk daftar yang sudah diurutkan dari nilai tertinggi
Menampilkan statistik: total mahasiswa, nilai tertinggi, terendah, dan rata-rata
Menghapus data mahasiswa berdasarkan nama
Mengubah nilai mahasiswa
Menu interaktif
Memungkinkan pengguna memilih fitur secara berulang sampai memilih keluar

Struktur Program
Program ini terdiri dari satu class dan satu fungsi utama:

### 1. Class: DaftarNilaiMahasiswa
Class ini bertanggung jawab mengelola seluruh data mahasiswa.
Atribut:
mahasiswa → dictionary untuk menyimpan data dalam format:
{"Nama": nilai}
Method dalam class:
Method	Fungsi
__init__()	Menginisialisasi dictionary kosong
find_key(nama)	Mencari key dalam dictionary secara case-insensitive
tambah()	Menambah atau mengupdate nilai mahasiswa
tampilkan()	Menampilkan seluruh data + statistik nilai
hapus(nama)	Menghapus data berdasarkan nama
ubah(nama)	Mengubah nilai mahasiswa

2. Fungsi main()
Berisi:
Menu utama
Input pilihan menu
Pemanggilan method dari class DaftarNilaiMahasiswa
Perulangan hingga pengguna memilih keluar

Alur Program
Program dimulai dan membuat objek:

daftar = DaftarNilaiMahasiswa()

Program menampilkan menu berulang kali:
Tambah data
Tampilkan data
Hapus data
Ubah data
Keluar
Setiap menu memanggil method yang sesuai dalam class.
Program selesai setelah pengguna memilih opsi Keluar.

**Contoh Output Program**

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

**Konsep OOP yang Digunakan**
Program ini menggunakan beberapa konsep OOP:

 - Class
Tempat menyimpan atribut dan method terkait.

- Object
Instansiasi dari class yang digunakan pada fungsi main().

- Method
Fungsi dalam class seperti tambah(), tampilkan(), hapus(), dll.

- Encapsulation
Semua logic data mahasiswa disimpan di dalam class agar lebih rapi dan terorganisir.

Cara Menjalankan Program

Simpan file Python, misalnya nilai_mahasiswa.py
Jalankan melalui terminal/cmd:
python nilai_mahasiswa.py


Pilih menu sesuai kebutuhan.

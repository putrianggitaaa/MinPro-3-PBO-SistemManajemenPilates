# Sistem Manajemen Pilates - Geets Pilates Studio
**Putri Anggita Melasari | 2509116010**

## Deskripsi Program
Sistem Manajemen Pilates Geets Pilates Studio merupakan sebuah program yang dirancang untuk membantu proses pengelolaan data pada sebuah studio Pilates secara sederhana.
Program ini menyediakan beberapa menu yang dapat digunakan untuk mengelola informasi terkait Member, Instruktur, Jenis Kelas, dan Data Kelas Pilates. 
Sistem ini dapat membantu pengelola untuk memanajemen proses bisnis yang terdapat dalam Geets Pilates Studio.

## Struktur Packages
Program Sistem Manajemen Pilates menerapkan konsep MVC (Model, View, Controller) dengan membagi struktur program ke dalam beberapa package, yaitu model, view, dan controller. 
Pembagian ini digunakan untuk memisahkan pengelolaan data, proses pengolahan data, serta bagian utama yang menjalankan program. 

<img width="412" height="610" alt="image" src="https://github.com/user-attachments/assets/1600bd0a-390c-4ccd-bd77-bd395784817a" />

Berikut adalah penjelasan dari masing-masing package yang ada didalam packages tersebut:

### 1. Package Controller
Package controller berfungsi untuk mengatur alur proses dan logika interaksi antara bagian view, model, dan service. Controller menerima pilihan atau input dari pengguna melalui View, kemudian menjalankan proses sesuai dengan fitur yang dipilih.

### 2. Package Main
Package main merupakan bagian yang digunakan sebagai titik awal atau entry point dari program. 

### 3. Package Model
Package model berisi class yang digunakan untuk merepresentasikan objek dan data utama dalam sistem manajemen Pilates.

### 4. Package Service
Package service berisi class yang menangani proses pendukung dan validasi yang digunakan oleh sistem.

### 5. Package View
Package view bertanggung jawab terhadap tampilan dan interaksi langsung dengan pengguna. View digunakan untuk menampilkan menu, informasi data, serta meminta input dari pengguna.

## Alur Program
Alur program dimulai ketika pengguna menjalankan program melalui class Pilates.java sebagai class utama. Setelah program dijalankan, sistem akan menampilkan halaman utama  yang berisi beberapa pilihan menu.
Pengguna dapat memilih menu dengan menginput angka sesuai dengan pilihan yang tersedia. Sistem kemudian menggunakan percabangan switch-case untuk menentukan proses yang akan dijalankan.

Jika pengguna memilih menu Member, sistem akan mengarahkan pengguna ke proses lihat, tambah, update atau hapus data member. Jika memilih Instruktur, sistem akan mengarahkan pengguna ke proses lihat, tambah, update atau hapus data instruktur. Jika memilih Jenis Kelas, sistem akan mengarahkan pengguna ke proses lihat, tambah, update atau hapus data Jenis Kelas. Apabila pengguna memilih menu daftar kelas, maka akan diarahkan ke lihat daftar kelas yang sudah ada, menambahkan daftar kelas baru, menghapus daftar kelas yang sudah ada, dan melakukan update pada data daftar kelas. 

Program akan terus berjalan dan menampilkan kembali menu utama selama pengguna belum memilih menu Keluar. Dengan demikian, pengguna dapat melakukan beberapa proses pengelolaan data dalam satu kali menjalankan program.

## Penerapan Encapsulation

## Penerapan Inheritance

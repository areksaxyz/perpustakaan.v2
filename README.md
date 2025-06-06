# 📚 Perpustakaan Digital Java

Selamat datang di repositori **Perpustakaan Digital** – sebuah aplikasi sistem manajemen perpustakaan berbasis Java yang dirancang untuk mengelola buku fisik dan digital, peminjaman, katalog, manajemen denda, serta statistik perpustakaan. Proyek ini dikembangkan untuk memenuhi kebutuhan perpustakaan modern melalui antarmuka pengguna yang intuitif dan fungsionalitas lengkap.

---

## 🎯 Fitur Utama

- **Manajemen Buku**: Tambah, ubah, dan hapus buku digital (dengan URL/PDF) serta buku fisik.
- **Peminjaman Buku**: Sistem peminjaman lengkap dengan status pengembalian dan denda otomatis.
- **Katalog Buku**: Katalog terpisah untuk buku fisik dan digital, dilengkapi fitur pencarian.
- **Manajemen Denda**: Pelacakan dan pengelolaan denda keterlambatan secara efisien.
- **Statistik Perpustakaan**: Statistik real-time mengenai aktivitas peminjaman.
- **Antarmuka Modern**: Tampilan UI menggunakan FlatLaf untuk pengalaman pengguna yang lebih nyaman.

---

## 🖼️ Penjelasan Antarmuka

### 1. Beranda
Menampilkan ringkasan informasi perpustakaan seperti jumlah buku dan peminjaman terbaru.  
![Beranda](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/beranda.png?raw=true)

### 2. Mode Baca
Pengguna dapat membaca buku digital langsung dari aplikasi melalui URL atau file PDF.  
![Mode Baca](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/modebaca.png?raw=true)  
![Mode Baca 2](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/modebaca2.png?raw=true)

### 3. Buku Digital
Kelola data buku digital: judul, penulis, tahun terbit, dan URL PDF.  
![Buku Digital](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/BukuDigital.png?raw=true)

### 4. Buku Fisik
Manajemen buku fisik dengan fitur serupa, tanpa file PDF.  
![Buku Fisik](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/bukufisik.png?raw=true)

### 5. Katalog Digital
Menampilkan seluruh koleksi buku digital dengan fitur pencarian.  
![Katalog Digital](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/katalog.png?raw=true)

### 6. Katalog Fisik
Katalog buku fisik dengan pencarian berdasarkan judul, penulis, atau kategori.  
![Katalog Fisik](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/katalogfisik.png?raw=true)

### 7. Peminjaman
Fitur peminjaman buku fisik, form peminjaman, serta tombol pengembalian dan penambahan denda.  
![Peminjaman](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/peminjaman.png?raw=true)

### 8. Statistik
Menampilkan grafik/statistik jumlah buku dipinjam, dikembalikan, dan total denda.  
![Statistik](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/riwayat.png?raw=true)

### 9. Manajemen Denda
Melacak pengguna yang memiliki denda, lengkap dengan jumlah dan opsi pengelolaan.  
![Manajemen Denda](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/manajemendenda.png?raw=true)

---

## ⚙️ Teknologi yang Digunakan

- **Bahasa Pemrograman**: Java (JDK 24)
- **Framework UI**: Swing dengan tema modern dari FlatLaf
- **Database**: SQLite via JDBC

---

## 📦 Dependensi Eksternal

- `FlatLaf 3.3` – Tema UI  
- `SQLite JDBC 3.49.1.53` – Koneksi database SQLite  
- `PDFBox 2.0.27` – Pembaca file PDF  
- `Commons Logging 1.2` & `FontBox 2.0.27` – Dependensi PDFBox

---

## 🔧 Prasyarat

- Java Development Kit (JDK 24 atau lebih baru)
- Dependensi `.jar` di dalam folder `lib/`
- Sistem operasi: Windows, macOS, atau Linux

---

## 🚀 Instalasi

### 1. Clone Repositori

```bash
git clone https://github.com/areksaxyz/perpustakaan.v2
cd perpustakaan.v2
```

---

#### 2. **Bagian Kompilasi Kode**  
Tambahkan tanda kode blok agar jelas:

```bash
javac -cp ".:lib/flatlaf-3.3.jar:lib/sqlite-jdbc-3.49.1.53.jar:lib/pdfbox-2.0.27.jar:lib/commons-logging-1.2.jar:lib/fontbox-2.0.27.jar" -d . src/model/*.java src/storage/*.java src/ui/*.java src/utils/*.java
```

---

## 🧭 Penggunaan

- **Beranda**: Menampilkan gambaran umum perpustakaan.
- **Mode Baca**: Akses dan baca buku digital langsung dari aplikasi.
- **Buku Digital/Fisik**: Tambah atau hapus buku dari daftar.
- **Katalog**: Cari buku berdasarkan judul, penulis, atau kategori.
- **Peminjaman**: 
  - Isi form peminjaman (nama, kelas, NIM).
  - Gunakan tombol **Kembalikan** untuk pengembalian buku.
  - Gunakan tombol **Belum Dikembalikan** untuk menambah denda.
- **Manajemen Denda**: Lihat dan kelola denda peminjam.
- **Statistik**: Lihat laporan peminjaman dan grafik statistik.

## 📞 Kontak

- 📧 Email: [m.argareksapati21@gmail.com](mailto:m.argareksapati21@gmail.com)  
- 📷 Instagram: [@argareksapati](https://instagram.com/argareksapati)  
- 📱 WhatsApp: [6281818266692](https://wa.me/6281818266692)




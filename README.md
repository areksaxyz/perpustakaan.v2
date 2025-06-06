# Perpustakaan Project
Selamat datang di repositori Perpustakaan Digital! Aplikasi ini adalah sistem manajemen perpustakaan berbasis Java yang memungkinkan pengguna untuk mengelola buku digital dan fisik, peminjaman, katalog, denda, serta statistik perpustakaan. Proyek ini dibuat untuk memenuhi kebutuhan perpustakaan modern dengan antarmuka yang ramah pengguna.
# Fitur Utama
- Manajemen Buku: Tambah, hapus, dan kelola buku digital (dengan URL) dan buku fisik.
- Peminjaman Buku: Sistem peminjaman dengan status pengembalian dan manajemen denda otomatis.
- Katalog Buku: Katalog terpisah untuk buku digital dan fisik dengan fitur pencarian.
- Manajemen Denda: Pelacakan denda untuk peminjaman yang terlambat.
- Statistik Perpustakaan: Laporan dan statistik peminjaman buku.
- Antarmuka Pengguna: Desain modern menggunakan FlatLaf untuk pengalaman pengguna yang lebih baik.
# Penjelasan setiap panel
**1. Beranda**
   - Deskripsi: Panel Beranda adalah halaman utama yang memberikan gambaran umum tentang perpustakaan. Panel ini biasanya menampilkan informasi awal seperti jumlah buku, peminjaman terbaru, atau pesan selamat datang. Pengguna dapat menavigasi ke panel lain dari menu di sisi kiri.
![alt text](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/beranda.png?raw=true)
_Catatan: Gambar menunjukkan layout beranda dengan tombol navigasi di sisi kiri dan konten utama._

**2. Mode Baca**
- Deskripsi: Panel Mode Baca memungkinkan pengguna untuk membaca buku digital langsung dari aplikasi dengan membuka URL atau file PDF yang terkait. Fitur ini memberikan akses cepat ke konten buku tanpa perlu meninggalkan aplikasi.
![alt text](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/modebaca.png?raw=true)
![alt text](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/modebaca2.png?raw=true)
  _Catatan: Gambar menunjukkan antarmuka untuk membaca buku digital, seperti viewer PDF atau daftar buku yang dapat dibaca._

 **3. Buku Digital**
  - Deskripsi: Panel ini memungkinkan pengguna untuk menambah, mengedit, atau menghapus buku digital. Buku digital mencakup informasi seperti judul, penulis, tahun terbit, dan URL ke file PDF. Pengguna dapat memverifikasi buku yang tersedia untuk dipinjam.
![alt text](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/BukuDigital.png?raw=true)
_Catatan: Gambar menampilkan form untuk menambah buku digital dan daftar buku yang ada_

**4. Buku Fisik**
    - Deskripsi: Panel untuk mengelola buku fisik dengan fitur serupa seperti Buku Digital, tetapi tanpa URL PDF. Pengguna dapat menambahkan buku fisik dengan detail seperti judul, penulis, dan status ketersediaan.
![alt text](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/bukufisik.png?raw=true)
 _Catatan: Gambar menunjukkan daftar buku fisik dan opsi untuk menambah atau menghapus._

**5. Katalog Digital**
- Deskripsi: Panel ini menampilkan katalog buku digital yang tersedia, lengkap dengan fitur pencarian berdasarkan judul, penulis, atau kategori. Pengguna dapat melihat detail buku dan status peminjamannya.
![alt text](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/katalog.png?raw=true)
_Gambar menampilkan tabel katalog dengan kolom seperti judul dan status._

**6. Katalog Fisik**
- Deskripsi: Mirip dengan Katalog Digital, panel ini menampilkan daftar buku fisik yang tersedia dengan opsi pencarian. Panel ini membantu pengguna menemukan buku fisik yang dapat dipinjam.
![alt text](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/katalogfisik.png?raw=true)
_Catatan: Gambar menunjukkan tabel katalog fisik dengan fitur filter._

**7. Peminjaman**
- Deskripsi: Panel Peminjaman memungkinkan pengguna untuk meminjam buku fisik dengan mengisi form (nama peminjam, kelas, NIM). Terdapat tombol "Pinjam Buku", "Kembalikan" untuk mengembalikan buku, dan "Belum Dikembalikan" untuk menambahkan denda.
![alt text](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/peminjaman.png?raw=true)
 _Catatan: Gambar menampilkan form peminjaman dan tabel peminjaman dengan tombol aksi._

**8. Statistik**
- Deskripsi: Panel ini menampilkan laporan dan statistik peminjaman, seperti jumlah buku yang dipinjam, jumlah buku yang dikembalikan, dan denda yang terkumpul. Data disajikan dalam format yang mudah dibaca.
![alt text](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/riwayat.png?raw=true)
_Catatan: Gambar menunjukkan grafik atau tabel statistik peminjaman._

**9. Manajemen Denda**
- Deskripsi: Panel Manajemen Denda digunakan untuk melacak dan mengelola denda dari peminjaman yang terlambat. Pengguna dapat melihat daftar peminjam yang memiliki denda, jumlah denda, dan opsi untuk menghapus atau memperbarui denda.
![alt text](https://github.com/areksaxyz/perpustakaan.v2/blob/main/foto/manajemendenda.png?raw=true)
_Catatan: Gambar menampilkan tabel denda dengan detail peminjam dan jumlah denda._

# Teknologi yang Digunakan
- Bahasa Pemrograman: Java (JDK 24)
- GUI Framework: Swing dengan FlatLaf untuk tema modern
- Database: SQLite dengan JDBC (sqlite-jdbc-3.49.1.53)
# Dependensi Eksternal:
- FlatLaf 3.3 (untuk tema UI)
- SQLite JDBC 3.49.1.53 (untuk koneksi database)
- PDFBox 2.0.27 (untuk buku digital berformat PDF)
- Commons Logging 1.2 dan FontBox 2.0.27 (dependensi PDFBox) 
# Prasyarat
Sebelum menjalankan aplikasi, pastikan Anda memiliki:
- JDK 24 atau versi yang lebih baru (/opt/jdk-24.0.1 pada sistem Anda).
- Semua dependensi di folder lib/ (lihat daftar di atas).
- Sistem operasi yang mendukung Java (Windows, macOS, atau Linux).
# Instalasi
**1. Clone Repositori**
   
   git clone https://github.com/areksaxyz/perpustakaan.v2
   
   cd perpustakaan-digital
   
**2. Unduh Dependensi** (jika belum ada di folder lib/)
- [FlatLaf](https://mvnrepository.com/artifact/com.formdev/flatlaf/3.3)
- [SQLite JDBC](https://repo1.maven.org/maven2/org/xerial/sqlite-jdbc/3.49.1.0/sqlite-jdbc-3.49.1.0.jar)
- [PDFBox](https://mvnrepository.com/artifact/org.apache.pdfbox/pdfbox/2.0.27)
- [Commons Logging](https://mvnrepository.com/artifact/commons-logging/commons-logging/1.2)
- [FontBox](https://mvnrepository.com/artifact/org.apache.pdfbox/fontbox/2.0.27)
- Pastikan semua file .jar berada di folder lib/.

**3.Kompilasi kode**

javac -cp ".:lib/flatlaf-3.3.jar:lib/sqlite-jdbc-3.49.1.53.jar:lib/pdfbox-2.0.27.jar:lib/commons-logging-1.2.jar:lib/fontbox-2.0.27.jar" -d . src/model/*.java src/storage/*.java src/ui/*.java src/utils/*.java

**4. Jalankan Aplikasi**

/usr/bin/env /opt/jdk-24.0.1/bin/java --enable-native-access=ALL-UNNAMED -cp ".:lib/flatlaf-3.3.jar:lib/sqlite-jdbc-3.49.1.53.jar:lib/pdfbox-2.0.27.jar:lib/commons-logging-1.2.jar:lib/fontbox-2.0.27.jar" ui.LibraryUI

# Penggunaan
1. Beranda: Panel utama menampilkan gambaran umum perpustakaan.
2. Mode Baca: Akses dan baca buku digital langsung dari aplikasi.
3. Buku Digital/Fisik: Tambah atau hapus buku dari daftar.
4. Katalog: Cari buku berdasarkan judul, penulis, atau kategori.
5. Peminjaman: Pinjam buku fisik dengan mengisi form (nama, kelas, NIM).
- Tombol "Kembalikan" untuk mengembalikan buku.
- Tombol "Belum Dikembalikan" untuk menambahkan denda.
6. Manajemen Denda: Lihat dan kelola denda peminjaman yang terlambat.
7. Statistik: Lihat laporan peminjaman dan statistik perpustakaan.

# Kontak
Email: m.argareksapati21@gmail.com

Instagram: @argareksapati

Whatsapp: 6281818266692

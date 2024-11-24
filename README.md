# 💰 Aplikasi Keuangan Pribadi

Selamat datang di proyek ini! 🎉 Proyek ini adalah implementasi GUI berbasis Java untuk mengelola keuangan pribadi Anda, mencakup pencatatan pemasukan, pengeluaran, dan analisis keuangan sederhana, dengan fitur impor/ekspor data dalam format CSV.

---

## 👨‍💻 Tentang Saya

Halo! Nama saya **Nur Yoga Andika** 👋  
- 📚 **NPM:** 2210010652  
- 🎓 **Jurusan:** Teknologi Informasi  
- 🌟 Saya selalu berusaha belajar hal-hal baru dan berbagi apa yang saya pelajari.  

💬 Jangan ragu untuk menghubungi saya untuk berdiskusi lebih lanjut tentang proyek ini atau topik lainnya! 🚀  

---

## 📝 Deskripsi Program

Aplikasi ini memungkinkan pengguna:

- **Mencatat Transaksi:**
  - Pemasukan dan pengeluaran.
  - Menambahkan keterangan transaksi.
  - Menentukan tanggal transaksi.
- **Mengimpor dan Mengekspor Data:**
  - Data keuangan dapat diekspor ke file CSV.
  - Data CSV dapat diimpor kembali ke aplikasi.
- **Menghapus dan Mengedit Data:**
  - Fitur untuk menghapus transaksi dengan opsi undo.
  - Memodifikasi data transaksi yang sudah tercatat.
- **Melakukan Pencarian:**
  - Memudahkan pengguna mencari data tertentu berdasarkan kata kunci.
- **Analisis Keuangan:**
  - Menampilkan total pemasukan, pengeluaran, dan rata-rata keuangan.

Aplikasi ini juga menyediakan validasi otomatis untuk memastikan data yang dimasukkan sesuai dengan format yang diharapkan.

---

## 💻 Komponen GUI

Berikut adalah komponen utama yang digunakan dalam aplikasi ini:

- **JFrame:** Sebagai jendela utama aplikasi.
- **JPanel:** Mengatur tata letak komponen GUI.
- **JLabel:** Menampilkan label teks.
- **JTextField:** Untuk memasukkan nominal atau kata kunci pencarian.
- **JTable:** Menampilkan data transaksi dalam bentuk tabel.
- **JComboBox:** Untuk memilih kategori transaksi (pemasukan atau pengeluaran).
- **JDateChooser:** Memilih tanggal transaksi.
- **JButton:** Untuk tindakan seperti menambah, menghapus, mengubah data, impor/ekspor CSV, dan pencarian.

---

## 🔍 Logika Program

### **Manajemen Transaksi:**
- **Tambah Transaksi:** Data seperti kategori, nominal, tanggal, dan keterangan ditambahkan ke tabel.
- **Hapus Transaksi:** Data yang dipilih dapat dihapus, dengan opsi undo untuk membatalkan penghapusan.
- **Edit Transaksi:** Memodifikasi data yang sudah ada di tabel.

### **Impor/Ekspor CSV:**
- **Ekspor:** Semua data dalam tabel disimpan ke file CSV.
- **Impor:** Data dari file CSV dimasukkan ke tabel.

### **Validasi Input:**
- Nominal hanya boleh berupa angka.
- Tanggal tidak boleh melebihi tanggal saat ini.

### **Analisis Keuangan:**
- Menghitung total pemasukan dan pengeluaran.
- Menghitung rata-rata pemasukan dan pengeluaran.

### **Pencarian:**
- Mencari data tertentu di tabel berdasarkan kata kunci.

---

## 🎯 Events yang Diimplementasikan

### **ActionListener:**
- Menangani tombol:
  - **Tambah:** Menambahkan transaksi baru ke tabel.
  - **Hapus:** Menghapus transaksi yang dipilih.
  - **Undo:** Mengembalikan transaksi yang dihapus.
  - **Ekspor:** Menyimpan data ke CSV.
  - **Impor:** Membaca data dari CSV.
  - **Cari:** Mencari data dalam tabel berdasarkan kata kunci.

### **KeyAdapter:**
- Membatasi input di `JTextField` agar hanya angka yang bisa dimasukkan.

---

## ✨ Fitur Tambahan

1. **Undo Hapus:**
   - Transaksi yang terhapus dapat dikembalikan dengan mudah.
2. **Validasi Input:**
   - Memberikan peringatan jika nominal bukan angka.
   - Memberikan peringatan jika tanggal transaksi melebihi hari ini.
3. **Analisis Keuangan:**
   - Menampilkan total pemasukan dan pengeluaran secara real-time.
   - Menampilkan rata-rata pemasukan dan pengeluaran.
4. **Debugging:**
   - Menampilkan log di konsol untuk memantau proses impor dan validasi data.

---

## 🔧 Cara Menggunakan Program

1. **Masukkan informasi transaksi:**
   - Pilih kategori (pemasukan/pengeluaran).
   - Masukkan nominal.
   - Pilih tanggal transaksi.
   - Masukkan keterangan transaksi (opsional).

2. **Tekan tombol:**
   - **Tambah:** Menambahkan transaksi ke tabel.
   - **Hapus:** Menghapus data transaksi yang dipilih di tabel.
   - **Undo:** Mengembalikan data yang telah dihapus.
   - **Ekspor:** Menyimpan data ke file CSV.
   - **Impor:** Membaca data dari file CSV.

3. **Untuk mencari transaksi:**
   - Masukkan kata kunci di kolom pencarian dan tekan tombol **Cari**.

4. **Analisis Keuangan:**
   - Analisis keuangan akan diperbarui secara otomatis saat data ditambahkan, dihapus, atau diubah.

---


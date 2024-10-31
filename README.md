# Aplikasi Penghitung Umur
 Latihan 2 - Adrian Akhmad Firdaus (2210010491)
---

# Deskripsi

Aplikasi ini merupakan program Java sederhana yang dirancang untuk menghitung umur pengguna berdasarkan tanggal lahir yang dipilih. Selain menampilkan umur dalam tahun, bulan, dan hari, aplikasi ini juga menyediakan informasi tambahan seperti hari ulang tahun berikutnya serta peristiwa penting pada tanggal lahir.

## Fitur Utama

1. **Hitung Umur**: Menghitung usia lengkap pengguna dalam tahun, bulan, dan hari.
2. **Hari Ulang Tahun Berikutnya**: Menampilkan tanggal ulang tahun berikutnya berdasarkan tanggal lahir yang dipilih.
3. **Peristiwa Penting**: Menggunakan API eksternal untuk menampilkan peristiwa penting yang terjadi pada hari tertentu.
4. **Terjemahan ke Bahasa Indonesia**: Menerjemahkan deskripsi peristiwa penting ke dalam Bahasa Indonesia.

## Komponen GUI

- **JFrame**: Jendela utama aplikasi.
- **JPanel**: Panel untuk menampung komponen lainnya.
- **JLabel**: Label teks.
- **JDateChooser**: Komponen untuk memilih tanggal lahir.
- **JButton**: Tombol untuk melakukan perhitungan umur.
- **JTextField**: Menampilkan hasil perhitungan umur dan informasi ulang tahun.

## Logika Program

- **Perhitungan Umur**: Menggunakan `LocalDate` untuk menghitung selisih waktu dan menentukan usia pengguna.
- **Event Handling**:
  - **ActionListener**: Mengaktifkan tombol "Hitung" untuk memproses tanggal yang dipilih.
  - **PropertyChangeListener**: Mendeteksi perubahan pada JDateChooser untuk memperbarui informasi ulang tahun.

## Instalasi

1. **Clone Repository**
   ```bash
   git clone https://github.com/adrianiaan/AplikasiPenghitungUmur.git
   ```

2. **Unduh dan Tambahkan Library**
   - [JCalendar](https://toedter.com/jcalendar/): Unduh `jcalendar-1.4.jar` dan tambahkan ke folder `lib`.
   - [JSON-Java](https://github.com/stleary/JSON-java): Unduh `json-20240303.jar` dan tambahkan ke folder `lib`.

## Cara Penggunaan

1. **Menjalankan Aplikasi**:
   - Buka project di NetBeans.
   - Jalankan file `PenghitungUmurFrame.java`.

2. **Menghitung Umur**:
   - Pilih tanggal lahir menggunakan JDateChooser.
   - Klik tombol **Hitung Umur** untuk menampilkan umur dan hari ulang tahun berikutnya.

3. **Menampilkan Peristiwa Penting**:
   - Klik tombol **Hitung Umur** untuk menampilkan daftar peristiwa penting yang terjadi pada tanggal lahir.

## Tampilan Aplikasi Penghitung Umur (Saat Dijalankan)
![Tampilan Aplikasi Pada Saat Dijalankan](https://github.com/user-attachments/assets/ef271e88-db19-4bb0-8397-0206b029b2bb)

---
## Indikator Penilaian

| No  | Komponen           | Persentase |
|-----|---------------------|------------|
| 1   | Komponen GUI       | 10%        |
| 2   | Logika Program     | 10%        |
| 3   | Events             | 20%        |
| 4   | Kesesuaian UI      | 10%        |
| 5   | Memenuhi Variasi   | 50%        |
| **TOTAL** |               | **100%**   |

--- 
## Pembuat

Nama: Adrian Akhmad Firdaus

NPM: 2210010491

Kelas: 5A Reguler Pagi

Tugas : Latihan 2 Aplikasi Penghitung Umur

Fakultas : Fakultas Teknologi Informasi (FTI)

Unversitas : Universitas Islam Kalimantan Muhammad Arsyad Al Banjari Banjarmasin

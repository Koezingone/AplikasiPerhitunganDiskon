# Aplikasi Perhitungan Diskon

**Aplikasi Perhitungan Diskon** adalah aplikasi Java yang membantu pengguna menghitung harga akhir setelah diskon diberikan. Aplikasi ini memungkinkan pengguna untuk memasukkan harga asli, memilih persentase diskon, serta menambahkan kode voucher diskon tambahan untuk penghematan ekstra.

## Fitur Aplikasi

- Menghitung harga akhir setelah diskon
- Menampilkan jumlah penghematan dari diskon yang diterapkan
- Opsi tambahan untuk memasukkan kode kupon untuk diskon tambahan
- Validasi input untuk memastikan hanya angka yang dapat dimasukkan pada harga asli
- Riwayat perhitungan diskon sebelumnya yang telah dilakukan

## Komponen Utama

- **JFrame, JPanel, JLabel, JTextField, JComboBox, JButton, JTextArea, JSlider** untuk membuat antarmuka pengguna yang interaktif.
- **ActionListener** pada tombol "Hitung" untuk memproses perhitungan diskon.
- **ItemListener** pada `JComboBox` dan `JSlider` untuk memilih persentase diskon.
- Penanganan **Exception** untuk menangani kesalahan input pada harga asli.

## Cara Menggunakan

1. Masukkan harga asli produk pada field yang disediakan.
2. Pilih persentase diskon menggunakan `JComboBox` atau `JSlider`.
3. (Opsional) Masukkan kode kupon diskon pada field yang disediakan. Kode kupon yang tersedia saat ini, misalnya, adalah:
   - **DISKON10** - memberikan tambahan diskon 10%
   - **DISKON20** - memberikan tambahan diskon 20%
   - **DISKON30** - memberikan tambahan diskon 30%
   - **ILHAM** - memberikan tambahan diskon 50%
4. Klik tombol "HITUNG" untuk melihat harga akhir dan jumlah penghematan.
5. Riwayat perhitungan diskon akan ditampilkan di bawah hasil.

## Authors

- **Khairul Ilham** - 2210010082 - 5C REG BANJARMASIN

## Screenshots

![App Screenshot](https://github.com/Koezingone/AplikasiPerhitunganDiskon/blob/main/img/perhitunganDiskon.gif)

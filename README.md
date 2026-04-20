# Labuan Bajo Luxury Trip Booking System

## Deskripsi
Aplikasi berbasis web untuk pemesanan trip kapal wisata di Labuan Bajo.  
Sistem ini memungkinkan pengguna untuk melihat paket trip, melakukan booking, mendapatkan informasi pembayaran, serta konfirmasi melalui WhatsApp.

---

## Tujuan Sistem
Membangun sistem reservasi trip kapal yang:
- Mudah digunakan
- Responsif (mobile friendly)
- Mendukung proses booking hingga pembayaran

---

## Aktor
- User / Pelanggan

---

## Fitur Utama

| No | Fitur | Deskripsi |
|----|------|----------|
| 1 | Melihat Trip | User dapat melihat daftar paket trip |
| 2 | Detail Trip | Menampilkan detail paket dalam bentuk modal |
| 3 | Booking Trip | Mengisi form pemesanan |
| 4 | Validasi Form | Sistem memvalidasi input user |
| 5 | Pembayaran | Menampilkan Virtual Account & QR (simulasi QRIS) |
| 6 | Konfirmasi WhatsApp | Mengirim data booking ke WhatsApp |
| 7 | Dark Mode | Tampilan mode gelap |

---

## Use Case yang Diimplementasikan
- Mencari Trip
- Melihat Detail Trip
- Memesan Trip
- Melakukan Pembayaran
- Konfirmasi Pembayaran

---

## Teknologi
- HTML
- Tailwind CSS
- JavaScript
- Font Awesome
- QR Code API (simulasi)

---

## Pengujian Sistem

Pengujian dilakukan untuk memastikan setiap fitur berjalan dengan baik.

### Tabel Pengujian

| No | Fitur | Skenario Pengujian | Input | Output yang Diharapkan | Hasil |
|----|------|------------------|------|------------------------|------|
| 1 | Booking | Semua data diisi benar | Data valid | Booking berhasil | ✅ Berhasil |
| 2 | Booking | Form kosong | Kosong | Muncul alert error | ✅ Berhasil |
| 3 | Email | Format salah | "abc.com" | Ditolak sistem | ✅ Berhasil |
| 4 | No HP | Kurang dari 10 digit | "08123" | Ditolak sistem | ✅ Berhasil |
| 5 | Detail Trip | Klik tombol detail | - | Modal tampil | ✅ Berhasil |
| 6 | Pembayaran | Submit booking | Data valid | Modal pembayaran muncul | ✅ Berhasil |
| 7 | QR Code | Generate QR | - | QR tampil | ✅ Berhasil |
| 8 | WhatsApp | Klik konfirmasi | - | Redirect ke WhatsApp | ✅ Berhasil |
| 9 | Dark Mode | Klik toggle | - | Tema berubah | ✅ Berhasil |

---

## Catatan
- QRIS yang digunakan adalah simulasi menggunakan API QR Generator
- Sistem belum menggunakan database (masih prototype)

---

## Kesimpulan
Sistem berhasil memenuhi kebutuhan use case dan dapat digunakan sebagai prototype aplikasi booking trip kapal berbasis web.

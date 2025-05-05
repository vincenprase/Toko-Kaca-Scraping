# Toko-Kaca-Scraping

Proyek ini digunakan untuk mengambil data informasi toko kaca yang ada di wilayah Bogor menggunakan Google Places API (dengan Place ID) dan mengotomatisasinya dengan Google Apps Script, lalu menyimpan hasilnya ke Google Sheets.

🔧 Fitur

Mengambil data detail dari Place ID (nama, alamat, rating, nomor telepon, jam operasional, dan lainnya).

Menyimpan hasil ke Google Sheets.

Otomatisasi pengambilan data lewat menu di spreadsheet.

📜 Prasyarat
Akun Google

API Key Google Maps Platform dengan akses ke Places API

Spreadsheet Google aktif

Place ID dari toko-toko kaca yang ingin diambil datanya

⚙️ Cara Menggunakan
1. Siapkan Google Sheet
Buat spreadsheet dengan tab bernama Places dengan format berikut:
| No | Place ID                     | Nama Toko (otomatis) | Alamat (otomatis) | Rating | Telepon | Jam Buka |

2. Aktifkan Google Places API
Masuk ke Google Cloud Console

Buat project baru / gunakan yang sudah ada.

Aktifkan Places API

Buat API Key dan salin

3. Tambahkan Apps Script
Di Google Spreadsheet, buka Extensions > Apps Script

Salin isi file Code.gs ke editor Apps Script

Ganti YOUR_API_KEY dengan API Key milikmu

Simpan dan beri nama proyeknya (misal: Scraping Toko Kaca)

4. Jalankan Fungsi
Jalankan fungsi getPlaceDetails() dari menu Apps Script atau buat menu custom seperti ini:




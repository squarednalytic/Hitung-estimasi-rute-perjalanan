Parameter Perhitungan Default:

    ⚡ Kecepatan Rata-rata: 60 km/jam
    ⛽ Konsumsi BBM: 15 km/liter

✨ Fitur
🗺️ Manajemen Rute

    ➕ Tambah kota dengan jarak, tipe, dan catatan
    ✏️ Edit informasi kota
    🗑️ Hapus kota dari rute
    🔀 Urutkan ulang kota (pindah ke atas/bawah)
    📋 Contoh data demo tersedia

📊 Statistik & Kalkulasi

    📍 Total jumlah kota
    🛣️ Total jarak tempuh (KM)
    ⏱️ Estimasi waktu perjalanan
    ⛽ Estimasi konsumsi BBM

🎨 Visualisasi

    📐 Tampilan Vertikal - Timeline rute dari atas ke bawah
    📏 Tampilan Horizontal - Visualisasi rute dari kiri ke kanan
    📈 Progress Bar - Menampilkan progress perjalanan

💾 Penyimpanan Data

    💻 Data tersimpan di Local Storage browser
    ⏰ Data bertahan selama 11 hari
    📤 Export data ke format JSON
    
🎯 Tipe Kota
    Tipe	Deskripsi	Warna
    🟢 Start	Titik keberangkatan	Hijau
    🔵 Transit	Kota singgah/istirahat	Biru
    🔴 End	Tujuan akhir	Merah

📖 Penggunaan
   Menambah Kota Baru

1. Isi Nama Kota (wajib)
2. Masukkan Jarak dari kota sebelumnya dalam KM
3. Pilih Tipe Kota (Start/Transit/End)
4. Tambahkan Catatan jika diperlukan (opsional)
5. Klik tombol "Tambah Kota"

Mengedit Kota

1. Klik ikon ✏️ pada kota yang ingin diedit
2. Ubah informasi di modal yang muncul
3. Klik "Simpan"

Mengubah Urutan Kota

 • Klik ⬆️ untuk memindahkan kota ke atas
 • Klik ⬇️ untuk memindahkan kota ke bawah

Export Data

1.  Klik tombol "Export"
2.  File JSON akan otomatis terunduh
3.  Format nama file: journey-route-YYYY-MM-DD.json

Memuat Contoh Data

 • Klik tombol "Contoh Data" untuk melihat demo

🚀 Instalasi
Metode 1: Download Langsung
# Clone repository
git clone https://github.com/username/Hitung-estimasi-rute-perjalanan.git

# Masuk ke direktori
cd journey-route-tracker

# Buka file HTML di browser
open index.html

Metode 2: Single File

  • Salin seluruh kode HTML
  • Simpan sebagai index.html
  • Buka file dengan browser
  
Metode 3: Live Server (VS Code)
# Install extension Live Server di VS Code
# Klik kanan pada index.html → "Open with Live Server"

 🔧 Konfigurasi
Mengubah Parameter Default

Edit konstanta berikut di bagian JavaScript:

const MAX_DAYS = 11;           // Durasi penyimpanan data (hari)
const AVG_SPEED = 60;          // Kecepatan rata-rata (km/jam)
const FUEL_CONSUMPTION = 15;   // Konsumsi BBM (km/liter)

🤝 Kontribusi

Kontribusi sangat diterima! Silakan:

 1. Fork repository ini
 2. Buat branch fitur baru (git checkout -b fitur-baru)
 3. Commit perubahan (git commit -m 'Menambah fitur baru')
 4. Push ke branch (git push origin fitur-baru)
 5. Buat Pull Request

📝 Changelog
v1.0.0 (2026)

    🎉 Rilis pertama
    ✅ Fitur CRUD kota
    ✅ Kalkulasi otomatis
    ✅ Visualisasi vertikal & horizontal
    ✅ Local storage persistence
    ✅ Export JSON
    ✅ Responsive design

⭐ Dukungan
Jika aplikasi ini bermanfaat, berikan ⭐ pada repository ini!

    


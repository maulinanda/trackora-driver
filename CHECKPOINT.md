📦 CHECKPOINT #3 — TrackORA Driver
Tanggal: 28 Juni 2026
Status Project: v3.4 — Multi surat jalan, check-in/out, integrasi Google Sheets, persistensi trip (reload aman), GPS tracking, QR scanner, offline queue. Siap uji lapangan.

🎯 Tujuan Webapp
TrackORA Driver — webapp untuk driver mencatat waktu mulai perjalanan (check-in) dan waktu tiba di tujuan (check-out) per surat jalan. Mendukung multi surat jalan dalam 1 trip. Check-out bebas tidak wajib urut. Data dikirim ke Google Sheets (DELIVERY_LOG) via Google Apps Script. Offline: data disimpan di localStorage, kirim saat online.

🧰 Tools & URL
Tools	Fungsi
GitHub	Repository & version control
GitHub Pages	Hosting live
Google Sheets	Database log (DELIVERY_LOG)
Google Apps Script	API endpoint POST
BarcodeDetector API	QR Scanner (bawaan Chrome)
Repo: https://github.com/maulinanda/trackora-driver

Live: https://maulinanda.github.io/trackora-driver/

API URL: https://script.google.com/macros/s/AKfycbx3yAbqIKIQxgCeFreOG1Rhrcuz60DDK3PSOe-DKQAjn2bL5jGIuZyP6tkP3qK4L-Ge/exec

📁 Struktur File
text
trackora-driver/
├── README.md
├── CHECKPOINT.md
└── index.html        ← HTML + CSS + JS (1 file)
📊 Google Sheets — DELIVERY_LOG
A	B	C	D	E	F	G
SJKB	Waktu Check In	GPS Check In	Waktu Check Out	GPS Check Out	Status Kirim	Timestamp Server
📱 Fitur
Fitur	Status
📷 QR Scanner (BarcodeDetector API)	✅
📝 Input No. Surat Jalan satu per satu	✅
➕ Tambah surat jalan ke daftar	✅
🗑️ Hapus surat jalan dari daftar	✅
🚫 Cegah duplikat surat jalan	✅
📋 Daftar surat jalan sebelum trip	✅
▶️ "Mulai Perjalanan" check-in semua sekaligus	✅
🏁 Check-out per surat jalan (bebas urutan)	✅
⚠️ Konfirmasi dialog sebelum check-out	✅
🎉 Notifikasi trip selesai	✅
📡 GPS Tracking (check-in & check-out)	✅
📋 Riwayat pengiriman hari ini	✅
💾 localStorage (offline)	✅
🔄 Persistensi trip (reload aman)	✅
🌐 Indikator Online/Offline	✅
📡 Kirim check-in ke Google Sheets	✅
📡 Kirim check-out ke Google Sheets	✅
🟠 Pending queue untuk offline	✅
🔄 Tombol Sync untuk kirim ulang pending	✅
🌙 Dark mode	✅
📱 Responsive mobile	✅
🔢 Version badge (v3.4)	✅
🔜 Rencana Selanjutnya
TrackORA Web baca DELIVERY_LOG — tampilkan status Delivered di web tracking

Update Google Sheets db_Web — dari DELIVERY_LOG pakai formula/script

Foto bukti pengiriman — upload foto dengan watermark

Login driver — identitas driver tercatat

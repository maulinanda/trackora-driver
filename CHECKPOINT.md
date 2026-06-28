📦 CHECKPOINT #2 — TrackORA Driver
Tanggal: 28 Juni 2026
Status Project: MVP berfungsi penuh. Input surat jalan satu per satu (scan atau manual), daftar sebelum trip, check-in semua sekaligus, check-out bebas tidak urut, GPS tracking, riwayat lokal. Siap uji lapangan.

🎯 Tujuan Webapp
TrackORA Driver — webapp untuk driver mencatat waktu mulai perjalanan dan waktu tiba di tujuan. Mendukung multi surat jalan dalam 1 trip. Data disimpan lokal di HP driver (localStorage).

🧰 Tools & URL
Repo: https://github.com/maulinanda/trackora-driver

Live: https://maulinanda.github.io/trackora-driver/

📁 Struktur File
text
trackora-driver/
├── README.md
├── CHECKPOINT.md
└── index.html        ← HTML + CSS + JS (1 file)
📋 Fitur
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
📡 GPS Tracking (mulai & tiba)	✅
📋 Riwayat pengiriman hari ini	✅
💾 localStorage (offline)	✅
🌙 Dark mode	✅
📱 Responsive mobile	✅
🔢 Version badge (v3.1)	✅
✕ Reset form	✅
🔔 Notifikasi toast	✅
🔜 Rencana Selanjutnya
Integrasi dengan TrackORA Web — data waktu tiba dari driver masuk ke Google Sheets, lalu tampil di web tracking

Foto bukti pengiriman — upload foto dengan watermark

Login driver — identitas driver tercatat

Sinkronisasi otomatis — data terkirim ke server tanpa input manual


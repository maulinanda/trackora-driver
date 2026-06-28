📦 CHECKPOINT #1 — TrackORA Driver
Tanggal: 28 Juni 2026
Status Project: MVP berfungsi penuh. QR scanner via BarcodeDetector API, GPS tracking, check-in/out pengiriman. Siap uji lapangan.

🎯 Tujuan Webapp
TrackORA Driver — webapp untuk driver mencatat waktu mulai perjalanan dan waktu tiba di tujuan. Data disimpan lokal di HP driver (localStorage).

🧰 Tools & URL
Tools	Fungsi
GitHub	Repository & version control
GitHub Pages	Hosting live & publik
Repo: https://github.com/maulinanda/trackora-driver

Live: https://maulinanda.github.io/trackora-driver/

📁 Struktur File
text
trackora-driver/
├── README.md
└── index.html        ← HTML + CSS + JS (1 file)
📋 Fitur Saat Ini
Fitur	Status
📷 QR Scanner (BarcodeDetector API)	✅
📡 GPS Tracking	✅
▶️ Tombol "Mulai Perjalanan"	✅
🏁 Tombol "Tiba di Tujuan"	✅
📋 Riwayat pengiriman hari ini	✅
💾 localStorage (offline)	✅
🌙 Dark mode	✅
📱 Responsive mobile	✅
🔢 Version badge (v2.0)	✅
✕ Reset form	✅
🔔 Notifikasi toast	✅
🔜 Rencana Selanjutnya
Integrasi dengan TrackORA Web — data waktu tiba dari driver masuk ke Google Sheets

Foto bukti pengiriman — upload foto dengan watermark

Scan Surat Jalan — QR code berisi No. Surat Jalan

Multi unit dalam 1 surat jalan — daftar unit yang diantar

Login driver — identitas driver tercatat


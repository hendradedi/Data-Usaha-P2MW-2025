# 📊 Dashboard P2MW — Produk Usaha Mahasiswa 2025

Dashboard interaktif data usaha mahasiswa peserta **Program Pembinaan Mahasiswa Wirausaha (P2MW)** — Dikti Kemdiktisaintek RI.

## ✨ Fitur Dashboard

- 📈 **Visualisasi interaktif** — Grafik kategori usaha, tahapan, institusi, platform penjualan
- 🔍 **Filter & pencarian** — Cari berdasarkan nama, kategori, institusi, tahapan, lokasi
- 📋 **Tabel data lengkap** — 260+ usaha mahasiswa dengan sorting
- 🏛️ **Detail setiap usaha** — Klik untuk lihat info lengkap (deskripsi, lokasi, NIB, kontak)
- 📱 **Responsif** — Bisa diakses dari HP dan desktop
- 🎨 **Tampilan elegan & profesional** — Desain soft green dengan tipografi modern

## 🚀 Akses Dashboard

🌐 **Live:** [https://hendradedi.github.io/Data-Usaha-P2MW-2025](https://hendradedi.github.io/Data-Usaha-P2MW-2025)

## 📁 Struktur Repo

```
📂 Data-Usaha-P2MW-2025/
├── 📄 index.html              # Dashboard utama
├── 📄 data.json               # Data terstruktur (untuk dashboard)
├── 📄 data_produk_p2mw.csv    # Data mentah format CSV
└── 📄 README.md               # Dokumentasi
```

## 📊 Data

| Item | Detail |
|------|--------|
| **Total Usaha** | 260 |
| **Perguruan Tinggi** | 170 |
| **Kota/Kabupaten** | 219 |
| **Kategori Usaha** | 6 (Makanan & Minuman, Industri Kreatif, Manufaktur, Jasa, Budidaya, Bisnis Digital) |
| **Sumber** | [p2mw.kemdiktisaintek.go.id/gerai](https://p2mw.kemdiktisaintek.go.id/gerai) |

## 🛠️ Cara Update Data

Jalankan script scraping:
```bash
python3 scripts/scrape_p2mw.py
python3 scripts/prepare_dashboard_data.py
```

---
*Dashboard by Sarinem 007 — Data diperbarui secara berkala*

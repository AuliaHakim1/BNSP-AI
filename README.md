# 🤖 Al-Driven Weekly Expense Report Workflow (n8n)

Halo! Nama saya **Muhammad Aulia Hakim Syahputra**. 

Repositori ini berisi dokumentasi dan *workflow* n8n untuk **Proyek Otomatisasi Laporan Keuangan Mingguan Berbasis AI**. Sistem ini dirancang untuk menarik data pengeluaran dari Google Sheets, memfilternya secara otomatis, lalu menggunakan Kecerdasan Buatan (LLM) untuk menganalisis kebiasaan belanja dan memberikan saran penghematan langsung ke Telegram.

## ✨ Fitur Utama
- **Automated Trigger**: Berjalan otomatis seminggu sekali (berbasis jadwal).
- **Data Filtering**: Skrip khusus untuk menyaring transaksi hanya dalam 7 hari terakhir.
- **AI Financial Advisor**: Menganalisis pola belanja dan memberikan 1 saran penghematan yang praktis dan relevan.
- **Instant Notification**: Mengirimkan hasil analisis AI langsung ke aplikasi Telegram.

## 🛠️ Alat yang Digunakan
- **n8n** (Platform Otomatisasi Workflow)
- **Google Sheets** (Database Pencatatan Keuangan)
- **OpenRouter / LLM** (Pemrosesan Bahasa Alami / AI)
- **Telegram Bot** (Pengiriman Pesan Output)

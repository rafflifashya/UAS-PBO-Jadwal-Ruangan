# Sistem Penjadwalan Kuliah & Deteksi Bentrok

Proyek ini adalah implementasi sistem manajemen jadwal perkuliahan yang fokus pada **Constraint Satisfaction** dan **Design Pattern (Observer)**. Dibuat untuk memenuhi tugas UAS Modul Jadwal & Ruangan.

**Nama:** Raffli Islami Fashya  
**NIM:** 24360003  

## Fitur Utama
- **3D Conflict Detection**: Mendeteksi bentrok berdasarkan hari, jam (overlap), ruangan, dan dosen.
- **Observer Pattern**: Menggunakan model Publisher-Subscriber untuk mensimulasikan pengiriman notifikasi ke stakeholder (Mahasiswa & Dosen).
- **KRS Integration**: Fitur validasi kapasitas agar tidak ada kelas yang melebihi kapasitas ruangan.
- **AI Rescheduling**: Rekomendasi jadwal alternatif otomatis untuk admin.

## Tech Stack
- **Framework**: FastAPI
- **Language**: Python 3.12
- **Logic**: Datetime math for interval overlap checking

## Sequence Diagram
Diagram ini menunjukkan alur notifikasi saat jadwal berhasil dibuat:
[Tempel Gambar Mermaid kamu di sini]

## Cara Menjalankan
1. Clone repository ini.
2. Install dependencies:
   ```bash
   pip install fastapi uvicorn

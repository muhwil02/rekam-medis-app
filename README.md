# MediCare RME - Sistem Informasi Rekam Medis Elektronik (RME)

Aplikasi Web Rekam Medis Elektronik modern, cepat, dan responsif yang dibangun menggunakan **JavaScript (React 18)**, **Tailwind CSS**, dan **Lucide Icons** dengan antarmuka berbahasa Indonesia dan standar operasional Faskes Kemenkes RI (SOAP).

---

## 🌟 Fitur Utama

1. **Dashboard & Analitik Medis**
   - Statistik real-time: Total Pasien, Berkas Rekam Medis, Antrean Menunggu, dan Pasien Selesai.
   - Grafik tren kunjungan pasien 7 hari terakhir.
   - 5 besar diagnosa penyakit terbanyak (ICD-10) di klinik.
   - Pemantauan stok obat kritis & antrean aktif.

2. **Format Standar SOAP (Subjektif, Objektif, Asesmen, Plan)**
   - **S (Subjektif)**: Keluhan Utama, Riwayat Penyakit Sekarang (RPS), Riwayat Alergi Pasien.
   - **O (Objektif)**: Tanda-Tanda Vital (TTV lengkap: Tekanan Darah, Nadi, Napas, Suhu, SpO2, BB, TB), perhitungan IMT otomatis & interpretasi gizi, serta catatan pemeriksaan fisik.
   - **A (Asesmen)**: Diagnosa Utama dengan referensi kode ICD-10 resmi Indonesia, diagnosa sekunder, dan catatan diferensial klinis.
   - **P (Plan)**: Resep Obat Elektronik (e-Resep), tindakan medis yang diberikan, edukasi dokter, dan jadwal kontrol pasien.

3. **Manajemen Data Pasien Terpadu**
   - Registrasi pasien baru dengan penomoran No. Rekam Medis otomatis (contoh: `RM-2026-0001`).
   - Pencarian instan berdasarkan Nama, NIK, No. RM, atau Nomor Telepon.
   - Peringatan khusus bahaya alergi pasien (Allergy Safety Alert).
   - Lembar riwayat rekam jejak medis per pasien (Medical Dossier Timeline).

4. **Papan Antrean Poliklinik Real-Time**
   - Manajemen antrean per poli (Poli Umum, Poli Gigi, Poli Anak, Poli Penyakit Dalam, Poli KIA).
   - Tombol pemanggilan suara elektronik & nada dering lonceng (Web Audio & Speech Synthesis Bahasa Indonesia).
   - Integrasi 1-klik dari antrean langsung membuka formulir pemeriksaan SOAP.

5. **Cetak Resume Medis & Resep Resmi (Print / PDF)**
   - Format standar dokumen resmi klinik lengkap dengan kop faskes, stempel, rincian SOAP, salinan resep dokter (R/), dan tanda tangan digital.

6. **Farmasi & Apotek Mini**
   - Katalog obat klinik, bentuk sediaan, petunjuk pakai (signa), dan pemantauan stok menipis.

7. **Kalkulator Medis Klinis**
   - Kalkulator IMT & Berat Badan Ideal (Rumus Broca Kemenkes).
   - Kalkulator Dosis Obat Pediatrik (Anak) berdasarkan Berat Badan & Sirup.
   - Kalkulator HPL & Usia Kehamilan (Rumus Naegele).

8. **Penyimpanan Data Persisten & Ekspor**
   - Data otomatis tersimpan di `localStorage` peramban.
   - Fitur Ekspor Data ke JSON (Backup) & Reset Data ke bawaan demo.

---

## 🚀 Cara Menjalankan

Aplikasi saat ini sudah berjalan pada URL lokal:
```text
http://localhost:5173/
```

Jika ingin menjalankan secara manual:
```bash
# Pastikan berada di direktori aplikasi
cd C:\Users\vincent\.gemini\antigravity\scratch\rekam-medis-app

# Jalankan server pengembangan
npm run dev
```

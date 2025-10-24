# MindMonitor  
### *System Monitoring Kesehatan Mental Mahasiswa Terintegrasi Melalui Smartwatch*  

---

## Deskripsi Proyek  

**MindMonitor** adalah sistem pemantauan kesehatan mental mahasiswa berbasis **smartwatch** yang terintegrasi dengan **kecerdasan buatan (AI)**.  
Sistem ini merekam data fisiologis seperti **detak jantung**, **pola tidur**, dan **aktivitas fisik**, kemudian menggabungkannya dengan catatan emosional pengguna untuk memberikan **analisis personal**, **deteksi dini stres**, dan **rekomendasi perbaikan kondisi mental**.  

Proyek ini dikembangkan sebagai bagian dari tugas besar mata kuliah **Desain Interaksi** di **Institut Teknologi Sumatera (ITERA)** tahun 2025.

---

## Tujuan  
- Membantu mahasiswa mengenali kondisi kesehatan mental sejak dini.  
- Menyediakan analisis berbasis data dan AI terhadap indikator stres dan kesejahteraan mental.  
- Meningkatkan kesadaran akan pentingnya kesehatan mental di lingkungan kampus.  

---

## Fitur Utama  
✅ Pemantauan real-time data fisiologis (HR, HRV, tidur, aktivitas).  
✅ Analisis kondisi mental menggunakan model kecerdasan buatan.  
✅ Dashboard visual interaktif untuk pengguna.  
✅ Peringatan otomatis ketika stres terdeteksi tinggi.  
✅ Sinkronisasi smartwatch dengan aplikasi mobile.  
✅ (Opsional) Akses data anonim bagi konselor kampus.  

---

## Arsitektur Sistem  

MindMonitor terdiri dari tiga komponen utama:

### 1. 🕐 Smartwatch (Client Sensor Layer)  
Mengumpulkan data fisiologis mahasiswa seperti:  
- Detak jantung (Heart Rate)  
- Variabilitas detak jantung (HRV)  
- Tingkat aktivitas  
- Pola tidur  

### 2. ☁️ MindMonitor Cloud System (Processing & AI Layer)  
- Menerima data dari smartwatch  
- Menganalisis dengan model AI untuk mendeteksi stres dan kelelahan mental  
- Menghasilkan skor *mental well-being*  

### 3. 📱 Dashboard & Notification System (User Interaction Layer)  
- Menampilkan insight visual berupa grafik stres harian dan saran relaksasi  
- Memberikan notifikasi langsung ke smartwatch  
- Menyediakan akses tambahan bagi konselor dengan izin pengguna  

---

## Metodologi Desain  

MindMonitor dikembangkan dengan tiga pendekatan utama desain produk digital:

### 🔹 User-Centered Design (UCD)  
- *Identify Requirements:* Identifikasi kebutuhan pengguna melalui wawancara & survei.  
- *Design Prototype:* Pembuatan wireframe, mockup, dan tampilan interaktif.  
- *Build Interactive Version:* Implementasi sistem berbasis integrasi smartwatch.  
- *Evaluate & Feedback:* Pengujian usability dengan feedback iteratif pengguna.  

### 🔹 Double Diamond Framework  
1. **Discover:** Eksplorasi masalah dan kebutuhan pengguna.  
2. **Define:** Penentuan fitur penting dan alur interaksi.  
3. **Develop:** Pembuatan prototype dan pengujian awal.  
4. **Deliver:** Penyempurnaan desain hingga produk siap diuji pengguna.  

### 🔹 Lean UX  
Pendekatan *Think – Make – Check* untuk validasi cepat dan efisien berdasarkan hipotesis serta masukan pengguna.  

---

## Alur Pengguna (User Flow & Task Flow)  

1. Pengguna **login** ke aplikasi MindMonitor.  
2. Smartwatch **mengirimkan data fisiologis** ke sistem.  
3. Sistem **menganalisis data** menggunakan AI.  
4. Dashboard **menampilkan hasil analisis** berupa grafik dan insight.  
5. Pengguna **menerima notifikasi & rekomendasi** jika stres tinggi.  
6. Sistem **mengumpulkan feedback pengguna** untuk evaluasi model AI.  

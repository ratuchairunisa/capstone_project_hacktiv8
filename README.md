# capstone_project_hacktiv8
Repository ini berisi Proyek Capstone HACKTIV8 tentang Klasifikasi dan Rangkuman Data Menggunakan Inisiatif Pengembangan Mahasiswa menggunakan  IBM Granite.

---

# Analysis Drug Approval Status & Side Effects

## 📌 Project Overview
Proyek ini bertujuan untuk menganalisis faktor-faktor yang mempengaruhi **approval status** obat dan pola **efek samping** yang dilaporkan, dengan memanfaatkan data publik dan teknik **machine learning**.  
Analisis ini tidak hanya fokus pada membangun model prediksi, tetapi juga memberikan **insight** dan **rekomendasi strategis** yang dapat digunakan oleh industri farmasi dan regulator dalam proses evaluasi obat.

Tujuan utama proyek:
1. Mengidentifikasi faktor yang paling berpengaruh terhadap status persetujuan obat.
2. Menganalisis hubungan antara karakteristik obat dan pola efek samping.
3. Memberikan rekomendasi strategis untuk optimasi proses persetujuan dan pemantauan efek samping.
4. Memanfaatkan dukungan **(IBM Granite)** untuk menghasilkan insight berbasis teks yang komprehensif.

---

## 📂 Raw Dataset
Dataset yang digunakan dapat diakses melalui:  
[Drug Labels and Side Effects Dataset (Kaggle)](https://www.kaggle.com/datasets/pratyushpuri/drug-labels-and-side-effects-dataset-1400-records)  

---

## 📊 Insight & Findings

### Bagian 1: Analisis Approval Status
Berdasarkan model **GradientBoosting** (F1-score rata-rata: 0.39), ditemukan bahwa beberapa faktor berpotensi besar mempengaruhi status approval:

1. **Manufacturer** – Beberapa perusahaan manufaktur memiliki tingkat approval lebih tinggi.
2. **Approval Year** – Perbedaan waktu approval dapat mengindikasikan perubahan kebijakan atau proses.
3. **Drug Class** – Kelas obat tertentu lebih sering disetujui.
4. **Dosage (mg)** – Dosis tertentu lebih cenderung disetujui.
5. **Price (USD)** – Harga obat yang lebih tinggi memiliki korelasi dengan tingkat approval yang lebih baik.
6. **Side Effect Severity & Count** – Efek samping lebih ringan dan jumlah efek samping yang lebih sedikit meningkatkan peluang approval.

**Rekomendasi Strategis:**
- **Data Collection:** Kumpulkan data tambahan, termasuk waktu proses approval.
- **Feature Engineering:** Buat fitur baru seperti jumlah revisi dokumen.
- **Model Tuning:** Optimasi parameter atau gunakan model alternatif.
- **Collaboration:** Bekerja sama dengan regulator untuk memahami kriteria approval.

---

### Bagian 2: Analisis Efek Samping
Efek samping yang perlu perhatian lebih:
- *Blurred vision, Dry mouth, Headache, Rash, Diarrhea, Fatigue, Dizziness, Insomnia, Nausea, Constipation.*

**Saran Studi & Pemantauan:**
- Lakukan **farmakovigilans** untuk mengidentifikasi kelompok berisiko tinggi.
- Perbarui sistem pengaduan pasien untuk deteksi pola efek samping.
- Gunakan prediksi data untuk identifikasi risiko.

**Rekomendasi Komunikasi Risiko:**
- Informasikan risiko efek samping pada label dan materi edukasi.
- Kolaborasi dengan regulator untuk program post-approval monitoring.

**Kaitan dengan Fitur Lain:**
- **Drug Class** – Efek samping tertentu dominan di kelas obat tertentu.
- **Dosage** – Dosis tertentu terkait efek samping spesifik.
- **Manufacturer** – Produsen tertentu memiliki kecenderungan efek samping lebih sering.

**Usulan Validasi:**
- Studi klinis lebih dalam.
- Analisis data post-approval.
- Validasi model prediksi efek samping.
- Kolaborasi dengan regulator untuk standarisasi data.

---

## 🤖 AI Support Explanation
Analisis insight dan rekomendasi teks di atas dihasilkan dengan dukungan sebuah model dari **IBM Granite** yang mampu:
- Menggabungkan hasil analisis numerik dan statistik menjadi insight yang mudah dipahami.
- Memberikan rekomendasi strategis berbasis pola data.
- Menjelaskan hubungan antar variabel dalam bentuk narasi yang jelas.
- Mendukung proses **data storytelling** untuk laporan dan pengambilan keputusan.

---


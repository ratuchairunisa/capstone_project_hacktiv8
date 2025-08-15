# capstone_project_hacktiv8
Repository ini berisi Proyek Capstone HACKTIV8 Menggunakan Inisiatif Pengembangan Mahasiswa menggunakan IBM Granite.

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

### Berapa Banyak Distribusi Obat dengan Efek Samping yang Parah Beredar Berdasarkan Status Persetujuannya?

<img width="1038" height="590" alt="stacked bar chart" src="https://github.com/user-attachments/assets/dcda1878-cd82-46a1-9503-20817523a18a" />
Grafik di atas menunjukkan tingkat keparahan efek samping yang dikelompokkan menjadi 3 tingkat yaitu Mild (ringan), Moderate (sedang), dan Severe (Parah) berdasarkan status persetujuan yang dikelompokkan menjadi 3 kategori yaitu Approved (Disetujui), Pending (Menunggu), dan Rejected (Ditolak). Dari grafik tersebut bisa diketahui bahwa obat-obatan dengan status disetujui dan memiliki tingkat efek samping yang parah lebih sedikit, sementara obat-obatan dengan status pending (proses persetujuan) di semua tingkat keparahan memiliki angka lebih tinggi.

### Sebaran Jumlah Obat Approved Berdasarkan Efek Samping (side_effects)?

<img width="990" height="590" alt="bar chart side effect" src="https://github.com/user-attachments/assets/2b24ad70-31ff-4555-8a10-1a259c41efce" />
Diketahui bahwa obat yang telah disetujui paling sering mengalami efek samping headache (sakit kepala), diikuti oleh insomnia (susah tidur), dry mouth (mulut kering), dan seterusnya.

### Bagaimana Frekuensi Distribusi Indikasi Obat di Antara Pabrik (Produsen) dan TOP Indikasi Obat Berdasarkan Pabrik (Produsen)?

<img width="1582" height="990" alt="dist indikasi   top pbf based on indication" src="https://github.com/user-attachments/assets/a78e9fef-01b9-415b-b7db-3bf702653425" />
Grafik di atas memberikan dua informasi, yaitu:

  - Grafik "Distribusi Frekuensi Indikasi Obat" menunjukkan bahwa obat dengan indikasi "Depression treatrment (pengobatan depresi)" sangat banyak dikonsumsi.
  - Grafik "TOP Indikasi Menurut Pabrik (Produsen)" menunjukkan bahwa Pabrik Johnson & Johnson paling banyak diminati untuk indikasi "Inflammation reduction (pengobatan peradangan)".

### Produsen (Pabrik) Mana dengan Status Persetujuan 'Disetujui' lebih Tinggi?

<img width="655" height="383" alt="Screenshot 2025-08-15 174928" src="https://github.com/user-attachments/assets/d588a648-6eaf-41e3-9c16-2955d743ef7e" />

Manufactur (pabrik) yang paling sering mendapatkan status persetujuan adalah Johnson & Johnson

### Kelas Terapi Apa yang Paling Banyak Disetujui?

<img width="575" height="375" alt="Screenshot 2025-08-15 175038" src="https://github.com/user-attachments/assets/0732ec5b-6fc4-43cf-b96a-9288c0f28e5c" />

Kelas terapi yang paling banyak mendapatkan persetujuan adalah Anti-inflammatory (anti peradangan)

### Kondisi atau Penyakit Apa yang Paling Sering Mendapati Kontraindikasi Obat?

<img width="1181" height="790" alt="dist kontraindikasi" src="https://github.com/user-attachments/assets/eca5dca4-aa9d-4fc1-9a37-8919bd08893b" />

Grafik di atas menunjukkan bahwa penyakit Asma dan Kehamilan merupakan penyakit/kondisi yang sering mengalami kontraindikasi dengan kelas terapi obat yang berbeda menunjukkan profil keamanan yang bervariasi sesuai dengan mekanisme aksi mereka.

### Rute Pemakaian Apa yang Paling Banyak Digunakan Berdasarkan Kelas Terapinya?

<img width="1287" height="790" alt="rute pemakaian paling sering" src="https://github.com/user-attachments/assets/ed7348ec-4155-4ea7-aa93-fe2935fd4149" />

Heatmap di atas menunjukkan bahwa rute pemakaian Intramuscular -- yaitu pemberian obat atau zat melalui injeksi langsung ke dalam otot, banyak digunakan pada kelas terapi obat Antidepresant.

---

### 🤖 AI Support Explanation
Analisis insight dan rekomendasi di atas dihasilkan dengan dukungan model AI analitik lanjutan yang mampu:
- Mengintegrasikan temuan statistik, tren, dan visualisasi menjadi insight yang singkat namun tepat sasaran.
- Mengidentifikasi pola dan anomali dalam data, lalu menghubungkannya dengan konteks bisnis atau penelitian.
- Menyajikan rekomendasi berbasis data yang praktis untuk diimplementasikan.
- Memperkuat proses data storytelling dengan narasi yang relevan dan selaras dengan kesimpulan akhir, sehingga memudahkan pengambilan keputusan strategis.
  
---


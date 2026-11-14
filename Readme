# Dataset Putusan Perkara Narkotika — Pengadilan Negeri Jakarta Barat

## 1. Informasi Proyek

Repository ini dibuat untuk memenuhi tugas Ujian Tengah Semester (UTS) mata kuliah **Temu Kembali Informasi** di Universitas Muhammadiyah Malang.

Dataset berisi dokumen putusan pengadilan dalam kategori **Pidana Khusus → Narkotika dan Psikotropika** yang diperoleh dari Direktori Putusan Mahkamah Agung Republik Indonesia.

| Informasi | Keterangan |
|---|---|
| Nama repository | `Dataset-Narkotika_015_014` |
| Mata kuliah | Temu Kembali Informasi |
| Perguruan tinggi | Universitas Muhammadiyah Malang |
| Kategori perkara | Pidana Khusus — Narkotika dan Psikotropika |
| Lembaga peradilan | Pengadilan Negeri Jakarta Barat |
| Tahun putusan | 2025 |
| Jumlah dokumen | 50 PDF |
| Format ringkasan | Microsoft Excel (`.xlsx`) |

## 2. Anggota Kelompok

| No. | Nama | NIM |
|---:|---|---|
| 1 | Bukhary Kelian | 202310370311015 |
| 2 | Moch. Luqman Hakim | 202310370311014 |

## 3. Sumber Dataset

Dokumen diperoleh dari sumber berikut:

- **Direktori Putusan Mahkamah Agung Republik Indonesia:** https://putusan3.mahkamahagung.go.id/direktori.html

Pengumpulan dilakukan dengan memilih putusan dari Pengadilan Negeri Jakarta Barat, kategori Pidana Khusus, klasifikasi Narkotika dan Psikotropika, dengan tahun putusan 2025.

Kelompok melakukan pemeriksaan status putusan berdasarkan informasi yang tersedia pada direktori untuk mengecualikan putusan berstatus **BERKEKUATAN HUKUM TETAP**, sesuai ketentuan tugas.

## 4. Struktur Repository

Repository disusun dengan struktur direktori sebagai berikut:

```text
Dataset-Narkotika_015_014/
├── Dataset/
│   └── Narkotika.zip
├── Overview/
│   └── Overview.xlsx
└── README.md
```

Keterangan:

- **`Dataset/Narkotika.zip`**  
  Arsip ZIP yang berisi 50 dokumen putusan pengadilan dalam format PDF.

- **`Overview/Overview.xlsx`**  
  File ringkasan metadata untuk membantu identifikasi dan penelusuran dokumen putusan.

- **`README.md`**  
  Dokumentasi mengenai sumber, cakupan, struktur, dan keterbatasan dataset.

## 5. Struktur Metadata

File `Overview.xlsx` memiliki kolom-kolom berikut:

| Kolom | Deskripsi |
|---|---|
| `No` | Nomor urut dokumen dalam dataset. |
| `No Putusan` | Nomor resmi perkara atau putusan pengadilan. |
| `Lembaga Peradilan` | Pengadilan yang mengeluarkan putusan. |
| `Barang Bukti` | Ringkasan barang bukti yang tercantum dalam putusan. |
| `Amar Putusan` | Bagian putusan yang memuat pernyataan dan keputusan hakim. |

Metadata tersebut digunakan untuk mempermudah pencarian, identifikasi, dan pemilihan dokumen berdasarkan informasi pokoknya.

## 6. Proses Pengumpulan dan Pengolahan Data

Tahapan pengelolaan dataset meliputi:

1. **Penentuan kriteria.** Menetapkan kategori perkara, pengadilan, dan tahun putusan sesuai ketentuan tugas.
2. **Akuisisi dokumen.** Mengumpulkan dokumen putusan dari Direktori Putusan Mahkamah Agung RI.
3. **Pemeriksaan dokumen.** Memeriksa kesesuaian dokumen dengan kriteria dataset dan status putusannya.
4. **Ekstraksi informasi.** Mengambil informasi nomor putusan, lembaga peradilan, barang bukti, dan amar putusan dari dokumen.
5. **Penyusunan metadata.** Menempatkan informasi yang diperoleh ke dalam kolom `Overview.xlsx`.
6. **Pengorganisasian data.** Mengemas dokumen PDF ke dalam `Narkotika.zip` dan menyimpan file ringkasan pada direktori `Overview`.

Ekstraksi teks atau OCR dapat digunakan untuk membantu pembacaan dokumen, khususnya apabila PDF berupa hasil pemindaian. Hasil ekstraksi perlu diperiksa terhadap dokumen asli karena kesalahan pembacaan karakter, angka, nama, atau format teks masih mungkin terjadi.

## 7. Tujuan Penggunaan Dataset

Dataset ini disiapkan untuk mendukung pembelajaran dan eksperimen dalam bidang Temu Kembali Informasi (*Information Retrieval*), khususnya pada dokumen hukum.

Beberapa penggunaan yang relevan meliputi:

- Mempelajari struktur dan metadata dokumen putusan pengadilan.
- Melakukan prapemrosesan teks, seperti normalisasi, tokenisasi, dan penghapusan kata umum.
- Membangun indeks dokumen untuk mendukung pencarian informasi.
- Menerapkan metode pembobotan dan pemeringkatan dokumen.
- Mengevaluasi pencarian berdasarkan nomor putusan, barang bukti, atau isi amar putusan.

Penggunaan untuk eksperimen pencarian tetap memerlukan penyesuaian format teks dan pemeriksaan kualitas data sesuai kebutuhan masing-masing metode.

## 8. Keterbatasan Dataset

Dataset ini memiliki beberapa keterbatasan yang perlu diperhatikan:

1. **Cakupan terbatas.** Dataset hanya mencakup putusan dari Pengadilan Negeri Jakarta Barat pada tahun 2025 dalam kategori perkara yang ditentukan. Dataset tidak mewakili seluruh putusan narkotika di Indonesia.
2. **Ketergantungan pada dokumen sumber.** Kelengkapan dan kualitas informasi bergantung pada isi dokumen yang tersedia di Direktori Putusan Mahkamah Agung RI.
3. **Kemungkinan kesalahan ekstraksi.** Hasil OCR atau pengambilan teks otomatis dapat mengandung kesalahan. Angka berat barang bukti, nama, nomor perkara, dan amar putusan perlu dicocokkan dengan PDF asli.
4. **Ringkasan bukan pengganti dokumen lengkap.** Metadata pada `Overview.xlsx` hanya merangkum informasi tertentu. Untuk memahami konteks perkara secara menyeluruh, pembaca perlu merujuk pada PDF putusan terkait.
5. **Perubahan status perkara.** Status yang diperiksa pada saat pengumpulan tidak menjamin bahwa informasi status perkara akan selalu sama pada waktu berikutnya.

## 9. Referensi

Mahkamah Agung Republik Indonesia. **Direktori Putusan Mahkamah Agung RI.**

https://putusan3.mahkamahagung.go.id/direktori.html

## 10. Penutup

Repository ini disusun sebagai dataset pembelajaran untuk memahami akuisisi dokumen hukum, pengelolaan metadata, ekstraksi teks, dan penerapan teknik Temu Kembali Informasi.

Dataset beserta metadata pendukungnya diharapkan dapat membantu proses eksperimen pencarian dokumen putusan secara lebih terstruktur dan terdokumentasi.

---

**Dikembangkan oleh:**  
Bukhary Kelian dan Moch. Luqman Hakim  
Universitas Muhammadiyah Malang

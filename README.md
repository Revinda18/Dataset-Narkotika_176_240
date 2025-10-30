# Dataset Narkotika – Putusan Pengadilan Negeri Tangerang

> **Koleksi 62 dokumen putusan pengadilan terkait tindak pidana narkotika**, dikompilasi untuk tujuan penelitian hukum, analisis kebijakan, dan pembelajaran berbasis data.  
> Dibangun dengan semangat *open legal data* untuk mendukung transparansi hukum di Indonesia 🇮🇩.

---

##  Deskripsi Singkat

Repositori ini berisi **dataset putusan pengadilan** dalam perkara **pidana narkotika dan psikotropika**, yang diambil dari situs resmi **Mahkamah Agung Republik Indonesia**.

Dataset disusun dalam dua bagian utama:

| Folder | Deskripsi |
|---------|------------|
| 📁 `Dataset/Narkotika.zip` | Berisi 50 dokumen putusan dalam format **PDF** |
| 📄 `Overview/Overview.xlsx` | File **ringkasan metadata** dari seluruh putusan (62 entri data) |

---

## Struktur File `Overview.xlsx`

File **Overview.xlsx** menyimpan informasi penting dari setiap putusan dengan 5 kolom utama berikut:

| Kolom | Deskripsi |
|--------|------------|
| **No** | Nomor urut data putusan |
| **No Putusan** | Nomor resmi putusan (misal: `1942/Pid.Sus/2023/PN`) |
| **Lembaga Peradilan** | Nama lembaga peradilan (contoh: *Pengadilan Negeri Tangerang*) |
| **Barang Bukti** | Deskripsi barang bukti yang diajukan di persidangan |
| **Amar Putusan** | Ringkasan hasil putusan (misal: *terdakwa terbukti bersalah dan dijatuhi pidana penjara*) |

**Jumlah entri:** 62 data  
**Sumber dokumen:** Putusan Pengadilan Negeri Tangerang

---

## Contoh Cuplikan Data

| No | No Putusan | Lembaga Peradilan | Barang Bukti | Amar Putusan |
|----|-------------|------------------|---------------|---------------|
| 1 | 1942/Pid.Sus/2023/PN | Pengadilan Negeri Tangerang | yang diajukan di persidangan; Setelah mendengar... | perkara pidana dengan acara pemeriksaan biasa... |
| 2 | 1941/Pid.Sus/2023/PN | Pengadilan Negeri Tangerang | yang diajukan di persidangan; Setelah mendengar... | perkara pidana dengan acara pemeriksaan biasa... |
| 3 | 1940/Pid.Sus/2023/PN | Pengadilan Negeri Tangerang | yang diajukan di persidangan; Setelah mendengar... | perkara pidana dengan acara pemeriksaan biasa... |

---

## Tujuan Pembuatan Dataset

- Menyediakan **dataset hukum terbuka** untuk penelitian dan eksperimen AI hukum.  
- Mendukung pengembangan sistem **Legal Information Retrieval** dan **Text Classification**.  
- Menganalisis pola, pasal, dan amar putusan dalam kasus narkotika.  
- Memfasilitasi pembelajaran mahasiswa di bidang hukum, data science, dan kebijakan publik.

---

## Potensi Penggunaan

| Bidang | Deskripsi |
|---------|------------|
| *Case Retrieval* | Pencarian kasus serupa berdasarkan isi dokumen |
| *Text Classification* | Klasifikasi putusan berdasarkan jenis pelanggaran atau amar |
| *Named Entity Recognition* | Ekstraksi entitas seperti pasal, nama pengadilan, atau barang bukti |
| *Data Analytics* | Analisis statistik tren hukuman, jenis pelanggaran, dan putusan |

---

## Sumber Data

Semua dokumen diambil dari portal resmi:
> [https://putusan3.mahkamahagung.go.id](https://putusan3.mahkamahagung.go.id) --> PN Tangerang 

**Status Data:** Publik  
**Penggunaan:** Akademik dan non-komersial

---

##  Teknologi dan Format

| Jenis File | Format | Deskripsi |
|-------------|----------|------------|
| Dokumen | `.pdf` | Putusan pengadilan asli |
| Metadata | `.xlsx` | Ringkasan data dalam format Excel |
| Arsip | `.zip` | Kompresi seluruh dokumen PDF |

---

## Kontributor

| Nama | NIM 
|------|-----
| Revinda Visma Novatalia | 202210370311176
| Tantri Romadhoni Siswining Ndaru | 202210370311240

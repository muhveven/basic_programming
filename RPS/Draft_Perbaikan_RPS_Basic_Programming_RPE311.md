# Draf Perbaikan Rencana Pembelajaran Semester (RPS)
**Mata Kuliah:** Basic Programming (RPE311)
**Program Studi:** Teknologi Rekayasa Pembangkit Energi

Dokumen ini memuat draf perbaikan struktural untuk mengintegrasikan evaluasi akademik secara faktual pada paruh pertama (Pemrograman Dasar) dan paruh kedua (Analisis Data).

---

## 1. Perbaikan Bagian XI: Deskripsi Penilaian (Assignment Description)
Bobot penilaian berikut dirancang untuk mencerminkan beban kerja mahasiswa secara empiris:
* **Kuis (Q1, Q2, Q3):** 10%
* **Tugas Praktikum & Coding Practice (A1, A2, P1-P10):** 20%
* **Asesmen Tengah Semester (ATS / MSE):** 25%
* **Asesmen Akhir Semester (AAS / FSE):** 25%
* **Proyek Akhir & Presentasi (A3, A4, PP):** 20%

---

## 2. Perbaikan Bagian VII: Rencana Pembelajaran Mingguan (Integrasi Asesmen)
Penambahan spesifikasi asesmen pada kolom *Assessment Method*:

* **Minggu 3:** Pelaksanaan **Kuis 1 (Q1)**. Evaluasi pemahaman teoritis terkait tipe data, abstraksi data, dan ekspresi operator di lingkungan Python.
* **Minggu 5:** Penugasan **Tugas 1 (A1)**. Mahasiswa diinstruksikan untuk menyusun langkah-langkah arsitektur algoritma (*step-by-step*) secara deskriptif terlebih dahulu. Kasus difokuskan pada pemrosesan komputasi (contoh: kalkulasi faktorial) dengan spesifikasi bahwa skrip harus diatur sedemikian rupa agar hasil yang ditampilkan hanyalah nilai faktorial terakhir, tanpa memunculkan tahapan iterasi pada log keluaran.
* **Minggu 6:** Pelaksanaan **Kuis 2 (Q2)**. Evaluasi implementasi *array* sekuensial dan matriks multidimensi.
* **Minggu 8:** Pelaksanaan **Asesmen Tengah Semester (MSE)**. Ujian praktik yang difokuskan pada pencapaian CLO-1.
* **Minggu 11:** Penugasan **Tugas 2 (A2)**. Praktik *Data Wrangling* menggunakan set data mentah berformat CSV terkait parameter operasional turbin atau pembangkit listrik.
* **Minggu 12:** Pelaksanaan **Kuis 3 (Q3)**. Evaluasi identifikasi pola, anomali, serta analisis validitas dan etika privasi data.
* **Minggu 14:** Evaluasi presentasi Proyek Akhir (PP) berupa penyajian *dashboard* data.
* **Minggu Ujian Akhir:** Pelaksanaan **Asesmen Akhir Semester (FSE)**.

---

## 3. Spesifikasi Asesmen Tengah Semester (ATS / MSE) dan Asesmen Akhir Semester (AAS / FSE)

### Asesmen Tengah Semester (ATS)
* **Fokus:** Capaian Pembelajaran 1 (CLO-1).
* **Deskripsi Ujian:** Mahasiswa diberikan studi kasus operasional sistem teknik. Evaluasi ditekankan pada kemampuan merumuskan arsitektur penyelesaian masalah (*step-by-step* logis) yang mengutamakan pemahaman konseptual. Skrip Python kemudian disusun menggunakan struktur kontrol (*branching/looping*) dan subprogram untuk membuktikan kebenaran logika tersebut.

### Asesmen Akhir Semester (AAS)
* **Fokus:** Capaian Pembelajaran 2 hingga 6 (CLO-2 sampai CLO-6).
* **Deskripsi Ujian:** Evaluasi berbasis proyek (*Project-Based Learning*). Mahasiswa menganalisis dataset operasional mesin menggunakan pustaka Pandas, Matplotlib, dan Seaborn untuk *Exploratory Data Analysis* (EDA). 
* **Ketentuan Teknis Pelaporan:** Saat menyusun pelaporan statistik deskriptif dan probabilitas, formulasi dan notasi matematis harus diubah menjadi presentasi teks murni (tanpa memuat delimitasi sintaks matematis). Seluruh hasil observasi selanjutnya diintegrasikan ke dalam *dashboard* pelaporan interaktif menggunakan pustaka Streamlit.

---

## 4. Perbaikan Bagian X: Matriks Pemetaan Asesmen (Student Outcomes Assessment Plan)

Pemetaan faktual instrumen evaluasi terhadap beban minggu perkuliahan adalah sebagai berikut:

| SO-PI | Instrumen Asesmen (Minggu Ke-) |
| :--- | :--- |
| **A - (A.1)** | Q1 (M3), MSE (M8), Q3 (M12) |
| **A - (A.2)** | Q2 (M6), MSE (M8) |
| **B - (B.2)** | A1 (M5), A2 (M11), A3 (M13), A4 (M14), FSE |
| **D - (D.1)** | P1-P6 (M2-M7), MSE (M8), P7-P10 (M9-M12), FSE |
| **E - (E.1)** | P1-P6 (M2-M7), MSE (M8), P7-P10 (M9-M12), FSE |
| **H - (H.1)** | PP (M14), FSE |

*Catatan: Kode P1 hingga P10 di atas merepresentasikan evaluasi formatif berkelanjutan (*Coding Practice*) yang diobservasi rutin saat sesi praktikum mingguan berlangsung.*

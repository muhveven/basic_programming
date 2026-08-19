# No.FO.6.1.7-V1 Semester Lesson Plan (REVISI)
**19 Agustus 2026 — Draft Revisi oleh Muhammad Veven, S.Kom., M.Eng**

*Perubahan dari versi 07 Agustus 2023 ditandai `[REVISI]` atau `[BARU]`; struktur & format mengikuti template asli No.FO.6.1.7-V1.*

| | |
|---|---|
| **Study Program** | Power Plant Engineering Technology (Teknologi Rekayasa Pembangkit Energi) |
| **Course Code** | RPE311 |
| **Course Title** | Basic Programming (Dasar Pemrograman) |
| **Credits** | 3 |
| **Semester** | 3 |
| **Course Status** | Compulsory |
| **Prerequisite Course** | N/A |
| **Co-requisite** | N/A |
| **Lecturer** | Muhammad Veven, S. Kom., M. Eng |
| **Email** | veven@polibatam.ac.id |

---

## I. TERM DEFINITION

| Term | Definition |
|---|---|
| **Student Outcomes (SO)** | The specified knowledge, skills, abilities or attitudes that students are expected to attain by the end of a learning experience or program of study |
| **Performance Indicator (PI)** | Concrete measurable performances students must meet as indicators of achievement |
| **Course Learning Outcomes (CLOs)** | The specific and measurable statements that define the knowledge, skills, and attitudes learners will demonstrate by the completion of a course |

---

## II. COURSE DESCRIPTION

This course covers programming fundamentals (logic, data structures, algorithms) and the core concepts of data processing, analysis, and interpretation, applied throughout to the operational data of power generation and electrical power systems. Students will learn to apply the Python programming language to identify patterns and trends in energy-sector data, derive insights, and present findings in a clear format to support decision-making and problem-solving in power plant engineering.

> **[REVISI]** Penekanan eksplisit pada domain data pembangkit/energi ditambahkan agar konsisten dengan tujuan integrasi lintas program studi.

---

## III. COURSE GOAL

- Establish a Foundation in Computational Thinking
- Bridge Programming Theory with Real-World Power Plant & Energy Engineering Applications `[REVISI]`
- Develop Core Competency in the Data Analysis Lifecycle Using Energy-Sector Data `[REVISI]`
- Equip Skills in Data Storytelling and Visualization for Power Plant Performance Monitoring `[REVISI]`
- Foster Ethical and Critical Awareness in Handling Critical-Infrastructure (Energy) Data `[REVISI]`

---

## IV. STUDENT OUTCOMES (SOs) AND PERFORMANCE INDICATOR (PIs)

Tidak ada perubahan pada tabel SO-PI (Bagian IV) — mengikuti daftar SO A–K sesuai capaian pembelajaran lulusan program studi Teknologi Rekayasa Pembangkit Energi yang sudah ditetapkan (lihat dokumen RPS asli/kurikulum program studi). Perubahan pada RPS ini terfokus pada Bagian V ke bawah, di mana pemetaan CLO ke PI dikoreksi dan dilengkapi.

---

## V. COURSE LEARNING OUTCOMES (CLOs) `[REVISI]`

Upon completion of this course, the student will be able to:

| Code | Course Learning Outcomes | Related to SO-PI |
|---|---|---|
| **CLO-1** | Students are able to apply fundamental programming concepts—including logic, control flow (branching/looping), and functions—to solve defined power plant/energy engineering problems in a functional and structured manner using the Python language. | A– (A.3) |
| **CLO-2** | Students are able to construct a Python script to perform the data wrangling cycle (gathering, assessing, and cleaning) on a raw energy/power-plant dataset (e.g., a .csv file of sensor or operational data) ensuring the data is valid and ready for analysis. | D– (D.1) |
| **CLO-3** | Students are able to analyze cleaned power-plant/energy data by applying descriptive statistics and Exploratory Data Analysis (EDA) to identify patterns, trends, and anomalies to support drawing (problem-solving) conclusions. | B – (B.2) - E – (E.2) |
| **CLO-4** | Students are able to design effective data visualizations (static graphs) and a simple interactive dashboard (Streamlit) to communicate power plant/energy performance findings clearly and professionally. `[REVISI: dashboard digabung eksplisit ke CLO-4, menggantikan "CLO-6" yang sebelumnya tidak terdefinisi]` | I – (I.1), H |
| **CLO-5** | Students are able to explain and identify the potential ethical implications, bias, and privacy issues within energy/power-plant data collection and processing procedures, including critical-infrastructure data security considerations. `[REVISI: konteks infrastruktur kritis ditambahkan]` | G – (G.1) |

---

## VI. COMPETENCY MAP

**Course: RPE311 – Basic Programming**

Struktur peta kompetensi tetap piramida CLO-1 → CLO-2 → CLO-3 → CLO-4 → CLO-5 (bottom-up) seperti RPS asli, dengan koreksi: puncak piramida adalah **CLO-5** (etika data), bukan "CLO-6" yang sebelumnya tidak terdefinisi. **CLO-4** kini eksplisit mencakup visualisasi *maupun* dashboard interaktif.

```
Course Learning Goal: fondasi pemrograman Python → analisis data operasional pembangkit/energi
                                  ▲
                     CLO-5  Etika, bias, privasi data (infrastruktur energi)
                                  ▲
                     CLO-4  Visualisasi data & dashboard interaktif (Streamlit)
                                  ▲
                     CLO-3  Statistik deskriptif & EDA
                                  ▲
                     CLO-2  Data wrangling (gathering, assessing, cleaning)
                                  ▲
                     CLO-1  Logika, control flow, fungsi (Python)
                                  ▲
              Entry behaviour: literasi komputer dasar / logika matematika
```

---

## VII. WEEKLY COURSE PLAN `[REVISI]`

*Satu dataset operasional pembangkit (nyata atau simulasi) diperkenalkan sejak Minggu 8 dan dipakai konsisten sebagai "proyek berjalan" hingga Minggu 14 — misalnya **UCI Combined Cycle Power Plant Dataset**, atau dataset sintetis suhu boiler/tekanan turbin/output MW/konsumsi bahan bakar.*

| Week | CLO | Subject | Konteks/Studi Kasus Energi (revisi) | Time | Assessment | Resources |
|---|---|---|---|---|---|---|
| 1 | CLO-1 | Introduction to Python (Intro Python & Colab; variables, I/O, comments) | Diagnostik logika dasar (non-nilai) + kasus sederhana: menghitung efisiensi termal dasar pembangkit | 270" | Diagnostik, journal | [1][2][3][4] |
| 2 | CLO-2 | Interacting with Data (Data types; list/set/dict; string ops) | Merepresentasikan data sensor pembangkit (suhu boiler, tekanan, output MW) dengan list/dict | 270" | Journal, coding practice | [1][2][3][4] |
| 3 | CLO-1 | Expressions & Operators | Menghitung efisiensi, capacity factor, heat rate dari data operasi harian | 270" | Q1 | [1][2][3][4] |
| 4 | CLO-1 | Control Flow (if/elif/else; for/while; error handling) | Deteksi anomali (over-temperature, overload) pada data time-series pembangkit | 270" | Coding practice | [1][2][3][4] |
| 5 | CLO-1 | Arrays and Their Processing | Pemrosesan sekuensial data produksi energi harian | 270" | Q2 / A1 | [1][2][3][4] |
| 6 | CLO-1 | Matrices (Matrix fundamentals & NumPy) | Representasi matriks beban/jaringan distribusi listrik sederhana; operasi matriks (penjumlahan, transpose) | 270" | Coding practice | [1][2][3][4] |
| 7 | CLO-1 | Subprograms (Functions) | Modularisasi fungsi perhitungan efisiensi pembangkit agar reusable | 270" | A2 | [1][2][3] |
| **Mid-Sem** | - | **Mid-semester Evaluation** | Materi Minggu 1–7 (fondasi pemrograman) | - | **MSE** | - |
| 8 | CLO-2 | Fundamentals of Data Analysis (Data Analysis Lifecycle; Pandas; Matplotlib/Seaborn) | Pengenalan dataset "Operasional Pembangkit" — proyek berjalan dimulai di sini | 270" | Journal | [1][2][3][4] |
| 9 | CLO-3 | Descriptive Statistics (Central tendency, dispersion, correlation) | Statistik deskriptif konsumsi bahan bakar, output daya, efisiensi antar-unit pembangkit | 270" | Q3 | [1][2][3][4] |
| 10 | CLO-5 | Considerations in Data Processing (Data Ethics & Validity) | Kerahasiaan data operasional infrastruktur kritis, keamanan data SCADA, regulasi ketenagalistrikan/ESDM, bias sensor `[REVISI]` | 270" | A3 (refleksi tertulis) | [1][2][3][4] |
| 11 | CLO-2 | Data Wrangling (Gathering, assessing, cleaning) | Membersihkan dataset pembangkit (missing reading sensor, outlier akibat kalibrasi) | 270" | Milestone Proyek 1 (P7) | [1][2][3][4] |
| 12 | CLO-3 | Exploratory Data Analysis (EDA) (EDA with Pandas) | Eksplorasi pola konsumsi energi/efisiensi per shift/musim | 270" | Milestone Proyek 2 (P8) | [1][2][3][4] |
| 13 | CLO-4 | Data Visualization (Univariate/bivariate; explanatory analysis) | Visualisasi tren produksi & efisiensi pembangkit | 270" | Milestone Proyek 3 (P9) | [1][2][3][4] |
| 14 | CLO-4 | Interactive Dashboard (Streamlit; widgets; layout) `[REVISI: dipetakan ke CLO-4, bukan "CLO-6"]` | Dashboard monitoring KPI kinerja pembangkit (efisiensi, output, downtime); presentasi proyek akhir | 270" | P10 + PP (presentasi) + A4 | [1][2][3][4] |
| **Final-Sem** | - | **Final-semester Evaluation** | Proyek akhir terintegrasi (CLO-2 s/d CLO-5) + ujian tertulis | - | **FSE** | - |

**(1) Learning Method** (tetap seperti RPS asli): Interactive lecture, demonstration, live coding practice in Colab — reinforcement of disciplinary knowledge; product & system design/implementation untuk milestone proyek Minggu 11–14.

**(2) Assessment Method** (tetap seperti RPS asli): Journal, portofolios, Coding practice — ditambah Milestone Proyek dan Presentasi Proyek (PP) untuk Minggu 11–14.

---

## VIII. FACILITIES, INFRASTRUCTURE AND EQUIPMENT TO SUPPORT THE PRACTICE/PRACTICUM

| No. | Name of Facilities/Infrastructure/Supporting Equipment | Quantity (Unit) |
|---|---|---|
| 1 | Computer | 30 |
| 2 | Projector | 1 |
| 3 | Code Editor | 30 |
| 4 | Python Engine | 30 |
| 5 | Dataset operasional pembangkit (real/simulasi) — mis. UCI Combined Cycle Power Plant Dataset `[BARU]` | 1 set |

---

## IX. ASSESSMENT RUBRIC

Rubrik proficiency level (1–5) mengikuti RPS asli tanpa perubahan skala (1 = exposed, 2 = participate, 3 = understand & explain, 4 = skilled in practice, 5 = lead/innovate), diterapkan pada PI: CLO-1 → A-(A.3), CLO-2 → D-(D.1), CLO-3 → B-(B.2) & E-(E.2), CLO-4 → I-(I.1), CLO-5 → G-(G.1). Deskriptor level tetap seperti dokumen asli; konteks contoh pada level 3–5 kini merujuk ke analisis/simulasi sistem pembangkit dan kelistrikan, bukan sistem generik.

---

## X. STUDENT OUTCOMES ASSESSMENT PLAN `[REVISI]`

| CDIO Stages | Conceive |||Design|||Implement||||||Operate||||
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| **Weeks** | 1 | 2 | 3 | 4 | 5 | 6 | 7 | **Mid-Sem** | 8 | 9 | 10 | 11 | 12 | 13 | 14 | **Final-Sem** |
| **A– (A.1)** | | | Q1 | | | | | **MSE** | | Q3 | | | | | | |
| **A – (A.2)** | | | | | Q2 | | | **MSE** | | | | | | | | |
| **B – (B.2)** | | | | | A1 | | A2 | | | | A3 | | | | A4 | **FSE** |
| **D – (D.1)** | P1 | P2 | P3 | P4 | P5 | P6 | | **MSE** | | | | P7 | P8 | | | **FSE** |
| **E – (E.1)** | P1 | P2 | P3 | P4 | P5 | P6 | | **MSE** | | | | P7 | P8 | P9 | P10 | **FSE** |
| **G – (G.1)** `[BARU]` | | | | | | | | | | | A3 | | | | Refleksi | **FSE** |
| **I – (I.1)** `[BARU]` | | | | | | | | | | | | | | P9 | P10 | **FSE** |
| **H – (H.1)** | | | | | | | | | | | | | | PP | PP | **FSE** |

**Notes:**
- **A** : Assignment
- **Q** : Quiz
- **MSE** : Mid-Semester Exam
- **FSE** : Final-Semester Exam
- **P** : Practice/Project
- **PP** : Project Presentation, Demo or Team meeting

> **[REVISI]** Baris G–(G.1) dan I–(I.1) ditambahkan karena sebelumnya tidak ada instrumen asesmen untuk capaian etika data (CLO-5) dan visualisasi/dashboard (CLO-4). Instrumen P7–P10 disebar merata di Minggu 11–14 (mengikuti milestone proyek: wrangling → EDA → visualisasi → dashboard) alih-alih menumpuk di Minggu 9–12 seperti pada RPS asli.

---

## XI. ASSIGNMENT DESCRIPTION `[REVISI — sebelumnya placeholder]`

| Komponen | Bobot |
|---|---|
| Tugas individu & journal mingguan (coding practice) | 15% |
| Kuis (Q1–Q3) | 10% |
| Proyek berkelanjutan berbasis data pembangkit (milestone wrangling → EDA → visualisasi → dashboard, Mgg 11–14) | 25% |
| Ujian Tengah Semester (UTS / MSE) | 20% |
| Ujian/Evaluasi Akhir Semester (FSE, termasuk presentasi proyek akhir) | 20% |
| Soft skill (kolaborasi tim, presentasi, portofolio/journal) | 10% |
| **Total** | **100%** |

---

## XII. GRADING SCALE

| Category | Grading Scale | Grade |
|---|---|---|
| Excellent | > 85 | A |
| Very Good | 80 – 84 | A- |
| | 75 – 79 | B+ |
| Good | 70 – 74 | B |
| | 65 – 69 | B- |
| Fair | 60 – 64 | C+ |
| | 55 – 59 | C |
| Poor | 50 – 54 | C- |
| | 45 - 49 | D+ |
| | 40 - 44 | D |
| | < 40 | E |

---

## XIII. COURSE POLICIES

The rules of conduct in the course, as agreed between the lecturer and students, may include tolerance for lateness, submission of assignments, participation in assessments, and other matters in accordance with the regulations of the study program or the lecturer's requirements to ensure the learning process runs effectively:

- A maximum lateness tolerance of 15 minutes from the scheduled class time.
- Assignments and laboratory reports must be uploaded to the learning platform within the specified deadline.
- No make-up Mid-Semester Exam (MSE) or Final-Semester Exam (FSE) will be provided.
- Proyek akhir (Minggu 11–14) dikerjakan berkelompok (2–3 mahasiswa) dengan milestone wajib dikumpulkan tiap minggu; keterlambatan milestone mengurangi nilai proyek berkelanjutan. `[BARU]`

---

## XIV. TEXTBOOKS/SUPPLIES/MATERIALS/EQUIPMENT/TECHNOLOGY OR TECHNICAL REQUIREMENTS

### A. Textbooks and References

1. Python Software Foundation. *Python 3.x Official Documentation*. (Tersedia online: https://docs.python.org/3/)
2. McKinney, W., *Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython*, 3rd Edition, O'Reilly Media, 2022
3. Matthes, E., *Python Crash Course: A Hands-On, Project-Based Introduction to Programming*, 3rd Edition, No Starch Press, 2023
4. Raharjo, B., *Logika dan Algoritma Pemrograman Menggunakan Python*, Informatika, 2023
5. Susilo, A., *Panduan Lengkap Analisis Data dan Visualisasi Menggunakan Python*, Elex Media Komputindo, 2022
6. Géron, A., *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*, 3rd Edition, O'Reilly Media, 2022
7. UCI Machine Learning Repository — *Combined Cycle Power Plant Data Set* (dataset operasional pembangkit untuk EDA/regresi) `[BARU]`
8. Kementerian ESDM — *Statistik Ketenagalistrikan* (data & regulasi konsumsi/produksi energi nasional) `[BARU]`

### B. Technology or Technical Requirements

1. Komputer atau Laptop pribadi dengan sistem operasi modern (Windows 10/11, macOS, atau Linux).
2. Koneksi internet yang stabil untuk mengakses Google Colab, cloud notebooks, dan mengunduh dataset.
3. Perangkat Lunak: Web Browser modern (Google Chrome atau Mozilla Firefox); Akun Google (untuk akses Google Colab).
4. (Opsional) Instalasi Python 3.10+ secara lokal, direkomendasikan melalui distribusi Anaconda.
5. (Opsional) Code Editor seperti Visual Studio Code.

---

## XV. ADDITIONAL INFORMATION

Draft revisi ini disusun untuk mengintegrasikan paruh pertama semester (dasar pemrograman Python) dengan paruh kedua (analisis data dasar) melalui satu alur data operasional pembangkit energi yang konsisten, sekaligus melengkapi kekosongan instrumen asesmen untuk capaian visualisasi (I-(I.1)) dan etika data (G-(G.1)) yang sebelumnya tidak ada pada RPS versi 07 Agustus 2023.

| | | | |
|---|---|---|---|
| **Date** | : 19 August 2026 | **Date** | : 19 August 2026 |
| **Prepared by** | : Muhammad Veven, S. Kom., M. Eng | **Approved by** | : Irwanto Zarma Putra S.Pd, M.Eng |
| **Sign** | | **Sign** | |

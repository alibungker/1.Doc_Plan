# 📘 Panduan Dokumen Pengembangan Aplikasi Sesuai Standar ISO

Dokumen ini merinci seluruh artefak/dokumen yang diperlukan dalam siklus hidup pengembangan perangkat lunak (Software Development Life Cycle / SDLC) sesuai standar ISO/IEC/IEEE.

| **No.** | **Tahap SDLC (ISO/IEC 12207)** | **Nama Dokumen** | **Deskripsi dan Isi Utama** | **Standar ISO Acuan** |
|:--:|:--|:--|:--|:--|
| **1** | **Inisiasi / Studi Kelayakan** | **Project Proposal / Business Case** | Menguraikan latar belakang, tujuan proyek, ruang lingkup, estimasi biaya, risiko, manfaat bisnis, dan analisis kelayakan investasi (ROI). | ISO 21500:2012 – Project Management |
| **2** | **Analisis Kebutuhan** | **URS – User Requirements Specification** | Menjelaskan kebutuhan pengguna (user stories, use case, proses bisnis, ekspektasi layanan). Fokus pada perspektif non-teknis. | ISO/IEC/IEEE 29148:2018 |
| **3** |  | **SRS – Software Requirements Specification** | Spesifikasi kebutuhan perangkat lunak secara formal dan terstruktur: kebutuhan fungsional, non-fungsional, antarmuka, batas sistem, dan kriteria penerimaan. | ISO/IEC/IEEE 29148:2018 |
| **4** |  | **SyRS – System Requirements Specification** | Menjabarkan kebutuhan sistem secara menyeluruh (software, hardware, network, keamanan, dependensi eksternal). | ISO/IEC/IEEE 29148:2018 |
| **5** | **Perancangan Sistem (System Design)** | **SDD – Software Design Document** | Mendeskripsikan arsitektur perangkat lunak: diagram C4, modul, interface, alur data, algoritma utama, dan rancangan database (ERD, DFD, Class Diagram). | ISO/IEC/IEEE 42010:2011 – Architecture Description |
| **6** |  | **UI/UX Design Specification** | Desain antarmuka dan pengalaman pengguna: wireframe, prototipe, pedoman desain visual, warna, tipografi, dan prinsip aksesibilitas. | ISO 9241-210:2019 – Human-Centred Design |
| **7** |  | **Data Dictionary / Data Model Document** | Menjabarkan definisi entitas, atribut, tipe data, relasi antar tabel, constraint, dan aturan validasi database. | ISO/IEC 11179 – Metadata Registry |
| **8** | **Implementasi / Konstruksi** | **Coding Standards & Style Guide** | Menetapkan konvensi penulisan kode, penamaan variabel, struktur folder, keamanan (OWASP), serta standar linting dan review. | ISO/IEC 25010 – Code Quality |
| **9** |  | **Configuration Management Plan (CMP)** | Menjelaskan strategi pengelolaan versi kode, branching model (GitFlow), tagging, dan dokumentasi perubahan. | ISO/IEC/IEEE 12207 – Configuration Management Process |
| **10** | **Verifikasi & Validasi (Testing)** | **Test Plan (TP)** | Strategi dan lingkup pengujian: unit test, integration test, system test, acceptance test; metode, alat uji, jadwal, dan kriteria keberhasilan. | ISO/IEC/IEEE 29119-3:2013 |
| **11** |  | **Test Case Specification (TCS)** | Daftar skenario uji per modul: input, expected output, pre-condition, langkah eksekusi, dan hasil aktual. | ISO/IEC/IEEE 29119-3:2013 |
| **12** |  | **Test Report (TR)** | Rekapitulasi hasil pengujian, tingkat keberhasilan, bug report, severity, dan rekomendasi perbaikan. | ISO/IEC/IEEE 29119-3:2013 |
| **13** | **Deployment / Rilis Produksi** | **Deployment Guide (DG)** | Langkah teknis untuk instalasi sistem ke server: requirement, environment setup, konfigurasi database, load balancing, rollback plan, dan verifikasi pasca deploy. | ISO/IEC/IEEE 12207 – Implementation Process |
| **14** |  | **Release Notes / Version Log** | Catatan versi rilis, daftar fitur baru, bug fix, perubahan API, dan kompatibilitas versi. | ISO/IEC 26514:2008 – User Documentation |
| **15** | **Operasional & Pemeliharaan** | **Maintenance Plan (MP)** | Rencana perawatan sistem: pemeliharaan korektif, adaptif, preventif, serta prosedur pelaporan masalah. | ISO/IEC 14764:2006 – Software Maintenance |
| **16** |  | **User Guide (UG)** | Panduan penggunaan aplikasi untuk pengguna akhir dan admin sistem, dilengkapi gambar dan prosedur operasional standar. | ISO/IEC 26514:2008 |
| **17** |  | **Administrator / Operator Manual** | Petunjuk untuk admin sistem: setup, konfigurasi, backup, monitoring, restart, dan troubleshooting. | ISO/IEC 26514:2008 |
| **18** |  | **Backup & Disaster Recovery Plan (DRP)** | Strategi backup dan pemulihan data: frekuensi backup, jenis backup (full, incremental), RPO/RTO, dan prosedur failover. | ISO/IEC 22301:2019 – Business Continuity Management |
| **19** | **Keamanan Informasi** | **Information Security Plan / Risk Assessment** | Analisis risiko keamanan, kontrol akses, enkripsi, audit log, kebijakan keamanan data pribadi, serta mitigasi risiko. | ISO/IEC 27001:2022 / 27002:2022 |
| **20** | **Monitoring & Evaluasi** | **Performance & SLA Report** | Analisis performa sistem (uptime, response time, throughput), serta kepatuhan terhadap SLA. | ISO/IEC 25010 – Quality in Use |
| **21** |  | **Audit Log & Compliance Report** | Laporan hasil audit sistem, kepatuhan terhadap standar keamanan, kebijakan privasi, dan hasil audit eksternal. | ISO/IEC 27001 – ISMS |
| **22** | **Retrospektif / Penutupan Proyek** | **Post Implementation Review (PIR)** | Evaluasi hasil proyek terhadap tujuan awal, tingkat keberhasilan implementasi, pelajaran yang diperoleh (lessons learned), dan rekomendasi perbaikan. | ISO 21500:2012 – Project Management |
| **23** | **Aset Pendukung Finansial** | **Financial Model / Cost Analysis Document** | Model biaya proyek, proyeksi pendapatan, analisis ROI, dan alokasi anggaran pengembangan serta operasional. | ISO/IEC 15939 – Measurement Process |
| **24** | **Kontrol & Dokumentasi Tambahan** | **Change Request Form (CRF)** | Formulir permintaan perubahan kebutuhan atau desain, beserta dampak biaya & jadwal. | ISO/IEC/IEEE 12207 – Change Management |
| **25** |  | **Traceability Matrix (RTM)** | Matriks keterlacakan antara kebutuhan (SRS), desain (SDD), dan pengujian (Test Case). | ISO/IEC/IEEE 29148:2018 |

---

## 🧩 Hierarki Hubungan Dokumen

```text
Business Case
 ├── URS (User Requirements)
 │     └── SRS (Software Requirements)
 │          └── SyRS (System Requirements)
 ├── SDD (Software Design)
 │     ├── UI/UX Design Spec
 │     └── Data Dictionary
 ├── Test Plan
 │     ├── Test Case
 │     └── Test Report
 ├── Deployment Guide
 ├── Maintenance Plan
 ├── User Guide
 ├── Security & DR Plan
 └── Post Implementation Review

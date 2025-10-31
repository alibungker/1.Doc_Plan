# SYSTEM ROLE
Kamu adalah seorang System Analyst, Software Architect, dan Full Stack Developer senior berpengalaman 15+ tahun dalam pengembangan aplikasi enterprise berbasis Laravel, AI Speech-to-Text, dan NLP. 
Kamu akan membuat proyek aplikasi web bernama **E-Risalah** secara lengkap, modular, dan siap produksi.

# PROJECT OVERVIEW
E-Risalah adalah **aplikasi web mandiri (stand-alone)** yang berfungsi sebagai **asisten rapat cerdas berbasis AI**. 
Produk ini dikembangkan khusus untuk membantu **pencatatan, transkripsi, dan analisis rapat secara otomatis.**

# OBJECTIVES
- Menghasilkan transkrip rapat **real-time** dari:
  1. Rapat tatap muka (melalui mikrofon)
  2. Rapat daring (Zoom, Google Meet, Microsoft Teams)
  3. File audio/video yang diunggah (MP3, WAV, MP4)
- Membuat **ringkasan otomatis**, daftar item tindakan, serta **analisis konteks percakapan**.
- Menghasilkan **infografis atau mind map otomatis** setelah rapat.
- Menerapkan fitur **Voice Match** untuk mengenali pembicara.
- Menyediakan **Ask AI** untuk membuat dokumen interaktif dari hasil rapat.

# TECHNOLOGY STACK
- **Back-end:** Laravel 11 (PHP 8.3+)
- **Front-end:** HTML5, TailwindCSS, Vue.js (optional), JavaScript
- **Database:** MySQL/MariaDB
- **AI Modules:** 
  - Speech-to-Text (Google Speech API / Whisper / OpenAI)
  - NLP (OpenAI GPT / HuggingFace Transformers)
- **Integrations:** Zoom API, Google Meet API, Microsoft Graph API
- **Deployment:** Nginx + PHP-FPM di Ubuntu 24.04, support Docker
- **Security:** OAuth2, CSRF, HTTPS, Role-Based Access Control (RBAC)

# CORE FEATURES
1. **Authentication & Role System**
   - Login/registrasi pengguna (admin, notulis, peserta)
   - Manajemen organisasi & tim
2. **Meeting Management**
   - Buat jadwal rapat, undang peserta, unggah agenda
   - Integrasi kalender (Google/Microsoft)
3. **Real-time Transcription**
   - Modul Speech-to-Text dengan multi-speaker diarization
   - Live captioning di layar web
   - Dukungan bahasa Indonesia dan Inggris
4. **Summary & Insights**
   - Ringkasan otomatis berbasis NLP
   - Action items (to-do list)
   - Sentiment & keyword extraction
5. **Visual Summary**
   - Auto-generated infographic, flowchart, atau mind map
   - Template visual HTML5/CSS dengan export ke PDF/PNG
6. **Ask AI Module**
   - Chat dengan hasil transkrip untuk menjawab pertanyaan
   - Cek fakta, jelaskan istilah, buat ringkasan baru
7. **Voice Match Recognition**
   - Label pembicara otomatis berdasarkan pola suara
8. **History & Archive**
   - Simpan hasil rapat, transkrip, dan infografis
   - Ekspor ke PDF, DOCX, dan share link

# OUTPUT REQUIREMENTS
Buatkan output berikut secara lengkap:

1. **SRS_E-Risalah.md** — Software Requirements Specification (IEEE 830 style)
2. **PRD_E-Risalah.md** — Product Requirement Document
3. **SDD_E-Risalah.md** — Software Design Document dengan diagram arsitektur & ERD
4. **DEPLOYMENT_E-Risalah.md** — Panduan deployment Ubuntu 24.04 (Nginx + PHP + SSL)
5. **MAINTENANCE_E-Risalah.md** — Panduan pemeliharaan dan pembaruan sistem
6. **TEST_PLAN_E-Risalah.md** — Dokumen pengujian fungsional & non-fungsional
7. **USER_GUIDE_E-Risalah.md** — Panduan penggunaan aplikasi untuk end-user
8. **finance_model_E-Risalah.md** — Model finansial dan proyeksi bisnis (3 tahun)
9. **app_structure.json** — Struktur direktori proyek Laravel lengkap
10. **main.blade.php + dashboard.blade.php + meeting_view.blade.php** — Mockup UI utama

# DESIGN REQUIREMENTS
- UI minimalis bergaya profesional (tema biru tua & putih)
- Layout responsif (Tailwind + Alpine.js)
- Dashboard intuitif dengan chart ringkasan rapat
- Tombol aksi cepat: “Mulai Rapat”, “Unggah Rekaman”, “Buat Ringkasan”

# EXPECTED OUTPUT
Hasilkan semua file dalam format Markdown dan kode Laravel siap pakai. 
Gunakan struktur penjelasan berjenjang dan jelaskan setiap komponen kode secara singkat. 
Jika memungkinkan, sertakan potongan kode dan pseudocode untuk modul AI utama.

# BONUS TASK
Tambahkan prompt slogan visual untuk “infografis hasil rapat”:
> “Transformasi Rapat Anda Menjadi Wawasan yang Bermakna — E-Risalah, Asisten Rapat Cerdas Anda.”

# GOAL
Buat sistem e-Risalah yang:
- Meningkatkan efisiensi rapat dan dokumentasi hingga 80%.
- Menghadirkan notulen, infografis, dan insight rapat otomatis.
- Siap diintegrasikan dengan sistem pemerintahan atau korporasi besar.


# OUTPUT FORMAT
Berikan hasil dalam format:

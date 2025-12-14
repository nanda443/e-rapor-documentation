# BUKU PANDUAN LENGKAP SISTEM E-RAPOR SMA

**Versi 3.0 - FINAL RELEASE**  
**Tanggal: 14 Desember 2024**  
**Update: Production Configuration, Maintenance Guide, Final Release for School Deployment**

## KATA PENGANTAR

Puji syukur kehadirat Tuhan Yang Maha Esa atas terselesaikannya Buku Panduan Lengkap Sistem e-Rapor SMA ini. Buku panduan ini disusun sebagai pedoman bagi seluruh pengguna sistem e-Rapor di lingkungan sekolah, mulai dari Admin, Guru, hingga Siswa.

Sistem e-Rapor SMA merupakan aplikasi berbasis web yang dirancang untuk memudahkan proses pengelolaan nilai dan rapor siswa secara digital. Dengan sistem ini, diharapkan proses penilaian menjadi lebih efisien, akurat, dan transparan.

Buku panduan ini disusun secara sistematis dan dilengkapi dengan langkah-langkah detail untuk setiap fungsi dalam sistem. Kami berharap buku panduan ini dapat membantu seluruh pengguna dalam mengoperasikan sistem e-Rapor dengan baik dan benar.

## DAFTAR ISI

### BAB I: PENDAHULUAN

-   1.1 Latar Belakang
-   1.2 Tujuan Sistem
-   1.3 Manfaat Sistem
-   1.4 Pengguna Sistem

### BAB II: AKSES DAN LOGIN SISTEM

-   2.1 Mengakses Sistem
-   2.2 Login ke Sistem
-   2.3 Lupa Password
-   2.4 Logout dari Sistem

### BAB III: PANDUAN UNTUK ADMINISTRATOR

-   3.1 Dashboard Admin
-   3.2 Manajemen Data Master
-   3.3 Manajemen Kurikulum
-   3.4 Manajemen Pembelajaran
-   3.5 Input dan Manajemen Nilai
-   3.6 Manajemen Data Siswa
-   3.7 Cetak Rapor
-   3.8 Kontrol Phase (Jadwal & Akses)
-   3.9 Profil Sekolah
-   3.10 Manajemen Akun

### BAB IV: PANDUAN UNTUK GURU

-   4.1 Dashboard Guru
-   4.2 Melihat Jadwal Mengajar
-   4.3 Input Tujuan Pembelajaran (TP)
-   4.4 Input Nilai Siswa
-   4.5 Input Deskripsi Capaian Kompetensi
-   4.6 Fitur Wali Kelas
-   4.7 Pembina Ekstrakurikuler
-   4.8 Melihat Rapor Siswa
-   4.9 Profil Pengguna

### BAB V: PANDUAN UNTUK SISWA

-   5.1 Dashboard Siswa
-   5.2 Melihat Nilai
-   5.3 Melihat Rapor
-   5.4 Download Rapor
-   5.5 Profil Pengguna

### LAMPIRAN

-   Lampiran A: Glossary
-   Lampiran B: Format Data Import
-   Lampiran C: FAQ (Frequently Asked Questions)

## BAB I: PENDAHULUAN

### 1.1 Latar Belakang

Sistem e-Rapor SMA merupakan aplikasi berbasis web yang dikembangkan untuk membantu sekolah dalam mengelola data akademik siswa, khususnya dalam proses penilaian dan pembuatan rapor. Sistem ini mengadopsi Kurikulum Merdeka yang menggunakan konsep Capaian Pembelajaran (CP) dan Tujuan Pembelajaran (TP).

Di era digital saat ini, pengelolaan data secara manual menjadi tidak efisien dan rentan terhadap kesalahan. Sistem e-Rapor hadir sebagai solusi untuk mengotomatisasi proses penilaian, mempercepat pembuatan rapor, dan meningkatkan akurasi data.

### 1.2 Tujuan Sistem

Tujuan pengembangan Sistem e-Rapor SMA adalah:

1. **Efisiensi**: Mempercepat proses input nilai dan pembuatan rapor
2. **Akurasi**: Mengurangi kesalahan perhitungan dan input data
3. **Transparansi**: Memudahkan akses informasi nilai bagi siswa dan orang tua
4. **Dokumentasi**: Menyimpan data akademik secara terpusat dan aman
5. **Pelaporan**: Memudahkan pembuatan laporan akademik dan statistik

### 1.3 Manfaat Sistem

**Untuk Sekolah:**

-   Pengelolaan data terpusat dan terorganisir
-   Proses administrasi lebih cepat dan efisien
-   Data akademik tersimpan aman dengan backup otomatis
-   Kemudahan dalam membuat laporan dan statistik

**Untuk Guru:**

-   Input nilai lebih mudah dan cepat
-   Perhitungan nilai otomatis
-   Dapat diakses kapan saja dan dimana saja
-   Mengurangi beban administrasi

**Untuk Siswa dan Orang Tua:**

-   Akses nilai secara real-time
-   Transparansi penilaian
-   Dapat mengunduh rapor digital
-   Memantau perkembangan akademik

### 1.4 Pengguna Sistem

Sistem e-Rapor SMA memiliki 3 (tiga) jenis pengguna dengan hak akses berbeda:

**1. Administrator** - Mengelola seluruh sistem dengan akses penuh ke semua fitur dan data.

**2. Guru** - Melakukan kegiatan pembelajaran dan penilaian dengan akses ke kelas yang diajar.

**3. Siswa** - Melihat data akademik pribadi termasuk nilai dan rapor.

## BAB II: AKSES DAN LOGIN SISTEM

### 2.1 Mengakses Sistem

**Kebutuhan Sistem:**

-   Perangkat: Komputer, laptop, tablet, atau smartphone
-   Browser: Google Chrome (direkomendasikan), Firefox, Safari, atau Edge versi terbaru
-   Koneksi Internet: Stabil dengan kecepatan minimal 1 Mbps

**Cara Mengakses:**

1. Buka browser web Anda
2. Ketik alamat URL sistem: `https://erapor.smamuhkasihan.sch.id/login`
3. Tekan **Enter**
4. Halaman login akan muncul

> **Catatan**: Simpan URL sebagai bookmark/favorit untuk akses cepat

### 2.2 Login ke Sistem

**Langkah-langkah Login:**

1. **Masukkan Email** - Ketik alamat email yang terdaftar dengan format yang benar
2. **Masukkan Password** - Ketik password dengan benar, perhatikan huruf besar/kecil
3. **Centang "Remember Me" (Opsional)** - Jika ingin tetap login di perangkat tersebut
4. **Klik Tombol "Login"** - Sistem akan memverifikasi kredensial Anda

**Kredensial Default:**

| User  | Email                    | Password              |
| ----- | ------------------------ | --------------------- |
| Admin | admin@erapor.sch.id      | (diberikan oleh IT)   |
| Guru  | NIP@guru.erapor.sch.id   | NIP (default, ganti)  |
| Siswa | NISN@siswa.erapor.sch.id | NISN (default, ganti) |

> **PENTING**: Segera ganti password default setelah login pertama kali!

### 2.3 Lupa Password

Jika lupa password, ikuti langkah berikut:

1. Klik **"Lupa Password?"** di halaman login
2. Masukkan **Email** yang terdaftar
3. Klik **"Send Password Reset Link"**
4. Cek email Anda
5. Klik **Link** yang dikirim via email
6. Masukkan **Password Baru** (minimal 6 karakter)
7. Konfirmasi password baru
8. Klik **"Reset Password"**

> **Catatan**: Link reset password berlaku selama 60 menit

### 2.4 Logout dari Sistem

**Cara Logout:**

1. Klik **nama/foto profil** di pojok kanan atas
2. Pilih **"Logout"**
3. Sistem akan kembali ke halaman login

> **PENTING**: Selalu logout setelah selesai menggunakan sistem, terutama di komputer umum!

## BAB III: PANDUAN UNTUK ADMINISTRATOR

### 3.1 Dashboard Admin

Dashboard Admin adalah halaman utama yang muncul setelah admin berhasil login. Dashboard menampilkan ringkasan data dan statistik penting dengan fitur monitoring kesehatan sistem.

**Konten Dashboard:**

1. **System Health Score** - Kesehatan sistem (0-100) dengan breakdown detail
2. **Critical Alerts** - Alert deadline TP/Nilai dan masalah urgent
3. **Statistik Utama** - Total guru, siswa, rombongan, tahun ajaran
4. **Tabbed Interface** - Overview, data master, progress input, alerts
5. **Menu Navigasi** - Sidebar kiri dengan menu utama

### 3.2 Manajemen Data Master

Data Master adalah data-data pokok yang harus disiapkan sebelum sistem dapat digunakan. Input data master harus dilakukan secara berurutan.

**Urutan Input Data Master:**

1. Tahun Ajaran
2. Kelas & Jurusan
3. Mata Pelajaran
4. Guru
5. Siswa
6. Rombongan Belajar
7. Ekstrakurikuler
8. Capaian Pembelajaran (CP)

### 3.3 Manajemen Kurikulum

Kurikulum terdiri dari Capaian Pembelajaran (CP) dan Tujuan Pembelajaran (TP).

**CP (Capaian Pembelajaran):** Kompetensi yang ditargetkan dicapai siswa untuk mata pelajaran tertentu pada fase tertentu. Diatur oleh admin.

**TP (Tujuan Pembelajaran):** Jabaran detail dari CP. Diinput oleh guru per pembelajaran.

### 3.4 Manajemen Pembelajaran

Pembelajaran adalah penugasan guru untuk mengajar mata pelajaran tertentu di rombongan tertentu.

**Cara Menambah Pembelajaran:**

1. Akses menu **Pembelajaran → Assign Pembelajaran**
2. Klik **"Tambah Pembelajaran"**
3. Isi form: Tahun Ajaran, Rombongan, Mata Pelajaran, Guru
4. Klik **"Simpan"**

### 3.5 Input dan Manajemen Nilai

Admin bisa input nilai untuk semua pembelajaran jika diperlukan.

**Cara Input Nilai:**

1. Akses menu **Penilaian → Input Nilai**
2. Pilih filter: Tahun Ajaran, Rombongan, Pembelajaran
3. Pilih jenis nilai: Formatif (per TP), UTS, atau UAS
4. Isi nilai untuk setiap siswa (rentang 0-100)
5. Klik **"Simpan Nilai"**

### 3.6 Manajemen Data Siswa

**Input Kedisiplinan:**

1. Akses menu **Penilaian → Kedisiplinan**
2. Pilih rombongan
3. Isi: Sakit, Izin, Alpha (dalam hari)
4. Klik **"Simpan"**

**Input Catatan Wali Kelas:**

1. Akses menu **Penilaian → Catatan Wali Kelas**
2. Pilih rombongan
3. Isi catatan untuk setiap siswa
4. Klik **"Simpan"**

**Input Kenaikan Kelas:**

1. Akses menu **Penilaian → Kenaikan Kelas**
2. Pilih rombongan
3. Tentukan status: Naik, Tinggal Kelas, atau Lulus
4. Klik **"Simpan"**

### 3.7 Cetak Rapor

**Cetak Rapor Individual:**

1. Akses **Rapor → Cetak Rapor**
2. Pilih tahun ajaran, rombongan, siswa
3. Klik **"Preview Rapor"**
4. Download PDF atau print

**Cetak Rapor Batch (Massal):**

1. Akses **Rapor → Cetak Rapor Batch**
2. Pilih rombongan dan siswa (bisa multiple)
3. Klik **"Generate Rapor"**
4. Tunggu selesai, download ZIP

**Cetak Leger Nilai dan Transkrip:**

-   Leger: Rekapitulasi nilai semua siswa dalam satu rombongan
-   Transkrip: Rekap nilai siswa selama 3 tahun (kelas X-XII)

### 3.8 Kontrol Phase (Jadwal & Akses)

Fitur untuk mengatur fase pembelajaran, akses input, deadline, dan jadwal otomatis.

**Phase-phase Pembelajaran:**

| Phase       | Nama            | Deskripsi                              |
| ----------- | --------------- | -------------------------------------- |
| planning    | Perencanaan     | Fase awal semester, setup pembelajaran |
| tp_input    | Input TP        | Guru menginput Tujuan Pembelajaran     |
| nilai_input | Input Nilai     | Guru menginput nilai siswa             |
| finalisasi  | Finalisasi      | Pengecekan akhir sebelum publish       |
| published   | Publikasi Rapor | Rapor sudah bisa diakses siswa         |

**Cara Mengubah Phase:**

1. Akses menu **Sistem → Kontrol Phase**
2. Lihat phase aktif saat ini
3. Pilih phase baru dari tombol yang tersedia
4. Konfirmasi perubahan

**Pengaturan Deadline:**

1. Tentukan deadline input TP dan nilai
2. Atur grace period (masa tenggang)
3. Setting akan divalidasi saat guru input

**Jadwal Otomatis:**

-   System bisa otomatis membuka akses berdasarkan jadwal
-   Memerlukan CRON job di server
-   Bisa diubah kapan saja sebelum waktu eksekusi

### 3.9 Profil Sekolah

Kelola informasi sekolah yang tampil di rapor:

1. Akses **Pengaturan → Profil Sekolah**
2. Isi data:
    - Nama Sekolah
    - NPSN
    - Alamat lengkap
    - Telepon & Email
    - Kepala Sekolah
    - Logo sekolah
3. Klik **"Simpan"**

### 3.10 Manajemen Akun

**Mengelola Profil Admin:**

1. Klik menu profile
2. Edit data dan klik **"Simpan"**

**Mengganti Password:**

1. Masuk ke halaman Profil
2. Isi password saat ini dan password baru
3. Klik **"Simpan"**

## BAB IV: PANDUAN UNTUK GURU

### 4.1 Dashboard Guru

Dashboard menampilkan:

-   Statistik kelas, siswa, mata pelajaran yang diajar
-   Jadwal mengajar
-   Reminder nilai & TP yang belum diinput
-   Fitur khusus jika Anda wali kelas

### 4.2 Melihat Jadwal Mengajar

1. Akses menu **Pembelajaran Saya**
2. Lihat daftar pembelajaran:
    - Tahun ajaran
    - Rombongan
    - Mata pelajaran
    - Jumlah siswa
3. Klik tombol untuk: Input nilai, lihat siswa, input TP, input deskripsi

### 4.3 Input Tujuan Pembelajaran (TP)

**Cara Membuat TP:**

1. Akses menu **Tujuan Pembelajaran**
2. Pilih pembelajaran yang akan dibuat TP-nya
3. Klik **"Tambah Tujuan Pembelajaran"**
4. Isi form:
    - Capaian Pembelajaran (pilih CP yang sesuai)
    - Kode TP (opsional)
    - Deskripsi TP (harus diisi)
    - Urutan (opsional)
5. Klik **"Simpan"**

**Tips Membuat TP:**

-   Buat TP di awal semester
-   Buat 3-5 TP per mata pelajaran per semester
-   TP harus spesifik dan terukur
-   Sesuaikan dengan CP yang ada

### 4.4 Input Nilai Siswa

**Input Nilai Formatif (per TP):**

1. Akses menu **Input Nilai**
2. Pilih pembelajaran
3. Pilih **"Formatif"**
4. Pilih TP yang akan dinilai
5. Isi nilai untuk setiap siswa (0-100)
6. Klik **"Simpan Nilai"**

**Input Nilai UTS:**

1. Pilih pembelajaran
2. Pilih **"UTS"**
3. Isi nilai UTS untuk setiap siswa
4. Klik **"Simpan Nilai"**

**Input Nilai UAS:**

1. Pilih pembelajaran
2. Pilih **"UAS"**
3. Isi nilai UAS untuk setiap siswa
4. Klik **"Simpan Nilai"**

**Tips Input Nilai:**

-   Input secara bertahap setelah pembelajaran selesai
-   Nilai bisa diubah kapan saja sebelum rapor dicetak
-   Sistem auto-calculate nilai akhir dari rata-rata

### 4.5 Input Deskripsi Capaian Kompetensi

Deskripsi berisi penjelasan naratif tentang pencapaian siswa.

1. Akses menu **Deskripsi Capaian**
2. Pilih pembelajaran
3. Pilih siswa
4. Isi deskripsi (naratif dan membangun)
5. Klik **"Simpan"**

**Contoh Deskripsi:**

> "Ananda Budi menunjukkan pemahaman baik dalam materi bilangan berpangkat. Mampu menyelesaikan soal dengan tepat. Perlu ditingkatkan kemampuan dalam soal cerita kompleks."

### 4.6 Fitur Wali Kelas

Fitur ini muncul jika Anda ditunjuk sebagai wali kelas.

**Input Kedisiplinan:**

1. Akses **Wali Kelas → Kedisiplinan**
2. Isi sakit, izin, alpha (dalam hari)
3. Klik **"Simpan"**

**Input Catatan Wali Kelas:**

1. Akses **Wali Kelas → Catatan Wali Kelas**
2. Isi catatan untuk setiap siswa
3. Klik **"Simpan"**

**Input Kenaikan Kelas:**

1. Akses **Wali Kelas → Kenaikan Kelas**
2. Pilih status: Naik, Tinggal Kelas, atau Lulus
3. Klik **"Simpan"**

**Cetak Rapor Kelas:**

1. Akses **Wali Kelas → Rapor Kelas**
2. Pilih siswa (single atau multiple)
3. Klik **"Generate Rapor"**
4. Download PDF atau ZIP

### 4.7 Pembina Ekstrakurikuler

Fitur ini muncul jika Anda adalah pembina ekstrakurikuler.

**Input Nilai Ekstrakurikuler:**

1. Akses **Ekstrakurikuler → Input Nilai**
2. Pilih ekstrakurikuler yang dibina
3. Pilih tahun ajaran
4. Isi nilai (predikat A/B/C/D) untuk setiap siswa
5. Isi keterangan (opsional)
6. Klik **"Simpan"**

### 4.8 Melihat Rapor Siswa

1. Akses menu **Rapor Siswa**
2. Pilih tahun ajaran, rombongan, siswa
3. Klik **"Lihat Rapor"**
4. Preview rapor dalam PDF
5. Download jika diperlukan

### 4.9 Profil Pengguna

**Mengelola Profil:**

1. Klik nama profil di pojok kanan atas
2. Pilih **"Profil"**
3. Edit data: nama, NIP, NUPTK, alamat, foto
4. Klik **"Simpan"**

**Mengganti Password:**

1. Masuk ke halaman Profil
2. Isi password saat ini dan password baru
3. Klik **"Simpan"**

## BAB V: PANDUAN UNTUK SISWA

### 5.1 Dashboard Siswa

Dashboard menampilkan:

-   Info pribadi: nama, NISN, kelas, foto
-   Statistik: jumlah mapel, rata-rata nilai, kehadiran
-   Quick links: lihat nilai, lihat rapor, download rapor

### 5.2 Melihat Nilai

1. Akses menu **Nilai Saya**
2. Pilih tahun ajaran
3. Lihat daftar nilai:
    - Nilai per mata pelajaran
    - Nilai formatif (per TP)
    - Nilai UTS & UAS
    - Nilai akhir

### 5.3 Melihat Rapor

1. Akses menu **Rapor Saya**
2. Pilih tahun ajaran dan semester
3. Klik **"Lihat Rapor"**
4. Preview rapor yang menampilkan:
    - Nilai semua mata pelajaran
    - Nilai ekstrakurikuler
    - Kedisiplinan
    - Catatan wali kelas
    - Status kenaikan kelas

### 5.4 Download Rapor

1. Buka rapor (lihat langkah 5.3)
2. Klik tombol **"Download PDF"**
3. Simpan file PDF ke perangkat Anda

**Kegunaan Rapor Digital:**

-   Arsip pribadi
-   Ditunjukkan ke orang tua
-   Pendaftaran kuliah/beasiswa

### 5.5 Profil Pengguna

**Edit Data Profil:**

1. Klik nama profil di pojok kanan atas
2. Pilih **"Profil"**
3. Edit: alamat, no telepon, foto
4. Klik **"Simpan"**

> **Catatan**: Data pribadi seperti nama, NISN hanya bisa diubah oleh admin.

**Mengganti Password:**

1. Masuk ke halaman Profil
2. Isi password saat ini dan password baru
3. Klik **"Simpan"**

## LAMPIRAN

### Lampiran A: Glossary

**Admin/Administrator** - Pengguna dengan hak akses penuh untuk mengelola sistem

**Alpha** - Ketidakhadiran tanpa keterangan

**Batch** - Proses massal (banyak data sekaligus)

**CP (Capaian Pembelajaran)** - Kompetensi yang harus dicapai siswa pada fase tertentu

**Dashboard** - Halaman utama setelah login

**Deskripsi** - Penjelasan naratif tentang pencapaian siswa

**Ekstrakurikuler** - Kegiatan di luar jam pelajaran

**Fase** - Periode capaian pembelajaran (E=kelas X, F=kelas XI-XII)

**Formatif** - Penilaian berkelanjutan selama pembelajaran

**KKM** - Kriteria Ketuntasan Minimal (nilai minimal untuk tuntas)

**Leger** - Rekapitulasi nilai semua siswa dalam satu rombongan

**NIP** - Nomor Induk Pegawai

**NISN** - Nomor Induk Siswa Nasional

**Rapor** - Laporan hasil belajar siswa

**Rombongan Belajar** - Kelas/kelompok siswa dalam satu periode pembelajaran

**TP (Tujuan Pembelajaran)** - Jabaran spesifik dari capaian pembelajaran

**UAS** - Ujian Akhir Semester

**UTS** - Ujian Tengah Semester

**Wali Kelas** - Guru yang bertanggung jawab atas satu rombongan

### Lampiran B: Format Data Import

**Template Import Siswa (Excel):**

| NISN       | NIS     | Nama Lengkap | Jenis Kelamin | Agama | Tempat Lahir | Tanggal Lahir |
| ---------- | ------- | ------------ | ------------- | ----- | ------------ | ------------- |
| 0051234567 | 2024001 | Ahmad Fauzi  | L             | Islam | Jakarta      | 2008-01-15    |

**Template Import Guru (Excel):**

| NIP                | Nama Lengkap | Jenis Kelamin | Email          |
| ------------------ | ------------ | ------------- | -------------- |
| 198501012010011001 | Budi Santoso | L             | budi@email.com |

**Catatan:**

-   Format tanggal: YYYY-MM-DD
-   Jenis kelamin: L atau P
-   Simpan dalam format .xlsx
-   Email harus unik

### Lampiran C: FAQ (Frequently Asked Questions)

**Q: Apakah sistem bisa diakses dari HP?**
A: Ya, sistem responsive dan bisa diakses dari smartphone/tablet.

**Q: Apakah data aman?**
A: Ya, tersimpan aman di server dengan backup berkala.

**Q: Bagaimana cara menambah banyak siswa sekaligus?**
A: Gunakan fitur Import dengan file Excel sesuai template.

**Q: Apakah nilai bisa diubah setelah disimpan?**
A: Ya, nilai bisa diubah kapan saja sebelum rapor dicetak.

**Q: Bagaimana jika guru mengundurkan diri?**
A: Ubah status guru menjadi "Tidak Aktif", jangan dihapus.

**Q: Apakah wajib membuat TP?**
A: Ya, TP diperlukan untuk input nilai formatif.

**Q: Kapan nilai bisa dilihat siswa?**
A: Setelah guru menginput nilai dan admin publikasi rapor.

**Q: Bagaimana cara menghubungi guru tentang nilai?**
A: Hubungi guru langsung atau melalui wali kelas.

## PENUTUP

Demikian Buku Panduan Lengkap Sistem e-Rapor SMA ini kami susun. Semoga buku panduan ini dapat membantu seluruh pengguna dalam mengoperasikan sistem dengan baik dan benar.

Sistem e-Rapor akan terus dikembangkan dan ditingkatkan untuk memberikan layanan terbaik bagi sekolah. Masukan dan saran untuk perbaikan sistem sangat kami harapkan.

**Tim IT Sekolah**
Email: [email IT sekolah]
Telepon: [nomor telepon]

**Tim Pengembang Sistem e-Rapor SMA**
2024

© 2024 Sistem e-Rapor SMA. All Rights Reserved.

## CATATAN REVISI

| Versi | Tanggal          | Perubahan                                                                       |
| ----- | ---------------- | ------------------------------------------------------------------------------- |
| 1.0   | 02 Desember 2024 | Dokumen awal - Panduan dasar admin, guru, siswa                                 |
| 2.0   | 07 Desember 2024 | Tambah Phase Control, Update Dashboard, System Health Monitoring                |
| 3.0   | 14 Desember 2024 | **FINAL RELEASE** - BAB VI (Production), BAB VII (Maintenance), Panduan Go-Live |
| 3.1   | 15 Desember 2024 | **CLEAN VERSION** - Hapus separator berlebihan, format lebih rapi untuk PDF     |
| 3.2   | 15 Desember 2024 | **USER VERSION** - Hapus BAB VI & VII (Production sudah ditangani tim IT)       |

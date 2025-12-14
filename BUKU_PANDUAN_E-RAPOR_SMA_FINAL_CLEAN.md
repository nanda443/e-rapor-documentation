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

### BAB VI: KONFIGURASI PRODUKSI & GO-LIVE

-   6.1 Requirement Server
-   6.2 Instalasi di Server Produksi
-   6.3 Konfigurasi Environment Produksi
-   6.4 Setup Queue Worker & Scheduler
-   6.5 Checklist Go-Live
-   6.6 Monitoring & Backup

### BAB VII: MAINTENANCE & TROUBLESHOOTING

-   7.1 Maintenance Rutin
-   7.2 Troubleshooting Umum
-   7.3 Error Messages & Solutions
-   7.4 Update & Upgrade System
-   7.5 Kontak Dukungan Teknis

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
2. Ketik alamat URL sistem: `https://erapor.namasekolah.sch.id`
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

1. Klik nama profil di pojok kanan atas
2. Pilih **"Profil"**
3. Edit data dan klik **"Simpan"**

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

## BAB VI: KONFIGURASI PRODUKSI & GO-LIVE

**Catatan**: Bagian ini ditujukan untuk Administrator Server/IT yang akan melakukan deployment.

### 6.1 Requirement Server

**Minimum Requirement (untuk 200-500 siswa):**

-   CPU: 2 Core
-   RAM: 2 GB
-   Storage: 20 GB SSD
-   Bandwidth: 100 Mbps
-   OS: Ubuntu 20.04+ / CentOS 8+ / Windows Server 2019+
-   PHP: 8.3+
-   MySQL: 8.0+ / MariaDB 10.5+

**Recommended Requirement (untuk 500+ siswa):**

-   CPU: 4 Core
-   RAM: 4-8 GB
-   Storage: 50 GB SSD NVMe
-   Bandwidth: 500 Mbps
-   OS: Ubuntu 24.04 LTS
-   Web Server: Nginx 1.24+
-   PHP: 8.3
-   Database: MySQL 8.0+
-   Cache: Redis 7.0+

**Estimasi Kapasitas:**

-   500 siswa: 2 CPU / 4 GB RAM
-   1000 siswa: 4 CPU / 8 GB RAM
-   2000+ siswa: 8 CPU / 16 GB RAM

### 6.2 Instalasi di Server Produksi

**Instalasi di Ubuntu 22.04 (VPS):**

```bash
# Update system
sudo apt update && sudo apt upgrade -y

# Install PHP 8.3
sudo add-apt-repository ppa:ondrej/php -y
sudo apt update
sudo apt install -y php8.3 php8.3-fpm php8.3-mysql php8.3-mbstring \
    php8.3-xml php8.3-bcmath php8.3-curl php8.3-zip php8.3-gd php8.3-intl

# Install MySQL
sudo apt install -y mysql-server
sudo mysql_secure_installation

# Install Nginx
sudo apt install -y nginx
sudo systemctl start nginx && sudo systemctl enable nginx

# Install Composer & Node.js
curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs

# Clone project
cd /var/www
sudo git clone https://github.com/yourusername/e-rapor-sma.git
cd e-rapor-sma

# Setup project
cp .env.example .env
composer install --optimize-autoloader --no-dev
npm install && npm run build
php artisan key:generate
php artisan migrate --seed

# Set permissions
sudo chown -R www-data:www-data .
sudo chmod -R 775 storage bootstrap/cache
php artisan storage:link

# Configure Nginx
sudo nano /etc/nginx/sites-available/erapor
# Paste Nginx config (lihat dokumentasi)
sudo ln -s /etc/nginx/sites-available/erapor /etc/nginx/sites-enabled/
sudo nginx -t && sudo systemctl restart nginx
```

**Instalasi di cPanel (Shared Hosting):**

1. Buat database MySQL di cPanel
2. Upload files via FTP (exclude vendor, node_modules)
3. Install dependencies: `composer install` & `npm run build`
4. Copy .env.example ke .env
5. Generate key: `php artisan key:generate`
6. Run migration: `php artisan migrate --seed`
7. Point domain ke `public` folder

### 6.3 Konfigurasi Environment Produksi

**File .env - Setting Penting:**

```env
APP_NAME="e-Rapor SMA"
APP_ENV=production
APP_DEBUG=false
APP_URL=https://erapor.sekolah.sch.id

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=e_rapor_sma
DB_USERNAME=erapor_user
DB_PASSWORD=P@ssw0rd_Aman123!

SESSION_DRIVER=file
CACHE_STORE=file
QUEUE_CONNECTION=database
```

**Optimisasi Performance:**

```bash
# Cache configuration
php artisan config:cache
php artisan route:cache
php artisan view:cache
composer dump-autoload --optimize

# Atau single command
php artisan optimize
```

**Setup SSL/HTTPS (Let's Encrypt):**

```bash
sudo apt install certbot python3-certbot-nginx
sudo certbot --nginx -d erapor.sekolah.sch.id
sudo certbot renew --dry-run
```

### 6.4 Setup Queue Worker & Scheduler

**Setup Cron Job:**

```bash
# Edit crontab
crontab -e

# Add line
* * * * * cd /var/www/e-rapor-sma && php artisan schedule:run >> /dev/null 2>&1
```

**Setup Queue Worker dengan Supervisor:**

```bash
# Install supervisor
sudo apt install supervisor

# Create config
sudo nano /etc/supervisor/conf.d/erapor-worker.conf
```

```ini
[program:erapor-worker]
process_name=%(program_name)s_%(process_num)02d
command=php /var/www/e-rapor-sma/artisan queue:work --sleep=3 --tries=3
autostart=true
autorestart=true
user=www-data
numprocs=2
redirect_stderr=true
stdout_logfile=/var/www/e-rapor-sma/storage/logs/worker.log
```

```bash
sudo supervisorctl reread
sudo supervisorctl update
sudo supervisorctl start erapor-worker:*
```

### 6.5 Checklist Go-Live

**Pre-Launch:**

-   [ ] Server memenuhi requirement
-   [ ] Database sudah dibuat & konfigurasi benar
-   [ ] SSL/HTTPS aktif
-   [ ] Code sudah ter-deploy
-   [ ] Migration sudah dijalankan
-   [ ] Cache sudah di-generate
-   [ ] Cron job & queue worker berjalan
-   [ ] File permissions sudah benar
-   [ ] Database backup strategy setup
-   [ ] Test login, CRUD, input nilai, generate rapor
-   [ ] User manual siap
-   [ ] Training admin & guru selesai

**Launch Day:**

-   [ ] Monitoring aktif
-   [ ] Support team standby
-   [ ] Database backup sebelum launch
-   [ ] Announce ke seluruh pengguna
-   [ ] Log monitoring untuk error

### 6.6 Monitoring & Backup

**Server Monitoring:**

```bash
# Check resources
htop
df -h

# Check services
sudo systemctl status mysql
sudo systemctl status php8.3-fpm
sudo systemctl status nginx

# Check logs
tail -f storage/logs/laravel.log
sudo tail -f /var/log/nginx/error.log
```

**Database Backup:**

```bash
#!/bin/bash
DATE=$(date +%Y%m%d_%H%M%S)
BACKUP_DIR="/var/backups/erapor"

# Create backup directory
mkdir -p $BACKUP_DIR

# Backup database
mysqldump -u erapor_user -pPassword e_rapor_sma | gzip > $BACKUP_DIR/db_$DATE.sql.gz

# Delete backups older than 30 days
find $BACKUP_DIR -name "db_*.sql.gz" -mtime +30 -delete
```

**Restore dari Backup:**

```bash
# Extract & restore
gunzip db_20241214_020000.sql.gz
mysql -u erapor_user -p e_rapor_sma < db_20241214_020000.sql
```

## BAB VII: MAINTENANCE & TROUBLESHOOTING

### 7.1 Maintenance Rutin

**Daily Maintenance:**

-   Monitor server resources (CPU, RAM, disk)
-   Check application logs untuk errors
-   Verify database berjalan
-   Check latest backups

**Weekly Maintenance:**

-   Clear old logs
-   Optimize database
-   Clear application cache
-   Check storage usage
-   Review queue jobs

**Monthly Maintenance:**

-   Update system packages
-   Security audit (composer audit, npm audit)
-   Review performance
-   Data archiving
-   Verify offsite backups

### 7.2 Troubleshooting Umum

**Masalah Login:**

| Masalah                 | Solusi                                |
| ----------------------- | ------------------------------------- |
| Lupa password           | Klik "Lupa Password?" dan ikuti reset |
| Email tidak terdaftar   | Hubungi admin untuk registrasi        |
| Password salah berulang | Tunggu 10 menit atau reset password   |
| Akun terkunci           | Hubungi admin untuk unlock            |

**Masalah Input Nilai:**

| Masalah                   | Solusi                                                |
| ------------------------- | ----------------------------------------------------- |
| Nilai tidak bisa disimpan | Pastikan format angka benar (0-100)                   |
| TP tidak muncul           | Buat TP terlebih dahulu                               |
| Siswa tidak muncul        | Pastikan siswa sudah di-assign ke rombongan           |
| Error format              | Hapus karakter non-angka, gunakan titik untuk desimal |

**Masalah Cetak Rapor:**

| Masalah                | Solusi                               |
| ---------------------- | ------------------------------------ |
| Nilai tidak muncul     | Pastikan semua nilai sudah diinput   |
| Catatan kosong         | Wali kelas harus input catatan       |
| Status kenaikan kosong | Input status kenaikan kelas          |
| PDF tidak bisa dibuka  | Update PDF reader atau ganti browser |

**Masalah Performance:**

| Masalah        | Solusi                                  |
| -------------- | --------------------------------------- |
| Sistem lambat  | Check koneksi internet, refresh browser |
| Timeout rapor  | Proses batch per kelas, jangan semua    |
| Browser freeze | Tutup tab lain, clear cache, restart    |

### 7.3 Error Messages & Solutions

**Error Validasi:**

-   "Field wajib diisi" → Isi semua field yang bertanda \*
-   "Email tidak valid" → Gunakan format email benar
-   "Password minimal 6 karakter" → Gunakan password lebih panjang
-   "Email sudah digunakan" → Gunakan email yang berbeda

**Error Input Nilai:**

-   "Nilai harus angka" → Hapus huruf/karakter
-   "Nilai 0-100" → Input nilai dalam range
-   "Angka positif" → Tidak boleh negatif

**Error Akses:**

-   "403 Forbidden" → Login dengan akun sesuai role
-   "401 Unauthorized" → Session habis, login ulang

### 7.4 Update & Upgrade System

**Update Aplikasi:**

```bash
# Backup dulu!
./backup-db.sh

# Pull latest code
cd /var/www/e-rapor-sma
git pull origin master

# Update dependencies
composer install --no-dev
npm install && npm run build

# Run migration
php artisan migrate

# Clear & rebuild cache
php artisan optimize:clear
php artisan optimize

# Restart services
sudo systemctl restart php8.3-fpm
sudo supervisorctl restart erapor-worker:*
```

**Rollback (jika update bermasalah):**

```bash
git reset --hard HEAD~1
mysql -u erapor_user -p e_rapor_sma < backup.sql
php artisan optimize:clear
php artisan optimize
```

### 7.5 Kontak Dukungan Teknis

**Tim IT Sekolah (Level 1 Support)**

-   Untuk: Login, password, akses, data master, operasional
-   Email: it@sekolah.sch.id

**Developer Support (Level 2)**

-   Repository: https://github.com/yourusername/e-rapor-sma
-   Issues: Report bug di GitHub Issues

**Jam Operasional:** Senin-Jumat 08:00-16:00 WIB, Sabtu 08:00-12:00 WIB

**Informasi yang Dipersiapkan Saat Menghubungi Support:**

-   Role/Jabatan
-   Username/Email
-   Browser & Version
-   Operating System
-   Deskripsi masalah yang jelas
-   Screenshot jika ada error
-   Langkah yang sudah dicoba

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

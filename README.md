🛠️ Fase 1: Persiapan Repository & Ruang Kerja
[ ] Buat repository baru di GitHub.

[ ] Inisialisasi file README.md dan .gitignore.

[ ] Buat akun gratis di FlutterFlow.io.

[ ] Unduh dan instal FlutterFlow Desktop App (Opsional).

[ ] Hubungkan akun GitHub ke dalam proyek FlutterFlow.

🔑 Fase 2: Setup Database & Autentikasi (Firebase Spark Plan)
[ ] Buat proyek baru di Firebase Console.

[ ] Aktifkan Firebase Authentication dengan metode Email/Password.

[ ] Hubungkan konfigurasi Firebase ke proyek FlutterFlow.

[ ] Buat akun Admin pertama secara manual lewat menu Users di Firebase Console.

🎨 Fase 3: Desain UI & Arsitektur Data Awal
[ ] Desain halaman Login (Login Page) di FlutterFlow.

[ ] Buat struktur tabel (Collection) users di FlutterFlow/Firebase dengan field: email, display_name, dan role.

[ ] Buat dokumen manual di tabel users untuk akun Admin pertama dengan mengisi field role bernilai 'admin'.

[ ] Hubungkan tombol "Login" ke aksi Firebase Authentication Log In.

[ ] Buat logika pengondisian (Conditional Action) setelah login berdasarkan status role == 'admin'.

📅 Fase 4: Perancangan Modul Manajemen Kegiatan & Presensi Santri
[ ] Buat struktur tabel (Collection) kegiatan dengan field: id_kegiatan, nama_kegiatan, dan dibuat_oleh.

[ ] Desain halaman "Manajemen Kegiatan" (Form input tambah kegiatan dan daftar list kegiatan).

[ ] Buat struktur tabel (Collection) presensi_santri dengan field: santri_id, nama_santri, tanggal, status (Hadir/Izin/Alpha), dan keterangan.

[ ] Desain halaman "Input Presensi Santri" (Pilihan dropdown kegiatan, daftar nama santri menggunakan ListView, pilihan Radio Button/ChoiceChips untuk status, dan tombol simpan).

[ ] Terapkan aturan filter tanggal (Query Filtering) dan aktivasi Cache Local pada query database presensi santri.

👨‍🏫 Fase 5: Perancangan Modul Presensi Guru (Tambahan Baru)
[ ] Buat struktur tabel (Collection) guru atau gunakan users dengan role == 'guru' untuk memisahkan data pengajar.

[ ] Buat struktur tabel (Collection) presensi_guru dengan field: guru_id, nama_guru, tanggal, status (Hadir/Izin/Alpha), dan keterangan.

[ ] Desain halaman "Input Presensi Guru" untuk Admin (Menggunakan ListView daftar guru, pilihan status, dan tombol simpan).

(Fase 6)

[ ] Desain halaman "Dashboard Guru".

[ ] Tambahkan tombol "Manajemen / Presensi Santri" di Dashboard Guru.

[ ] Beri aksi (Action) pada tombol tersebut untuk mengarahkan (Navigate To) guru ke halaman "Input Presensi Santri".

[ ] Terapkan aturan filter tanggal (Query Filtering) dan aktivasi Cache Local pada query database presensi guru.# to-do-list-belajar-buat-aplikasi-managemen-pesantren

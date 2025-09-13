#  PROJEK: PENGELOLAAN KERJA KELOMPOK

---

### Latar Belakang
Dalam lingkungan kampus, mahasiswa sering diberi tugas atau proyek kelompok. Namun, masalah yang muncul antara lain:

- Sulit membagi tugas secara adil dan jelas
- Minimnya komunikasi antar anggota, sehingga progres tidak terpantau
- Beberapa anggota tidak aktif atau tidak tahu perkembangan terakhir
- Kesulitan mendokumentasikan kontribusi setiap anggota

Untuk itu, kami mengembangkan aplikasi Sistem Pengelolaan Kerja Kelompok berbasis Laravel, yang membantu mencatat, membagi, dan memonitor tugas secara digital, sehingga kerja kelompok lebih terstruktur, transparan, dan efisien.

---

### Tujuan Utama Proyek
1. Mempermudah pembagian tugas dalam kelompok secara terorganisir.
2. Mencatat setiap progres pekerjaan anggota kelompok.
3. Memberikan notifikasi dan pengingat deadline tugas.
4. Memastikan semua anggota terlibat sesuai peran masing-masing.
5. Menyediakan laporan aktivitas sebagai bahan evaluasi kerja kelompok.

---

### Fitur Utama
- Autentikasi Pengguna: Login & register untuk ketua dan anggota.
- Manajemen Kelompok: Ketua membuat kelompok, menambahkan anggota.
- Manajemen Proyek: Buat project baru, kelola deskripsi & timeline.
- Task Management: Tambah tugas, tetapkan deadline, assign ke anggota tertentu.
- Progress Tracking: Status tugas (To-Do, In Progress, Done) & persentase progress project.
- Komentar & Diskusi: Forum per tugas agar komunikasi terarah.
- File Sharing: Upload dokumen/lampiran terkait project.
- Dashboard & Laporan: Grafik progress dan laporan kontribusi tiap anggota.

---

### Manfaat
- Membantu kelompok bekerja lebih teratur dan profesional.
- Mengurangi miskomunikasi antaranggota.
- Meningkatkan produktivitas dengan pembagian tugas yang jelas.
- Mempermudah monitoring oleh ketua kelompok.
- Menyediakan data riil untuk evaluasi kerja sama tim.

### Lingkup Proyek
- User: Mahasiswa (ketua & anggota kelompok).
- Teknologi: Laravel, MySQL/MariaDB, TailwindCSS (frontend), dan Chart.js (grafik).
- Output: Aplikasi berbasis web untuk mengelola kerja kelompok.
- Batasan: Fokus untuk kerja kelompok skala kecil-menengah (3–10 orang).

### Alur Kerja Sistem (Konsep)
1. Ketua membuat kelompok & project baru.
2. Ketua/anggota menambahkan tugas.
3. Anggota yang ditugaskan meng-update progres.
4. Diskusi dilakukan lewat komentar di setiap tugas.
5. Sistem menampilkan laporan kontribusi & progress project.
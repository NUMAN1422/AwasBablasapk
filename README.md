# AwasBablas!

**Jangan sampai kebablasan!**

AwasBablas! adalah aplikasi Android yang membangunkan pengguna dengan alarm ketika sudah mendekati tujuan, sehingga penumpang KRL, bus, dan angkutan umum lainnya dapat beristirahat tanpa khawatir melewati stasiun atau halte.

Pengguna memilih tujuan pada peta, menentukan radius, lalu menekan **Mulai pantau**. Ketika posisi perangkat masuk ke dalam radius, alarm berbunyi dan perangkat bergetar.

<!-- Tambahkan 3-4 tangkapan layar di sini, misalnya: -->
<!-- ![Beranda](gambar/beranda.png) -->

## Unduh

Unduh berkas APK terbaru pada halaman **[Releases](https://github.com/NUMAN1422/AwasBablasapk/releases/latest)**:

- **Android**: `AwasBablas-v1.0.0.apk`
- **iOS**: segera hadir

Versi terbaru: **1.0.0**. Aplikasi memerlukan layanan lokasi (GPS) dan koneksi internet untuk peta dan pencarian tempat.

## Cara memasang

Aplikasi ini didistribusikan di luar Play Store, sehingga Android meminta beberapa izin tambahan:

1. Unduh berkas APK dari halaman Releases.
2. Buka berkas tersebut. Apabila diminta, izinkan **Pasang aplikasi dari sumber ini** untuk peramban atau pengelola berkas yang digunakan.
3. Apabila Google Play Protect menampilkan peringatan karena aplikasi tidak berasal dari Play Store, pilih **Tetap instal**.
4. Buka AwasBablas! dan izinkan akses **lokasi** dan **notifikasi** ketika diminta.

Untuk memperbarui, unduh APK terbaru dan pasang di atas versi yang lama. Data favorit tetap tersimpan. Aplikasi juga memberi tahu apabila terdapat pembaruan wajib.

## Cara penggunaan

1. Ketuk kolom **Tujuan**, cari tempat, atau pilih titik langsung pada peta.
2. Atur **radius** alarm: 300 m, 500 m, 1 km, 2 km, atau 3 km.
3. Tekan **Mulai pantau**. Layar boleh dikunci dan aplikasi lain boleh dibuka.
4. Ketika posisi memasuki radius, alarm berbunyi. Geser untuk mematikannya.

## Fitur

- Alarm berbasis posisi, bukan waktu, sehingga tetap sesuai meskipun kereta atau bus terlambat.
- Pemantauan tetap berjalan di latar belakang dan saat layar mati, dengan notifikasi tetap.
- Pilihan nada alarm: nada bawaan aplikasi, dering Android, atau berkas sendiri. Getar dan volume penuh dapat diatur.
- Favorit: Rumah, Kantor, dan beberapa tempat favorit lain, tersimpan di perangkat.
- Riwayat pencarian terakhir.
- Peringatan ketika koneksi internet terputus saat pemantauan berlangsung.
- Peta dan pencarian menggunakan data OpenStreetMap.

## Hal yang perlu diperhatikan

- **Alarm merupakan alat bantu, bukan jaminan.** Akurasi GPS dapat menurun di terowongan, di bawah atap peron, atau di antara gedung tinggi. Sistem Android atau fitur penghemat baterai tertentu juga dapat menghentikan aplikasi. Untuk perjalanan penting, tetap siapkan alarm cadangan.
- Jarak dihitung berdasarkan **garis lurus** ke tujuan, bukan sepanjang rute jalan atau rel.
- Peta dan pencarian memerlukan internet. Setelah pemantauan dimulai, alarm memanfaatkan GPS perangkat.
- Sebagian merek ponsel membatasi aplikasi di latar belakang. Apabila alarm tidak berbunyi, izinkan AwasBablas! berjalan tanpa pembatasan baterai pada pengaturan perangkat.

## Privasi

Lokasi GPS diproses di perangkat dan tidak dikirim ke server pengembang. Penjelasan lengkap tersedia pada **[PRIVACY.md](PRIVACY.md)**.

## Pelaporan masalah dan masukan

Silakan buka tab **Issues** pada repositori ini dan jelaskan masalah yang dialami, mencakup tipe perangkat, versi Android, versi aplikasi, serta langkah yang menyebabkan masalah tersebut muncul.

## Atribusi

- Data peta dan pencarian: © kontributor [OpenStreetMap](https://www.openstreetmap.org/copyright), dengan layanan [Photon](https://photon.komoot.io) dan [Nominatim](https://nominatim.org).
- Font **Bagel Fat One** (SIL Open Font License 1.1) dan **Chewy** (Apache License 2.0).
- Dibangun menggunakan [Flutter](https://flutter.dev) dan Firebase.

## Lisensi

Aplikasi ini dapat digunakan secara gratis untuk keperluan pribadi. Syarat penggunaan lengkap tersedia pada [LICENSE](LICENSE). Kode sumber tidak dipublikasikan pada repositori ini.

Dikembangkan oleh Muhamad Nur Rohman, mahasiswa Program Studi Sistem Komputer, Universitas Pamulang Kampus Serang.

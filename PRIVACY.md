# Kebijakan Privasi AwasBablas!

Berlaku sejak 9 November 2026.

AwasBablas! dikembangkan oleh Muhamad Nur Rohman ("pengembang"). Aplikasi ini tidak meminta pembuatan akun, nama, maupun alamat email. Dokumen ini menjelaskan data yang digunakan dan ke mana data tersebut diteruskan.

## Ringkasan

- Lokasi GPS digunakan di perangkat untuk menjalankan alarm dan tidak dikirim ke server pengembang.
- Favorit, riwayat pencarian, dan pengaturan disimpan di perangkat pengguna.
- Aplikasi memakai layanan pihak ketiga untuk peta, pencarian tempat, pengaturan jarak jauh, dan statistik pemakaian. Rinciannya dijelaskan di bawah.

## Data yang disimpan di perangkat

- Pengaturan aplikasi (nada alarm, getar, volume, dan sebagainya).
- Tempat favorit (Rumah, Kantor, dan lainnya) serta riwayat pencarian terakhir.

Data tersebut tidak dikirim kepada pengembang. Data akan hilang apabila aplikasi dihapus atau datanya dibersihkan.

## Lokasi

Aplikasi membaca lokasi GPS perangkat selama pemantauan perjalanan berlangsung, untuk menghitung jarak ke tujuan dan membunyikan alarm. Perhitungan dilakukan di perangkat dan koordinat posisi pengguna tidak dikirim ke server pengembang. Izin lokasi dapat dicabut kapan saja melalui pengaturan Android, tetapi alarm tidak akan berfungsi tanpa izin tersebut.
<!-- PERIKSA: pastikan permintaan pencarian tidak mengirim koordinat posisi pengguna. Apabila ya, sebutkan pada bagian Layanan pihak ketiga. -->

## Layanan pihak ketiga

**Firebase (Google)**
- *Analytics* mengumpulkan data pemakaian secara otomatis, antara lain pengenal instalasi aplikasi yang bersifat anonim, versi aplikasi, model perangkat, versi Android, perkiraan wilayah berdasarkan alamat IP, serta kejadian seperti membuka aplikasi dan melakukan pencarian. Isi pencarian tidak dikirim.
- *Remote Config* mengunduh pengaturan dari server, misalnya status pemeliharaan, versi minimum, dan tautan pembaruan. Firebase menerima pengenal instalasi aplikasi untuk keperluan ini.
- Pengembang menggunakan data tersebut hanya untuk menilai tingkat pemakaian dan kebutuhan pengembangan aplikasi. Data tidak dijual. Masa penyimpanan mengikuti pengaturan retensi Firebase Analytics. Lihat [Kebijakan Privasi Google](https://policies.google.com/privacy) dan [Privasi Firebase](https://firebase.google.com/support/privacy).
<!-- PERIKSA: atur retensi data Analytics di Firebase (Admin > Data settings > Data retention), lalu sebutkan angkanya di sini. -->

**OpenStreetMap**
Peta diunduh dari server ubin OpenStreetMap. Server tersebut menerima alamat IP pengguna dan permintaan ubin peta, yang menunjukkan perkiraan area peta yang dilihat. Lihat [Kebijakan Privasi OSMF](https://osmfoundation.org/wiki/Privacy_Policy).

**Photon dan Nominatim**
Ketika pengguna mencari tempat, teks pencarian dikirim ke layanan Photon (komoot) dan, sebagai cadangan, Nominatim (OpenStreetMap). Kedua layanan ini juga menerima alamat IP pengguna. Lihat [Kebijakan Privasi komoot](https://www.komoot.com/privacy) dan [Kebijakan Penggunaan Nominatim](https://operations.osmfoundation.org/policies/nominatim/).

## Izin yang diminta

- **Lokasi**: menghitung jarak ke tujuan.
- **Notifikasi**: menampilkan notifikasi pemantauan dan alarm.
- **Pengecualian penghemat baterai** (opsional): agar pemantauan tidak dihentikan oleh sistem.
- Izin teknis lain, seperti internet, getar, layanan latar depan, dan menjaga layar tetap menyala, sesuai fitur yang digunakan.
<!-- PERIKSA: cocokkan daftar ini dengan AndroidManifest.xml. -->

## Pilihan pengguna

- Menghapus aplikasi menghentikan seluruh pengumpulan data pemakaian dari perangkat tersebut.
- Izin lokasi dan notifikasi dapat dicabut kapan saja melalui pengaturan Android.
- Pertanyaan atau permintaan penghapusan data dapat disampaikan kepada pengembang melalui kontak di bawah. Karena data analitik bersifat anonim, pengembang mungkin tidak dapat mengaitkannya dengan individu tertentu.

## Perubahan kebijakan

Kebijakan ini dapat diperbarui sewaktu-waktu. Versi terbaru selalu tersedia pada halaman ini, dengan tanggal berlaku di bagian atas.

## Kontak

Muhamad Nur Rohman, melalui tab **Issues** pada repositori ini atau melalui email: awasbablas.app@gmail.com

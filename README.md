# PAKET-B_SHIFT-C_H1D022062_RIFQI-ALRASID
Responsi 2 Pemrograman Mobile

# SOAL
1. Sebuah menu dalam aplikasi memerlukan load data setiap kali menu tersebut diakses, pada fungsi apakah load data tersebut dilakukan untuk framework Angular dan Vue?
Jawaban:
      Load Data untuk Framework Angular dan Vue
      Angular: Data biasanya dimuat dalam metode ngOnInit di komponen yang bersangkutan atau melalui resolver jika perlu memuat data sebelum navigasi selesai. Resolver didefinisikan dalam routing module, memastikan data tersedia sebelum komponen dirender​
      Vue: Ada dua pendekatan:
      Memuat data setelah navigasi menggunakan lifecycle hook seperti created atau Composition API (watch pada parameter route).
      Memuat data sebelum navigasi dengan menggunakan beforeRouteEnter, yang memastikan data dimuat sebelum komponen dirender
   
2. Pada menu profil, komponen bawaan Ionic apa saja yang dapat diterapkan untuk membangun menu tersebut? (min. 3 dan sebutkan untuk apa fungsinya)
Jawaban:
      IonAvatar: Digunakan untuk menampilkan gambar profil pengguna, biasanya berupa lingkaran kecil dengan gambar di dalamnya.
      IonList dan IonItem: Membuat daftar navigasi atau opsi profil, seperti pengaturan, riwayat, atau logout.
      IonButton: Digunakan untuk aksi seperti "Edit Profil" atau "Logout".
      Komponen-komponen ini membantu membangun antarmuka yang responsif dan ramah pengguna.
   
3. Pada Firebase, apa perbedaan antara Cloud Firestore dan Realtime Database?
Jawaban:
      Realtime Database: Database NoSQL berbasis JSON. Data diupdate secara real-time dan cocok untuk aplikasi sederhana dengan kebutuhan sinkronisasi langsung.
      Cloud Firestore: Database NoSQL yang lebih fleksibel dengan fitur seperti query yang lebih kompleks, struktur koleksi-dokumen, dukungan offline yang lebih baik, dan skalabilitas tinggi. Firestore lebih cocok untuk aplikasi dengan kebutuhan data yang kompleks dan terstruktur

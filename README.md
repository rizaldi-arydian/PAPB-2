# PAPB-2

Penjelasan Singkat Kode

Kode tersebut merupakan aplikasi Android berbasis Jetpack Compose yang menampilkan kartu profil pengguna yang responsif tepat di tengah layar. Layout utama menggunakan komponen Column luar yang dikonfigurasi memenuhi seluruh layar dengan latar belakang transparan serta perataan konten di bagian tengah secara vertikal dan horizontal. Di dalam layout utama terdapat komponen Card berwarna biru muda yang berfungsi sebagai wadah untuk mengelompokkan elemen profil, di mana di dalamnya disusun elemen foto berbentuk lingkaran yang dipotong rapi, teks informasi diri, serta ruang pemisah bertahap menggunakan Spacer. Selain itu, aplikasi dilengkapi dengan komponen interaktif bernama FollowButton yang memanfaatkan manajemen state dinamis untuk mengubah status tombol dari Follow menjadi Unfollow secara otomatis saat diklik.

Analisis Singkat Keuntungan Compose Dibandingkan XML Layout

Keuntungan pertama Jetpack Compose adalah efisiensi pengembangan berkat pendekatan kode tunggal di mana seluruh tampilan antarmuka dan logika bisnis ditulis menggunakan satu bahasa pemrograman Kotlin. Pendekatan ini menghilangkan kebutuhan untuk membuat dan mengelola file XML terpisah, serta menghapus kode penghubung yang rumit seperti pemanggilan findViewById atau penyiapan View Binding yang biasa ditemui pada metode tradisional. Keuntungan kedua terletak pada paradigma pemograman deklaratif yang mempermudah pengelolaan state dan pembaruan antarmuka secara dinamis. Ketika ada data yang berubah, Compose akan melakukan proses recomposition untuk memperbarui komponen visual yang relevan secara otomatis tanpa memerlukan perintah pembaruan manual. Selain itu, Compose mengusung struktur kode yang sangat modular sehingga elemen antarmuka dapat dipecah menjadi fungsi-fungsi independen yang sangat mudah untuk digunakan kembali di bagian aplikasi lainnya.

![Follow1](PAPB2_landscapefollow.jpeg)

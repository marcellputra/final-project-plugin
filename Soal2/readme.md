1. Objek `lirik_lagu`
Di sini, kita mendefinisikan sebuah objek JavaScript bernama `lirik_lagu`.
Objek ini memiliki dua properti:

    `status`: Menyimpan nilai boolean `true`.
    `data`: Objek lain yang menyimpan informasi tentang lagu, termasuk nama artis, judul lagu, lirik dalam bentuk string, dan lirik yang dibagi menjadi array baris (dalam `songLyricsArr`).

2. Mengupdate objek `lirik_lagu`
    Di sini, kita menggunakan metode `Object.assign()` untuk membuat salinan dari objek `lirik_lagu` dan mengupdate bagian tertentu dari objek tersebut.
Penjelasan Langkah demi Langkah:

    `Object.assign({}, lirik_lagu)`: Membuat salinan dangkal dari objek `lirik_lagu`.
    `Object.assign({}, lirik_lagu.data)`: Membuat salinan dangkal dari objek `data` di dalam `lirik_lagu`.
    `Object.assign({}, lirik_lagu.data), { artist: "Marcell", songTitle: "Pengusaha" }`: Mengupdate properti `artist` dan `songTitle` di dalam salinan `data` dengan nilai yang sama seperti di objek asli.
    Seluruh proses ini menghasilkan objek baru bernama updated_lirik_lagu yang memiliki struktur yang sama seperti `lirik_lagu`, tetapi dengan salinan dari data yang sudah diupdate.

3. Menampilkan objek yang diperbarui
    Ini mencetak objek `updated_lirik_lagu` ke konsol, sehingga Anda bisa melihat strukturnya dan memverifikasi bahwa perubahan telah dilakukan.

4. Mengakses lirik tertentu
    Pada bagian ini, kita mengambil elemen kedua dari array `songLyricsArr` (indeks `1`) dari objek `lirik_lagu`.
Ini mengacu pada lirik yang berbunyi: "For me to take what's mine, until the end of time?"
Kemudian, lirik tertentu ini dicetak ke konsol.


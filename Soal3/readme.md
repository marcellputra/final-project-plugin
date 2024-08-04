1. Deklrasi Fungsi
Ini mendeklarasikan fungsi bernama `cetakSegitigaSikuSiku` yang menerima satu parameter:

    `tinggi`: Tipe data `number`, yang menunjukkan tinggi dari segitiga yang akan dicetak.

2. looping untuk mencetak segitiga
Ini adalah loop `for` yang berjalan dari `1` hingga `tinggi` (inklusif). Variabel `i` digunakan untuk menghitung baris yang sedang diproses:

    Baris pertama (i=1) hingga baris terakhir (i=tinggi).

3. Menghitung spasi dan Bintang
`spasi`: Ini menghitung jumlah spasi yang harus ditampilkan di awal setiap baris.

    `tinggi - i`: Menghitung jumlah spasi berdasarkan tinggi segitiga dan nomor baris saat ini. Semakin tinggi baris (`i`), semakin sedikit spasi yang ditambahkan.
    ' '.repeat(...)`: Fungsi repeat()` digunakan untuk mengulangi karakter spasi sebanyak yang dihitung. Jadi, jika `tinggi` adalah 10 dan `i` adalah 1, maka akan ada 9 spasi. Jika `i` adalah 10, tidak ada spasi.

Menghitung bintang
`bintang`: Ini menghitung jumlah bintang yang akan ditampilkan pada setiap baris.

    '*'.repeat(i): Mengulangi karakter bintang (`*`) sebanyak `i` kali. Jadi, untuk baris pertama (`i=1`), hanya akan ada 1 bintang, untuk baris kedua (`i=2`), akan ada 2 bintang, dan seterusnya hingga baris terakhir.

4. Mencetak ke konsol
Ini mencetak kombinasi dari spasi dan bintang ke konsol. Setiap baris akan memiliki spasi di depan, diikuti oleh bintang.

5. Memanggil fungsi
Ini adalah pemanggilan fungsi dengan parameter 10, yang berarti kita ingin mencetak segitiga siku-siku dengan tinggi 10 baris.
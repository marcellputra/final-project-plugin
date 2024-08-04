1. Deklarasi Fungsi
Fungsi ini bernama `hitungRataRataDanGrade` yang menerima empat parameter:

    `nilaiWeb`: Tipe data `number` yang mewakili nilai Pemrograman Web.
    `nilaiKomputer`: Tipe data `number` yang mewakili nilai Pemrograman Komputer.
    `nilaiStatistika`: Tipe data `number` yang mewakili nilai Statistika.
    `nilaiSistemBasisData`: Tipe data `number` yang mewakili nilai Sistem Basis Data.

Tipe pengembalian fungsi adalah `void`, yang berarti fungsi ini tidak mengembalikan nilai.

2. Validasi data
Bagian ini memeriksa apakah semua nilai yang dimasukkan berada dalam rentang yang valid (0 hingga 100).
Jika salah satu nilai tidak valid, fungsi akan mencetak pesan kesalahan dan keluar dari fungsi dengan menggunakan `return`.

3. Menghitung total dan rata-rata
`totalNilai`: Menghitung total dari semua nilai yang diberikan.
`rataRata`: Menghitung rata-rata nilai dengan membagi `totalNilai` dengan jumlah mata pelajaran (4).

4. Menentukan grade
Di sini, kita mendeklarasikan variabel `grade` untuk menyimpan hasil grade berdasarkan nilai rata-rata.
Menggunakan serangkaian pernyataan `if` dan `else if` untuk menentukan grade berdasarkan nilai rata-rata:

    Rata-rata 90 ke atas: Grade A
    Rata-rata 80 ke 89: Grade B
    Rata-rata 70 ke 79: Grade C
    Rata-rata 60 ke 69: Grade D
    Rata-rata di bawah 60: Grade E

5. Mencetak hasil
    Mencetak rata-rata nilai ke konsol dengan dua angka desimal menggunakan `toFixed(2)`.
    Mencetak grade yang telah ditentukan.

6. Memanggil fungsi
Di bagian ini, kita mendeklarasikan variabel untuk masing-masing nilai mata pelajaran.
Kemudian, kita memanggil fungsi `hitungRataRataDanGrade` dengan nilai-nilai tersebut sebagai argumen.

contoh output
Dengan nilai yang diberikan:

    `nilaiPemrogramanWeb = 85`
    `nilaiPemrogramanKomputer = 90`
    `nilaiStatistika = 78`
    `nilaiSistemBasisData = 88`




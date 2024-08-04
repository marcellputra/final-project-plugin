1. DOCTYPE dan Elemen HTML:
   - `<!DOCTYPE html>`: Menunjukkan bahwa ini adalah dokumen HTML5.
   - `<html lang="en">`: Elemen root dari dokumen, dengan atribut `lang` yang menunjukkan bahwa bahasa yang digunakan adalah bahasa Inggris.

2. Elemen `<head>`:
   - Berisi informasi metadata, seperti karakter set (`<meta charset="UTF-8">`), pengaturan untuk IE (`<meta http-equiv="X-UA-Compatible" content="IE=edge">`), dan pengaturan viewport untuk responsivitas di perangkat mobile (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`).
   - Memuat stylesheet dari Font Awesome untuk ikon dan menghubungkan file CSS lokal (`style.css`) untuk gaya halaman.

3. Elemen `<body>`:
   - Bagian utama dari halaman yang berisi konten yang akan ditampilkan kepada pengguna.

4. Header dan Navigasi:
   - `<header>`: Bagian atas halaman yang berisi navigasi dan bagian hero.
   - `<nav>`: Berisi logo dan daftar tautan yang mengarahkan ke bagian-bagian tertentu dari halaman (Beranda, Tentang Saya, Hobi, Kontak).

5. Bagian Hero:
   - `<section id="home" class="hero">`: Menampilkan perkenalan dengan nama dan profesi, disertai gambar profil. Teks disusun dalam dua kolom menggunakan div `content`, satu untuk teks dan satu untuk gambar.

6. Bagian Tentang Saya:
   - `<section id="about" class="about">`: Menyediakan informasi lebih mendalam tentang diri pengguna, termasuk pendidikan, ketertarikan, dan cita-cita. Terdapat gambar dan deskripsi dalam format teks.

7. Bagian Hobi:
   - `<section id="hobbies" class="hobbies">`: Memperkenalkan hobi pengguna dalam bentuk kartu, masing-masing dilengkapi dengan ikon dan deskripsi singkat. Kartu-kartu ini disusun dalam kolom.

8. Aside (Informasi Tambahan):
   - `<aside>`: Memberikan informasi tambahan tentang hobi pengguna dan mengarahkan pengunjung untuk menghubungi pengguna untuk informasi lebih lanjut.

9. Bagian Kontak:
   - `<section id="contact" class="contact-me">`: Mengajak pengunjung untuk berinteraksi lebih lanjut dengan tautan untuk menghubungi pengguna.

10. Footer:
   - `<footer>`: Menyediakan informasi tentang pemilik halaman, serta tautan ke media sosial. Mencantumkan nama pengguna dan hak cipta.


Style css
1. Gaya Umum

    Global Styles:
        Mengatur font dasar dan menghapus margin dan padding pada elemen body.

2. Header dan Navigasi

    `header`: Mengatur warna latar belakang dan teks untuk bagian header.
    `nav`: Mengatur tampilan fleksibel untuk navigasi, dengan pengaturan posisi tetap di bagian atas.
    `.logo`: Mengatur ukuran font untuk logo.
    `nav ul`: Mengatur gaya untuk daftar navigasi (membuatnya menjadi baris horizontal).

3. Bagian Hero

    `.hero`: Menentukan gaya untuk bagian hero, termasuk padding dan margin.
    `.hero` .content: Mengatur tampilan fleksibel untuk menempatkan teks dan gambar secara berdampingan.
    `.hero img`: Menentukan ukuran maksimal untuk gambar profil.

4. Bagian Tentang Saya

    `.about`: Mengatur padding dan teks agar terpusat.
    `.about .main`: Menentukan gaya untuk penataan gambar dan teks dalam bagian tentang.

5. Bagian Hobi

    `.hobbies`: Mengatur tampilan hobi pengguna.
    `.hobbies .box`: Mengatur tata letak kartu hobi menggunakan tampilan fleksibel.

6. Kartu Hobi

    `.card`: Menentukan gaya untuk setiap kartu hobi, termasuk warna latar belakang, border, dan shadow.
    `.card i`: Mengatur ukuran ikon di dalam kartu.

7. Aside dan Kontak

    `aside`: Menyediakan gaya untuk informasi tambahan.
    `.contact-me`: Menentukan gaya untuk bagian kontak.

8. Footer

    `footer`: Mengatur gaya untuk footer, termasuk warna latar belakang dan teks.
    `.social a`: Mengatur gaya untuk tautan sosial di footer.

9. Responsivitas

    Media Queries: Mengatur tata letak yang responsif saat lebar layar di bawah 768px, termasuk pengaturan untuk navigasi dan gambar.  


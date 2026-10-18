# Lab4Web

## Praktikum 4: CSS Layout

## Identitas
- **Nama** : Muhammad Agusti Abi Rizqi
- **NIM** : 312510042
- **Kelas** : I253A 
- **Prodi / Semester** : Teknik Informatika / 3
- **Dosen Pengampu** : Agung Nugroho, S.Kom., M.Kom.

## Tujuan
1. Mahasiswa mampu memahami struktur dasar pembuatan Layout.
2. Mahasiswa mampu memahami konsep box element.
3. Mahasiswa mampu memahami CSS Floating.
4. Mahasiswa mampu memahami HTML 5 Semantics Element.
5. Mahasiswa mampu membuat Layout Web Sederhana.

## Langkah-langkah Praktikum
1. ## Membuat repository baru dengan nama Lab4Web dengan cara sebagai berikut:
    - **** - Klik icon garis 3 dipojok kanan atas <img src="images/Gambar 1.jpg" width="50">, lalu pilih all repository

        <img src="images/Gambar 2.jpg" width="500">
    
    - **** - Klik New Repository <img src="images/Gambar 3.jpg" width="50">
    - **** - Setelah klik New Repository akan tampil seperti pada gambar (Gambar 1), lalu isi Repository name "Lab4Web"/ sesuai kebutuhan, dan add README di aktifkan (ON). Selanjutnya klik Create Repository dan akan tampil seperti pada gambar (Gambar 2)

        <img src="images/Gambar 4.jpg" width="500">
                        (Gambar 1)

        <img src="images/Gambar 5.jpg" width="500">
                        (Gambar 2)
2. ## Buka git bash lalu ketik pwd. pwd adalah hasil output dari perintah. setelah itu akan muncul kode /c/User/Abi Rizqi (Nama User). Ini menunjukan jalur (path) folder aktif anda saat ini, yaitu berada difolder drive C: pada folder users, didalam sub folder Abi Rizqi

    <img src="images/Gambar 6.jpg" width="500">

3. ## Setelah mempunyai direktori kerja lalu pindahkan ke d (Disk Local) dan di masukkan ke folder Labs dengan cara ketik kode cd /d/Labs/

    <img src="images/Gambar 7.jpg" width="500">

4. ## Selanjutnya salin local link yang terdapat di web github di ikon Code seperti pada gambar (Gambar 1). Lalu masuk ke git bash ketik git clone dan tempelkan link yang sudah disalin seperti pada gambar (Gambar 2). Ini berfungsi untuk memulai atau melanjutkan pengerjaan proyek yang sudah ada diserver lain agar dapat dikerjakan langsung di laptop atau komputer anda.

    <img src="images/Gambar 8.jpg" width="500">
                    (Gambar 1)

    <img src="images/Gambar 9.jpg" width="500">
                    (Gambar 2)

5. ## Didalam folder Lab4Web sekarang sudah ada file README.md (Gambar 1), setelah itu coba klik hasilnya seperti pada gambar (Gambar 2), pada file ini diisi sesuai tugas praktikum yaitu: nama repository, judul praktikum, data diri, tujuan, langkah-langka dan penjelasannya, serta hasil/gambar.

    <img src="images/Gambar 10.jpg" width="500">
                    (Gambar 1)

   <img src="images/Gambar 11.jpg" width="500">

6. ## Selanjutnya membuat file lab4_box.html dengan cara sebagai berikut:

    - **** - Klik menu file di pojok kiri atas
    - **** - Pilih New File

        <img src="images/Gambar 12.jpg" width="500">
    - **** - Memberi nama file lab4_box.html sesuai kebutuhan (Gambar 1), lalu klik enter akan tampil (Gambar 2), lalu pilih folder untuk menyimpan file tersebut setelah itu klik Create file

        <img src="images/Gambar 13.jpg" width="500">
                    (Gambar 1)

        <img src="images/Gambar 14.jpg" width="500">
                    (Gambar 2)

    - **** - Lalu buka file dengan cara klik tombol kanan pada mause, lalu pilih buka dengan, pilih Visual Studio Code untuk melaksanakan praktek (Gambar 1) dan jika ini membuka/melihat hasilnya praktek pilih Google Chrome, Firefox, Microsoft Edge hasilnya seperti pada gambar (Gambar 2).

        <img src="images/Gambar 15.jpg" width="500">
        <img src="images/Gambar 16.jpg" width="500">
                    (Gambar 1)

        <img src="images/Gambar 17.jpg" width="500">
                    (Gambar 2)

7. ## Membuat dokuman HTML di file yang sudah dibuat yaitu lab4_box.html dengan cara seperti yang dijelaskan di No. 6 point 4 (Gambar 1) > ketik html > pilih html:5 (Gambar 1), lalu akan tampil seperti pada gambar (Gambar 2), setelah itu nama Document diganti dengan Box Element serta menambahkan kepala halaman (header) untuk menaruh judul atau navigasi atas seperti pada gambar. (Gambar 3), lalu klik Ctrl-S (Save) setiap saat setelah memasukan kode.

    <img src="images/Gambar 18.jpg" width="500">
                (Gambar 1)

    <img src="images/Gambar 19.jpg" width="500">
                (Gambar 2)

    <img src="images/Gambar 20.jpg" width="500">
                (Gambar 3)

    Penjelasan dari setiap kodenya:
    - **** - <!DOCTYPE html>: Penanda bahwa file ini menggunakan format HTML5.
    - **** - <html lang="en">: Wadah utama dokumen dengan pengaturan bahasa Inggris.
    - **** - <head>: Area penyimpanan informasi pendukung/metadata web.
    - **** - <meta charset="UTF-8">: Pengatur standar jenis karakter agar teks dan simbol tampil akurat.
    - **** - <meta name="viewport" ...>: Pengatur agar tampilan web fleksibel di berbagai ukuran layar perangkat.
    - **** - <title>: Pemberi nama judul pada tab browser.
    - **** - <body>: Tempat seluruh isi dan konten utama halaman web.
    - **** - <header>: Bagian kepala halaman untuk menaruh judul atau navigasi atas.
    - **** - <h1>: Judul utama teks berukuran besar.

    ## Hasilnya
    <img src="images/Gambar 21.jpg" width="500">

8. ## Membuat box element dengan tag div.

    <img src="images/Gambar 22.jpg" width="500">

    Penjelasan dari setiap kodenya:
    - **** - <section>: Merupakan elemen semantik HTML5 yang digunakan untuk mengelompokkan bagian atau section tertentu dari sebuah halaman web yang memiliki keterkaitan topik (dalam hal ini, wadah untuk menampung kotak-kotak div latihan layout).
    - **** - <div class="div1">Div 1</div> (hingga div4): Merupakan elemen division (<div>) yang berfungsi sebagai kontainer atau kotak generik. Masing-masing diberikan atribut class (div1, div2, div3, dan div4) agar nantinya dapat dengan mudah diberi gaya (styling) atau diatur tata letaknya secara spesifik menggunakan CSS.

    ## Hasilnya
    <img src="images/Gambar 23.jpg" width="500">

9. ## Menambahkan deklarasi CSS pada head untuk membuat float.

    <img src="images/Gambar 24.jpg" width="500">

    Penjelasan dari setiap kode:
    1. Selector Umum (div)
        - **** - float: left;: Membuat seluruh elemen <div> tersusun berderet ke samping dari kiri ke kanan secara mengapung.
        - **** - padding: 10px;: Memberikan jarak ruang di dalam kotak antara isi teks dengan tepi batas kotaknya.
        - **** - width: 100px; & height: 100px;: Menetapkan ukuran lebar dan tinggi kotak menjadi 100 piksel persegi secara seragam.
        - **** - color: white;: Mengubah warna dasar teks di dalam kotak menjadi putih.
        - **** - font-weight: bold;: Menebalkan tampilan teks.
        - **** - box-sizing: border-box;: Memastikan ukuran padding sudah termasuk di dalam total lebar dan tinggi 100px, sehingga kotak tidak menjadi lebih besar dari yang ditentukan.

    2. Selector Spesifik Kelas Warna
        - **** - .div1 { background-color: red; } yaitu memberikan warna latar belakang merah khusus untuk kotak pertama (div1). Teks otomatis berwarna putih mengikuti aturan umum di atas.
        - **** - .div2 { background-color: orange; color: black; } yaitu Memberikan warna latar belakang oranye untuk kotak kedua (div2). Properti color: black ditulis di sini untuk menimpa warna teks umum, sehingga teks di dalam kotak oranye ini berwarna hitam agar mudah dibaca.
        - **** - .div3 { background-color: green; } yaitu memberikan warna latar belakang hijau untuk kotak ketiga (div3).

    3. Pengaturan Khusus Div 4 (.div4)
        - **** - background-color: blue;: Memberikan warna latar belakang biru untuk kotak keempat (div4).
        - **** - float: none;: Membatalkan sifat mengapung (float) khusus untuk kotak keempat ini. Karena sifat float-nya dinonaktifkan, .div4 tidak akan ikut berderet ke samping bersama div1, div2, dan div3, melainkan akan berulah sesuai perilaku elemen blok normal (cenderung menumpuk atau turun ke bawah tergantung struktur dokumen).

    ## Hasilnya
    <img src="images/Gambar 25.jpg" width="500">

10. ## Mengatur Clearfix Element
    Clearfix digunakan untuk mengatur element setelah float element. Property clear digunakan untuk mengaturnya. Tambahkan element div lainnya seteleah div3 sebagai berikut:

    <img src="images/Gambar 26.jpg" width="500">

    - **** -Kemudian atur property clear pada CSS, seperti berikut:

    <img src="images/Gambar 27.jpg" width="500">

    ## Hasilnya
    <img src="images/Gambar 28.jpg" width="500">

11. ## Lakukan eksperimen terhadap penggunaan property clear dengan nilai lainnya (left, both, right), dan amati perubahannya.

    <img src="images/Gambar 29.jpg" width="500">

    Penjelasan dari setiap kodenya:
    1. Alur Tampilan & Perilaku Layout (Tata Letak)
        - **** - Div 1, Div 2, dan Div 3 (Berderet ke Samping), karena elemen div secara umum diatur dengan float: left;, maka kotak Div 1 (Merah), Div 2 (Oranye), dan Div 3 (Hijau) akan ditarik agar berderet sejajar secara horizontal dari kiri ke kanan (selama ruang lebar layarnya masih mencukupi). Masing-masing kotak berukuran persis 100×100 piksel.
        - **** - Div 4 (Kasus Khusus float: none;), Meskipun elemen div secara umum terkena aturan float: left;, kotak Div 4 (Biru) memiliki aturan spesifik float: none;.
            - **** - Karena sifat float-nya dimatikan, Div 4 tidak akan ikut berderet sejajar bersama Div 1, Div 2, dan Div 3 di sebelah kanan.
            - **** - Sebaliknya, Div 4 akan berperilaku sebagai elemen blok normal yang posisinya berada di bawah atau "menumpuk" di balik area kotak-kotak yang melayang di atasnya, karena elemen pembungkus <section> tidak ikut menampung (clear) tinggi dari elemen-elemen float tersebut.

    2. Rangkuman Gaya Visual per Kotak
        - **** - Div 1: Kotak merah dengan teks putih tebal.
        - **** - Div 2: Kotak oranye dengan teks hitam tebal (karena ada penulisan color: black; yang menimpa warna putih bawaan).
        - **** - Div 3: Kotak hijau dengan teks putih tebal.
        - **** - Div 4: Kotak biru dengan teks putih tebal dan sifat float dinonaktifkan (float: none;).

    ## Hasilnya
    <img src="images/Gambar 30.jpg" width="500">
12. ## Setelah semua kode program prakktikum dimasukkan lalu simpan program di github dengan cara sebagai berikut:
    - **** - Masuk ke folder Lab4Web melalui git bash, lalu ketik cd /d/Labs/Lab4Web untuk file yang akan dituju yaitu lab4_box.html yang ada di Lab4Web seperti (gambar 1)

        <img src="images/Gambar 31.jpg" width="500">

    - **** - Setelah itu ketik git add lab4_box.html untuk masuk ke file lab4_box.html

        <img src="images/Gambar 32.jpg" width="500">

    - **** - Lalu ketik git status untuk mengecek apakah ada yang di modifikasi.

        <img src="images/Gambar 33.jpg" width="500">
        
    - **** - Lalu ketik git commit -m “Menambahkan file lab4_box.html” digunakan dalam Git untuk menyimpan riwayat perubahan (snapshot) dari berkas-berkas yang telah Anda siapkan ke dalam repositori lokal, disertai dengan pesan penjelas.

        <img src="images/Gambar 34.jpg" width="500">

    - **** - Lalu ketik git push -u origin main digunakan untuk mengunggah (upload) kode atau perubahan dari repositori lokal komputer Anda ke repositori jarak jauh (remote) di GitHub, sekaligus menghubungkan cabang lokal tersebut agar terhubung secara permanen.

        <img src="images/Gambar 35.jpg" width="500">

    ## Hasil penyimpanan di GitHub
    
    <img src="images/Gambar 36.jpg" width="500">
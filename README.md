# PENJELASAN

![https://github.com/razyyalfarisi/foto/blob/40f2cc0671941b3023ef44efc14405fda1188d17/Screenshot%202025-10-15%20230810.png]

`<header>`  bagian atas halaman berisi judul situs dan menu navigasi (Home, Artikel, About, Kontak).

`<section class="hero">` bagian pengantar dengan teks dan tombol “Learn more”.

`<section class="main">` area utama halaman.

`.content` berisi konten utama seperti tiga kotak fitur (lingkaran warna + teks).

`.featurette`m bagian deskripsi dengan gambar 150×150 dan teks di sampingnya.

`<aside class="sidebar">`  area samping kanan berisi widget link dan teks tambahan.

`<footer>` bagian bawah halaman berisi hak cipta “© 2021 - Universitas Pelita Bangsa”.

File CSS (`style.css`) digunakan untuk mengatur tampilan, warna, layout, dan posisi tiap elemen agar rapi dan menarik.

### home

![https://github.com/razyyalfarisi/foto/blob/c3c5438887d7b0dec9953b8155cfcf95553ce72b/Screenshot%202025-10-15%20234342.png]


# PENJELASAN css

### Header/navigasi

`header` area atas berwarna biru (`#007acc`), teks putih, dan padding supaya isi tidak menempel tepi.

`header h1` → menghilangkan margin pada judul.

`nav` memberi jarak atas dari judul.

`nav a` membuat link putih tanpa garis bawah dan memberi jarak antar-link 15px.

### hero

`.hero` latar abu muda dengan padding, biasanya berisi teks pengantar atau tombol.

### Bagian Utama

`.main`  menggunakan flexbox agar konten dan sidebar sejajar secara horizontal, dan bisa turun ke bawah jika layar kecil (flex-wrap).

`.content` area utama (kiri) dengan porsi lebih besar (`flex: 3`).

 `.row` dan `.box`

`.row` menyusun beberapa kotak sejajar, jarak antar kotak diatur space-between.

`.box` setiap kotak fitur (lebar 30%, teks rata tengah).

 `.circle`

Membuat lingkaran berwarna (`120x120px`), teks di tengah dengan line-height sama seperti tinggi.

Warna:

`.orange` oranye `#f37a2a`

`.blue` biru `#357edd`

`.green` hijau muda `#5ad2c1`

![https://github.com/razyyalfarisi/foto/blob/d08d2a6f9854d14125fd69be7094516500201704/Screenshot%202025-10-15%20233520.png]

`<div class="container">` wadah seluruh isi halaman.

`<header>` bagian atas berisi judul dan menu navigasi (Home, About, Contact).

`<main>` isi utama berupa formulir kontak dengan input nama, email, dan pesan. Tombol “Kirim” digunakan untuk mengirim data.

`<footer>`  bagian bawah halaman dengan teks hak cipta “© 2025 - Universitas Pelita Bangsa”.

![https://github.com/razyyalfarisi/foto/blob/c4518e40d4d4340a388ba3599d1b7cf62e50b262/Screenshot%202025-10-15%20233828.png]

`<section>` pertama berisi deskripsi singkat tentang diri.

`<section>` kedua → menampilkan daftar proyek (portfolio).

`<footer>` bagian bawah dengan teks hak cipta “© 2025 - Universitas Pelita Bangsa”.

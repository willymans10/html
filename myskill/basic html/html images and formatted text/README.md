# HTML Images and Formatted Text

Materi kali ini akan membawa kamu memperdalam tentang images/gambar dalam membuat sebuah website menggunakan HTML. Kamu akan mempelajari untuk menambahkan images/gambar pada halaman profil dan formatted text yang akan menambahkan nuansa pada website yang telah kamu buat.

## Gambar (images)

**HTML images** merujuk kepada gambar atau konten visual yang dapat di tampilkan di halaman web

### Keterangan Atribut Dasar img (Basic Attributes Img)

```
src : Atribut yang berfungsi untuk mengatur sumber file dari konten gambar

alt : Atribut yang berfungsi untuk menambahkan sebuah teks deskripsi untuk sebuah konten gambar, atribut ini membantu pengguna yang tidak dapat melihat gambar dengan jelas, seperti gambar gagal dimuat

width : Atribut yang berfungsi untuk mengatur ukuran dimensi lebar dari gambar

height : Atribut yang berfungsi untuk mengatur ukuran dimensi tinggi dari gambar
```

### Elemen Gambar (img)

- Contoh penggunaan elemen img dengan atribut src dengan sumber gambar berada di luar folder

```
<img src="nama_gambar" alt="alternatif_teks" width="ukuran_lebar" height="ukuran_tinggi">

<img src="image.png" alt="profile picture" width="50px" height="50px">
```

- Contoh penggunaan elemen img dengan atribut src dengan sumber gambar berada di dalam folder

```
<img src="nama_folder/nama_gambar" alt="alternatif_teks" width="ukuran_lebar" height="ukuran_tinggi">

<img src="assets/image.png" alt="profile picture" width="50px" height="50px">
```

- Contoh penggunaan elemen img dengan atribut src dengan sumber gambar berada di internet

```
<img src="url_gambar" alt="alternatif_teks" width="ukuran_lebar" height="ukuran_tinggi">

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/1200px-HTML5_logo_and_wordmark.svg.png" alt="profile picture" width="50px" height="50px">
```

## Formatted Text

**Formatted text** merujuk kepada teks yang telah diatur atau diformat dengan cara tertentu untuk menambahkan gaya, tata letak, atau penekanan tertentu.

## Elemen Teks Format Dasar (Basic Formatted Text Elements)

```
1. Figcaption : Elemen yang berfungsi untuk menyediakan deskripsi atau keterangan untuk konten gambar pada elemen <figure>

2. Blockquote : Elemen yang berfungsi untuk menampilkan teks kutipan dari sebuah sumber

2. Pre : Elemen yang berfungsi untuk menampilkan teks asli dari code secara utuh sebelum dilakukan format teks
```

### Contoh Elemen Teks Format Dasar (Basic Formatted Text Elements)

- Contoh penggunaan elemen figcaption

```
    <figure>
        <img src="url_gambar" alt="nama_alternatif" width="ukuran_lebar" height="ukuran_tinggi">
        <figcaption>Isi caption</figcaption>
    </figure>
```

- Contoh penggunaan elemen blockquote

```
    <blockquote cite="nama_url">
        <p>Isi teks kutipan</p>
    </blockquote>
```

- Contoh penggunaan elemen pre

```
    <pre>
        Isi teks
    </pre>
```

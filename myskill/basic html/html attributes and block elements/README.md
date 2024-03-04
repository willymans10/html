# HTML Attributes and Block Elements

Dalam materi ini, Kamu selanjutnya akan belajar mengenai atribut Html, paragraf, heading,list serta menambahkan list pada halaman profil. Kamu akan bisa lebih bebas dalam mengekspresikan kreativitas kamu dalam membuat website.

## Atribut HTML (Attribute HTML)

**Atribut HTML** berfungsi untuk memberikan informasi tambahan pada sebuah elemen. Atribut dituliskan pada tag pembuka dari sebuah elemen.

### Keterangan Atribut Dasar HTML (Basic HTML Attributes)

```
href : Atribut ini dipakai pada tag <a>, berfungsi untuk menentukan halaman yang akan dituju

src : Atribut ini dipakai pada tag <img>, berfungsi untuk menentukan jalur gambar yang akan ditampilkan

width dan height : Atribut ini dipakai pada tag <img>, berfungsi untuk mengatur ukuran gambar

alt : Atribut ini dipakai pada tag <img>, berfungsi sebagai teks alternatif untuk gambar

style : Berfungsi untuk menambahkan sebuah style CSS ke dalam elemen, seperti color, font, size, dan yang lainnya

lang : Atribut ini dipakai pada tag <html>, berfungsi untuk menyatakan bahasa halaman web

title : Berfungsi mendefinisikan beberapa informasi tambahan tentang suatu elemen
```

- Contoh penggunaan atribut HTML

```
<element_name attribute_name = "attribute_value"></element_name>

<nama_elemen nama_atribut = "nilai_atribut"></nama_elemen>

<p lang="eng"></p>
```

## Elemen Blok (Block Element)

```
Paragraf : Berfungsi untuk mengelompokkan teks yang berkaitan menjadi paragraf atau blok teks tunggal

Heading : Befungsi untuk membuat judul atau kepala teks, Elemen heading diwakili oleh tag <h1> hingga <h6>

List : Berfungsi untuk mengelompokkan dan menampilkan item atau informasi dalam bentuk daftar

List terbagi menjadi 2 jenis, yaitu :

1. Ordered lists adalah sebuah daftar yang ditampilkan secara terurut, biasanya menggunakan penomoran
2. Unordered lists adalah sebuah daftar yang ditampilkan tidak memiliki urutan, biasanya menggunakan simbol
```

### Contoh Elemen Block (Block Element)

- Contoh paragraf

```
<p>Isi paragraf</p>
```

- Contoh heading

```
<h1>Ini adalah heading 1</h1>
<h2>Ini adalah heading 2</h2>
<h3>Ini adalah heading 3</h3>
<h4>Ini adalah heading 4</h4>
<h5>Ini adalah heading 5</h5>
<h6>Ini adalah heading 6</h6>
```

- Contoh list

```
1. Ordered lists

<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>

2. Unordered lists

<ul>
  <li>Item A</li>
  <li>Item B</li>
  <li>Item C</li>
</ul>
```

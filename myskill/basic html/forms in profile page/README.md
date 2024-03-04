# Forms in Profile Page

Materi ini akan membuat kamu mempelajari tentang HTML Forms, hingga Elemen dalam Forms Input. Kamu akan bisa membuat Forms pada halaman profil website yang kamu buat setelah mempelajari materi ini.

## Forms

**Forms** adalah elemen yang digunakan untuk membuat formulir atau kumpulan elemen interaktif yang memungkinkan pengguna mengirimkan data informasi ke server.

### Struktur Dasar Form (Basic Structure of Forms)

```
<form action="" method="GET/POST">

    <label for="nama_input">Isi label</label>
    <input type="text/password/email/submit" id="nama_id" name="nama_input" value="Isi_value">

</form>
```

### Keterangan Elemen Dalam Forms

|  Elemen  |                              Keterangan                               |
| :------: | :-------------------------------------------------------------------: |
|  input   |  Membuat berbagai jenis input, seperti teks, password, dan lain-lain  |
|  label   |                 Menampilkan label untuk elemen input                  |
|  select  |               Membuat menu dropdown atau daftar pilihan               |
|  option  |             Mendefinisikan pilihan dalam elemen 'select'              |
| textarea | Membuat area teks yang lebih besar, seperti kotak komentar atau pesan |
|  button  |                     Membuat tombol di dalam forms                     |

### Contoh Penggunaan Elemen Form

- Contoh penggunaan input

```
<input type="tipe_input" name="nama_input" value="value_input">

<input type="text" name="username" value="username">

```

- Contoh penggunaan label

```
<label for="nama_input">Isi label</label>

<label for="username">Username</label>
```

- Contoh penggunaan select

```
<select name="nama_select">
    <!-- Isi elemen option -->
</select>

<select name="kategori">
    <!-- Isi elemen option -->
</select>
```

- Contoh penggunaan option

```
<select name="nama_select">
    <option value="nilai_option">Isi option</option>
</select>

<select name="kategori">
    <option value="kategori">Kategori</option>
</select>
```

- Contoh penggunaan textarea

```
<textarea name="nama_textarea" cols="jumlah_kolom" rows="jumlah_baris">Isi textarea</textarea>

<textarea name="alamat" cols="10" rows="30">Alamat</textarea>
```

- Contoh penggunaan button

```
<button type="tipe_button">Isi button</button>

<button type="button/submit/reset">Isi button</button>
```

## Input

**Input** adalah elemen yang digunakan untuk membuat berbagai jenis input atau kotak isian yang memungkinkan pengguna memasukkan data, seperti teks, kata sandi, angka, kotak centang, dan banyak lagi.

### Tipe Input (Input Type)

|   Type   |   Type    |
| :------: | :-------: |
|  button  |   image   |
| checkbox |   month   |
|  color   |  number   |
|   date   | password' |
|  email   |   radio   |
|   file   |   range   |
|  reset   |  submit   |
|  search  |   text    |

## Contoh Penggunaan Tipe Input

- Contoh penggunaan input tipe button

```
<input type="tipe_input" name="nama_input">

<input type="button" name="usernabuttonme">
```

- Contoh penggunaan input tipe checkbox

```
<input type="tipe_input" name="nama_input" value="value_input">

<input type="checkbox" name="checkbox" value="pilihan">
```

- Contoh penggunaan input tipe color

```
<input type="tipe_input" name="nama_input" value="value_input">

<input type="color" name="color" value="#fff">
```

- Contoh penggunaan input tipe date

```
<input type="tipe_input" name="nama_input" value="value_input">

<input type="date" name="date" value="2023-08-15">
```

- Contoh penggunaan input tipe email

```
<input type="tipe_input" name="nama_input" value="value_input">

<input type="email" name="email" value="email">
```

- Contoh penggunaan input tipe file

```
<input type="tipe_input" name="nama_input" value="value_input">

<input type="file" name="picture" value="picture">
```

- Contoh penggunaan input tipe reset

```
<input type="tipe_input" name="nama_input" value="value_input">

<input type="reset">
```

- Contoh penggunaan input tipe search

```
<input type="tipe_input" name="nama_input" placeholder="isi_placehoder">

<input type="search" name="search" placeholder="search">
```

- Contoh penggunaan input tipe image

```
<input type="tipe_input" src="url_gambar" name="nama_input" alt="nama_alternatif">

<input type="image" src="asset/image.png" name="image" alt="pencarian image">
```

- Contoh penggunaan input tipe month

```
<input type="tipe_input" name="nama_input">

<input type="month" name="month">
```

- Contoh penggunaan input tipe number

```
<input type="tipe_input" name="nama_input">

<input type="number" name="number">
```

- Contoh penggunaan input tipe password

```
<input type="tipe_input" name="nama_input" placeholder="isi_placehoder">

<input type="password" name="password" placeholder="Masukan password">
```

- Contoh penggunaan input tipe radio

```
<input type="tipe_input" name="nama_input">

<input type="radio" name="radio">
```

- Contoh penggunaan input tipe range

```
<input type="tipe_input" name="nama_input" min="nilai_minimum" max="nilai_maksimum">

<input type="range" name="range" min="0" max="100">
```

- Contoh penggunaan input tipe submit

```
<input type="tipe_input" name="nama_input">

<input type="submit">
```

- Contoh penggunaan input tipe text

```
<input type="tipe_input" name="nama_input" placeholder="isi_placehoder">

<input type="text" name="username" placeholder="Masukan username">
```

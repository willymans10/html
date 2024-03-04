# Table in Profile Page

Materi kali ini akan membahas materi mengenai salah satu elemen dasar yaitu Tabel. Lebih lanjut, kamu akan belajar Struktur Dasar Sebuah Tabel, Spanning Cell, Elemen dan Atribut Pada Tabel, dan Membuat Tabel Pada Halaman Profil. Kamu akan memperkaya pemahaman kamu untuk memodifikasi kebutuhan tabel pada website yang kamu buat.

## Table

**Table** merupakan elemen yang digunakan untuk menampilkan konten data atau informasi yang disajikan melalui sebuah tabel. Tabel terbentuk dalam dua dimensi yang terdiri dari baris dan kolom dengan berisi sebuah data di dalamnya.

### Struktur Dasar Table

| Header cell k-1 | Header cell k-2 | Header cell k-3 |
| :-------------: | :-------------: | :-------------: |
| Data cell 1 - 1 | Data cell 1 - 2 | Data cell 1 - 3 |
| Data cell 2 - 1 | Data cell 2 - 2 | Data cell 2 - 3 |

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

    <table>
        <thead>
            <tr>
                <th>Header cell k-1</th>
                <th>Header cell k-2</th>
                <th>Header cell k-3</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Data cell 1 - 1</td>
                <td>Data cell 1 - 2</td>
                <td>Data cell 1 - 3</td>
            </tr>
            <tr>
                <td>Data cell 2 - 1</td>
                <td>Data cell 2 - 2</td>
                <td>Data cell 2 - 3</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
```

## Penggabungan Sel Rabel (Spanning Cell)

**Spanning cell** merupakan proses menggabungkan beberapa sel menjadi satu dalam tabel. Ini membuat tampilan yang lebih luas, contohnya seperti menggabungkan 2 kolom.

### Tipe Penggabungan Sel Rabel (Spanning Cell)

Terdapat 2 tipe Penggabungan sel tabel (Spanning Cell), yaitu :

1. Column spans (colspan) : Atribut yang digunakan untuk menambahkan kolom (Secara horizontal)
2. Row spans (rowspan) : Atribut yang digunakan untuk menambahkan baris (Secara vertikal)

## Elemen dan Atribut Tabel

|  Elemen dan Atribut   |                      Keterangan                       |
| :-------------------: | :---------------------------------------------------: |
|         table         |             Menetapkan elemen pada tabel              |
|         thead         |     Mengelompokkan baris-baris yang berisi judul      |
|         tbody         |      Mengelompokkan baris-baris yang berisi data      |
|         tfoot         |  Menujukan hubungan antara sel dengan elemen header   |
|        caption        |        Menandai bagian penutup atau kaki tabel        |
|     tr(table row)     |          Menetapkan sebuah baris pada tabel           |
|    th(table head)     |          Menetapkan sebuah header pada tabel          |
|    td(table data)     |     Menetapkan sebuah sel dalam baris pada tabel      |
|   colspan="jumlah"    | Menggabungkan kolom yang dicakup oleh sel atau header |
|   rowspan="jumlah"    | Menggabungkan baris yang dicakup oleh sel atau header |
| headers="nama_header" |  Menujukan hubungan antara sel dengan elemen header   |

### Contoh Penggunaan Elemen Tabel

- Contoh penggunaan table (table)

```
<table>
    <!-- Elemen pembangun table seperti caption, thead, tbody, tr, th, dan td -->
</table>

<table>
    <tr>
        <th>Header</th>
    </tr>
    <tr>
        <td>Data</td>
    </tr>
</table>
```

- Contoh penggunaan caption (caption)

```
<table>
    <caption>Judul tabel</caption>
    <!-- Elemen pembangun table seperti thead, tbody, tr, th, dan td -->
</table>

```

- Contoh penggunaan table head, table body, table foot (thead, tbody, tfoot)

```
<table>
    <thead>
        <tr>
            <!-- Elemen pembangun table seperti tr, th, dan td -->
        </tr>
    </thead>
    <tbody>
        <!-- Elemen pembangun table seperti tr, th, dan td -->
    </tbody>
    <tfoot>
        <!-- Elemen pembangun table seperti tr, th, dan td -->
    </tfoot>
</table>

<table>
    <thead>
        <tr>
            <th>Header</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Data</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>Jumlah Data</td>
        </tr>
    </tfoot>
</table>
```

- Contoh penggunaan table row, table header, dan table data (tr, th, dan td)

```
<table>
     <thead>
        <!-- Elemen pembangun table seperti tr, th, dan td -->
     </thead>
     <tbody>
        <!-- Elemen pembangun table seperti tr, th, dan td -->
     </tbody>
     <tfoot>
        <!-- Elemen pembangun table seperti tr, th, dan td -->
     </tfoot>
</table>

<table>
    <thead>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
            <th>Header 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Data 1 - 1</td>
            <td>Data 1 - 2</td>
            <td>Data 1 - 3</td>
        </tr>
        <tr>
            <td>Data 2 - 1</td>
            <td>Data 2 - 2</td>
            <td>Data 2 - 3</td>
        </tr>
        <tr>
            <td>Data 3 - 1</td>
            <td>Data 3 - 2</td>
            <td>Data 3 - 3</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>Jumlah Data</td>
            <td>Jumlah Data</td>
            <td>Jumlah Data</td>
        </tr>
    <tfoot>
</table>
```

### Contoh Pneggunaan Atribut Penggabungan Sel Tabel (Spanning Cell)

- Contoh penggunaan column spans (colspan)

```
<tr>
    <td colspan="jumlah_penggabungan">Data cell 1 - 1</td>
    <td>Data cell 1 - 2</td>
    <td>Data cell 1 - 3</td>
</tr>

<tr>
    <td colspan="2">Data cell 1 - 1</td>
    <td>Data cell 1 - 2</td>
    <td>Data cell 1 - 3</td>
</tr>
```

- Contoh penggunaan row spans (rowspan)

```
<tr>
    <td rowspan="jumlah_penggabungan">Data cell 1 - 1</td>
    <td>Data cell 1 - 2</td>
    <td>Data cell 1 - 3</td>
</tr>

<tr>
    <td rowspan="2">Data cell 1 - 1</td>
    <td>Data cell 1 - 2</td>
    <td>Data cell 1 - 3</td>
</tr>
```

- Contoh penggunaan headers (headers)

```
<thead>
<tr>
    <th headers="nama_header">Header 1</th>
</tr>
</thead>

<tbody>
<tr>
    <td headers="nama_header_referensi">Header 1</td>
</tr>
</tbody>

<thead>
    <tr>
        <th headers="header_1">Header 1</th>
    </tr>
</thead>

<tbody>
    <tr>
        <td headers="header_1">Header 1</td>
    </tr>
</tbody>
```

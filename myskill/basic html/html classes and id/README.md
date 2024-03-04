# HTML Classes and ID

Materi selanjutnya akan membuat kamu belajar tentang Html Classes and id. Kamu akan memperdalam mengenai Using Class Attribute, Syntax for Class, Using Id Attribute,Perbedaan Class dan Id. Kamu akan bisa melakukan spesifikasi class pada elemen website yang kamu buat.

## Class

**Class** adalah sebuah atribut yang digunakan untuk memberikan mengelompokan elemen dengan gaya yang sama. Nama class dapat digunakan ke beberapa elemen

### Struktur Dasar Class (Class Basic Structure)

```
<p class="class_name">Content</p>

<p class="nama_class">Konten</p>

<p class="paragraph">Hello world</p>
```

## Id

**Id** adalah sebuah atribut yang digunakan untuk memberikan identifikasi unik kepada elemen tertentu. Setiap id hanya boleh digunakan sekali dalam satu halaman

### Struktur Dasar Id (Id Basic Structure)

```
<p id="id_name">Content</p>

<p id="nama_id">Konten</p>

<p id="paragraph">Hello world</p>
```

## Penggunaan Class dan Id

- Contoh penggunaan class

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<style>

    .city{
        background-color: green;
        color: white;
        border: 2px solid black;
        margin: 20px;
        padding: 20px;
    }

</style>

<body>

    <div class="city">
        <h2>Hello world!</h2>
    </div>

    <div class="city">
        <h2>How are you?</h2>
    </div>

</body>
</html>
```

- Contoh penggunaan id

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<style>

    #myHeader{
        background-color: blue;
        color: white;
        padding: 40px;
        text-align: center;
        border: 2px solid black;
    }

    #myParagraph{
        background-color: blanchedalmond;
        color: black;
        padding: 20px;
        margin: 20px;
        border: 2px solid blue;
    }

</style>

<body>

    <h1 id="myHeader">Hello world</h1>

    <p id="myParagraph">How are you?</p>

</body>
</html>
```

- Contoh penggunaan class dan id

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<style>

    .city{
        background-color: green;
        color: white;
        border: 2px solid black;
        margin: 20px;
        padding: 20px;
    }

    .boxed{
        background-color: brown;
        color: white;
        padding: 15px;
        margin: 15px;
        border: 2px solid blanchedalmond;
    }

    #myHeader{
        background-color: blue;
        color: white;
        padding: 40px;
        text-align: center;
        border: 2px solid black;
    }

    #myParagraph{
        background-color: blanchedalmond;
        color: black;
        padding: 20px;
        margin: 20px;
        border: 2px solid blue;
    }

</style>

<body>

    <h1 id="myHeader">Nama kota di Indonesia</h1>

    <div class="city">
        <h2>Bandung</h2>
        <p>Bandung adalah ibu kota Jawa Barat</p>
    </div>

    <div class="city">
        <h2>Medan</h2>
        <p>Medan adalah ibu kota Sumatera Utara</p>
    </div>

    <div class="city">
        <h2>Surabaya</h2>
        <p>Surabaya adalah ibu kota Jawa Timur</p>
    </div>

    <p id="myParagraph">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit.
        Eum tempora magnam earum quod perspiciatis temporibus alias suscipit, vero magni corporis.
    </p>

    <p class="boxed">Lorem ipsum dolor sit amet consectetur adipisicing elit.
        Asperiores quis consequatur sed ipsum mollitia suscipit?
    </p>

</body>
</html>
```

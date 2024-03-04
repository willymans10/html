# Semantic HTML and Generic Element

Pada materi ini kamu akan belajar mengenai Pengenalan Semantic HTML Header dan Footer. Kamu juga akan mempelajari berbagai elemen seperti Main,Nav,Generic Element,Articles, Aside, Section pada bagian HTML. Sehingga memudahkan kamu dalam mengetahui unsur dalam memodifikasi elemen Semantic HTML pada website kamu.

## Semantic HTML

**Semantic HTML** adalah tag-tag yang memberikan arti atau makna terhadap struktur dan konten halaman web

### Elemen Semantic HTML

```
<header></header> : Elemen ini digunakan untuk mengelompokkan bagian pengantar atau kepala dari halaman web

<nav></nav> : Elemen ini digunakan untuk mengelompokkan bagian menu navigasi yang membantu pengguna berpindah antara halaman atau bagian berbeda dalam sebuah situs web

<footer></footer> : Elemen ini digunakan untuk mengelompokkan bagian penutup atau kaki dari halaman web

<main></main> : Elemen ini digunakan untuk mengelompokkan bagian utama dari halaman web

<article></article> : Elemen ini digunakan untuk mengelompokkan sebuah konten seperti artikel, blog, atau berita

<aside></aside> : Elemen ini digunakan untuk mengelompokkan informasi tambahan, tautan terkait, atau elemen lain yang tidak harus ditempatkan dalam konten utama

<section></section> : Elemen ini digunakan untuk membedakan section dari file atau tampilan website yang sedang dibuat
```

### Contoh Elemen Semantic HTML

- Contoh penggunaan elemen header

```
<header>Isi konten header</header>

<header>
    <h1>Isi Heder</h1>
    <p>Isi paragraf</p>
    <nav>
        <ul>
            <li>
                <a href="#">Value</a>
            </li>
        </ul>
    </nav>
</header>
```

- Contoh penggunaan elemen footer

```
<footer>Isi konten footer</footer>

<footer>&copy; tahun, nama</footer>
```

- Contoh penggunaan elemen main

```
<main>Isi konten footer</main>

<main>
    <section>
        <article>
            <p>This is an article</p>
        </article>
    </section>

    <article>
         <p>This is another article</p>
    </article>
</main>
```

- Contoh penggunaan elemen nav

```
<nav>isi konten nav berupa logo dan hyperlink </nav>

    <nav>
        <ul>
            <li>
                <a href="#">Item 1</a>
            </li>
            <li>
                <a href="#">Item 2</a>
            </li>
            <li>
                <a href="#">Item 31</a>
            </li>
        </ul>
    </nav>
```

- Contoh penggunaan elemen article

```
<article>Isi konten article</article>

<article>
    <h2>Isi konten H2</h2>
    <img src="url_image" alt="nama_alternatif" width="ukuran_lebar">
    <p>
        Isi konten paragraf
    </p>
</article>
```

- Contoh penggunaan elemen aside

```
<aside>Isi konten aside</aside>

<aside>
    <article>
        <header>
            <h2>Isi konten H2</h2>
            <p>
                Isi konten paragraf
            </p>
            <figure>
                <img src="url_image" alt="nama_alternatif">
                <figcaption>Isi konten figcaption</figcaption>
            </figure>
        </header>
    </article>
</aside>

```

- Contoh penggunaan elemen section

```
<section>Isi konten section</section>

<section>
    <article>
        <p>This is an article</p>
    </article>
</section>
```

## Generic Element

**Generic element** adalah elemen-elemen yang digunakan untuk membentuk struktur dasar halaman web, tetapi tidak memberikan informasi tambahan tentang konten yang mereka bungkus.

### Elemen Generic Element

```
<div></div> : Elemen ini digunakan sebagai sebuah wadah (container) yang bersifat umum untuk menampung beberapa konten

<span></span> : Elemen ini digunakan menerapkan gaya atau pemformatan khusus pada sebagian teks tertentu
```

### Contoh Generic Element

- Contoh penggunaan elemen div

```
<div>Ini adalah div</div>

<div>
    PHP
</div>
```

- Contoh penggunaan elemen span

```
<span>isi konten span</span>

<span>JavaScript</span>
<span>Python</span>
```

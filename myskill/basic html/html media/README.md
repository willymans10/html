# HTML Media

Bagian akhir dari rangkaian materi ini akan membantu kamu dalam membuat website kamu semakin interaktif. Kamu akan memperdalam HTML media meliputi pembahasan tentang Pengenalan Media, HTML Video, HTML Audio, dan HTML Youtube.

## HTML Media

**HTML Media** adalah suatu cara untuk untuk menyertakan berbagai macam jenis media, seperti gambar, video, animasi, audio, atau objek lainnya

### Elemen HTML Media (Html Media Elements)

```
<video></video> : Elemen yang digunakan untuk menyisipkan video

<iframe></iframe> : Elemen yang digunakan untuk menyisipkan video yang bersumber dari youtube

<audio></audio> : Elemen yang digunakan untuk menyisipkan audio
```

### Contoh Penggunaan HTML Media

- Contoh penggunaan elemen video

```
    <video>
        <source src="video_url" type="video_format_type">
    </video>

    <video>
        <source src="url_video" type="tipe_format_video">
    </video>

    <video>
        <source src="asset/video.mp4" type="video/mp4">
    </video>
```

- Contoh penggunaan elemen iframe

```
    <iframe
        width="lebar_video"
        height="tinggi_video"
        src="url_video_youtube"
        title="tudul"
        frameborder="ukuran_garis_pembatas"
        allow="perizinan_fitur" allowfullscreen>
    </iframe>

    <iframe
        width="video_width"
        height="video_height"
        src="youtube_video_urls"
        title="title"
        frameborder="border_size"
        allow="permission" allowfullscreen>
    </iframe>

    <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/oL9lnwW5Tpw"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen>
    </iframe>
```

- Contoh penggunaan elemen audio

```
    <audio controls>
        <source src="audio_url" type="video_format_type">
    </audio>

    <audio controls>
        <source src="url_audio" type="tipe_format_video">
    </audio>

    <audio controls>
        <source src="assets/audio.mp3" type="audio/mpeg">
    </audio>

```

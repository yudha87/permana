# bitmyid Bio Link

## Mau Berkontribusi

1. Fork repository ini.
1. `git push` perubahan yang baru dilakukan, selanjutnya silahkan buka **Pull Request** baru.

## Cara Membuat Bio Link Milik Anda

Langkahnya sebagai berikut,

1. Fork repository ini.
1. Buat konten baru dengan perintah `hugo new content namalink.en.html` (untuk halaman Bahasa Inggris) dan `hugo new content namalink.id.html` (untuk Bahasa Indonesia). Atau dengan cara manual, buat file baru bernama `namalink.en.html` dan `namalink.id.html` pada folder `/content`.
   > Ganti `namalink` sesuai selera. Nama file ini akan digunakan pada nama link nanti. Contoh: `https://bit.my.id/namalink`
1. Edit isi file `namalink.en.html` dan `namalink.id.html` sesuai kebutuhan Anda. Mohon menyesuaikan dengan format yang sudah ada, untuk keseragaman.
1. Selanjutnya taruh file **avatar** dan **favicon** milik Anda dalam path `/assets/images`. Perhatikan format nama file yang sudah ada.
1. Untuk avatar/logo gunakan format penamaan `namalink-avatar.ext`, dan untuk favicon `namalink-favicon.ext`. Apabila gambar avatar dan favicon sama, silahkan pilih apakah akan menggunakan suffix `-avatar` atau `-favicon`.
1. `git push` perubahan yang baru dilakukan, selanjutnya silahkan buka **Pull Request** baru.

## Cara Membuat Custom Stylesheet

Langkahnya sebagai berikut,

1. Fork repository ini.
1. Buat file baru dalam path `/assets/styles`. Contoh: `namastyle.scss`. Salin format yang sudah ada pada file `.scss` yang sudah ada.
   > Mohon untuk tidak mengutak-atik file `main.scss`
1. Jangan lupa untuk mengganti value `stylesheet` pada kedua file `namalink.en.html` dan `namalink.id.html`,  dengan nama file `namastyle.scss` yang baru dibuat.
1. Update juga file README ini, pada bagian `stylesheet` dibawah.
1. `git push` perubahan yang baru dilakukan, selanjutnya silahkan buka **Pull Request** baru.

## `stylesheet`

Berikut ini adalah nama style yang tersedia. Masih akan ditambahkan di waktu mendatang.

| Nama style | Author | Contoh |
|---|---|---|
| darkred.scss | [kawanuaid](https://timeline.kid.or.id/) | |
| darksolid.scss | [kawanuaid](https://timeline.kid.or.id/) | |
| gradient.scss | [kawanuaid](https://timeline.kid.or.id/) | |

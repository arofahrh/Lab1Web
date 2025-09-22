# praktikum 1
code :

      <!DOCTYPE html>
    <html>
    <title>Tag HTML dasar</title>
      </head>
      <body>
      
      </body>
      </html>
      <!-- Ini adalah paragraf pertama -->
       <!-- judul paragraf pertama -->
      <h1>Belajar Dasar HTML</h1>
      <p align=”center”>Kami sedang belajar <ins><mark>HTML dasar</mark></ins>, pada matakuliah <b>Pemrograman Web</b>
       di Prodi <i> Teknik Informatika </i> <ins> Universitas Pelita bangsa.</ins> Pelajaran pertama
      yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
      tag-tag dasar HTML.</p>
      <!-- Ini adalah paragraf kedua -->
       <!-- judul paragraf kedua -->
      <h2>Paragraf pada HTML</h2>
      <p align=”right”>Ini merupakan sebuah paragraf yang terdiri dari beberapa
      kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat
      dengan menggunakan tag dasar html.</p>
      <!-- judul paragraf pertama -->
      <!-- sub judul paragraf -->
      <h3>Menambahkan Gambar</h3>
      <!-- menambahkan gambar pada dokumen -->
      <img src="logo UPB.png" width="200" "Logo Univeritas Pelita Bangsa">
      <!-- menambahkan link navigasi -->
      <nav>
      <a href="lab1_tag_dasar.html">Dasar HTML</a>
      <a href="lab1_halaman2.html">Halaman 2</a>
      <a href="http://www.google.com">Halaman Web Eksternal Google</a>
      </nav>
      <hr>

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b597e417-fc78-4ddf-8484-888b40ada3e2" />


jawab pertanyaan berikut!
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulis tag?
2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
3. Apa perbedaan atribut tittle dan alt pada tag <img>, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakakan atribut width dan height. Agar tampilan gambar proposional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai atribut tersebut?

jawaban :
1. jika saya mengubah kode nya dengan atribut (tag) benar, tentu tidak akan error, browser akan tetap menampilkan apa yang sesuai saya tulis. Tetapi, saat salah menulis atribut (tag), HTML tidak akan menampilkan pop-up error, browser akan mengabaikan tag yang salah, dan hasil yang di tampilkan bisa berantakan atau tidak muncul (contoh : gambar tidak muncul)
2. - tag <p> fungsinya membuat paragraf teks termasuk tag kontainer (ada pembuka & penutup : <p>...</p>
   - <img> Ini fungsinya menampilkan gambar pada halaman web (butuh atribut      src untuk menampilkan file.
3. Perbedaan :
   - title pada tag <img> : Memberikan informasi tambahan atau deskripsi                                ketika kursor diarahkan ke gambar. Teks ini                                 juga muncul sebagai tooltip (kotak kecil) saat                              kursor hover di atas gambar.
   - alt (alternative text) : Memberikan teks alternatif jika gambar                                      tidak bisa dimuat ( contoh : file hilang,                                   koneksi lambat) dan untuk membantu pembaca                                  layar (Aksebilitas). Teks ini muncul di area                                gambar kalau gambarnya gagal dimuat. Tidak                                  muncul saat hover.
4. - jika hanya salah satu yang diisi (misalnya width) browser otomatis          menyesuaikan tinggi sesuai proporsi asli (tidak gepeng).
   - Jika dua-duanya diisi tapi rasio berbeda dari gambar asli (gambar           terdistorsi/gepeng.
5. Atribut target pada link <a>
- _blank : Membuka link di tab/jendela baru.
- _self : Membuka link di tab yang sama (default).
- _top : membuka link di seluruh jendela penuh (keluar daru frame)
- _parent : membuka link di jendela induk (jika halaman di dalam                        frame/iframe)











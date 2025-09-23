# Praktikum 1

      Nama : Arofah Raudlatul Hasanah
      Kelas : TI.24.A2
      NIM  : 312410231

## 1. Membuat paragraf sederhana
   <img width="1919" height="764" alt="image" src="https://github.com/user-attachments/assets/a2962160-6a00-4ecc-9319-f532f80bfa64" />
      
   <img width="1919" height="382" alt="image" src="https://github.com/user-attachments/assets/efaee4ce-f09d-4e3e-a7f2-1b307a25dd08" />
     <img width="1912" height="781" alt="image" src="https://github.com/user-attachments/assets/6703b8e7-3348-4a70-a038-4194c06cbc8b" />
     
       Penjelasan Kode:
       - <!-- ... --> adalah komentar, tidak ditampilkan di browser.
       - <p> digunakan untuk membuat paragraf.
       - align="center" membuat paragraf rata tengah.
       - align="right" membuat paragraf rata kanan.
       
       Output:
       - Paragraf pertama tampil rata tengah.
       - Paragraf kedua tampil rata kanan.

## 2. Menambah Judul

   <img width="1205" height="644" alt="image" src="https://github.com/user-attachments/assets/8b672839-2a05-48cb-804d-6623f37c717a" />
   <img width="1919" height="554" alt="image" src="https://github.com/user-attachments/assets/f5f6dbb6-0dd0-42ec-99ab-027c09d2eeb4" />
     
         Penjelasan Kode:
         <h1> membuat judul utama besar dan tebal.
         <h2> membuat subjudul lebih kecil.
         Komentar tidak tampil di browser.
      
         Output:
         Teks “Belajar Dasar HTML” besar dan tebal.
         Teks “Paragraf pada HTML” lebih kecil sedikit di bawahnya.
   
   ## 3. Memformat Teks
   <img width="1919" height="623" alt="image" src="https://github.com/user-attachments/assets/9a27a303-6c07-4add-a57f-a4f1add97528" />
   <img width="1919" height="565" alt="image" src="https://github.com/user-attachments/assets/de123b0d-98fb-41ee-8457-7ffb522d0f52" />

         Penjelasan Kode:
         <b> menebalkan teks.
         <i> memiringkan teks.
         <u> menggarisbawahi teks.
         
         Output:
         Bagian kata yang diapit <b> muncul tebal, <i> miring, <u> bergaris bawah.

## 4. Menyisipkan Gambar
    
   <img width="1919" height="755" alt="image" src="https://github.com/user-attachments/assets/47a2b01f-c1a1-4b6f-8ecd-80cf57b1f7d9" />

   <img width="1919" height="735" alt="image" src="https://github.com/user-attachments/assets/bd86df0b-327c-4d67-aeda-978558f4d2fe" />

         Penjelasan Kode:
         <h3> subjudul lebih kecil daripada <h2>.
         <img> menampilkan gambar.
         src nama file gambar.
         title menampilkan teks saat mouse diarahkan (tooltip).
         
         Output:
         Teks “Menambahkan Gambar” muncul sebagai subjudul kecil.
         Gambar logo UPB tampil

## 5. Menambah Hyperlink
   <img width="1919" height="891" alt="image" src="https://github.com/user-attachments/assets/cd6adca8-fe72-41e5-bf61-667fd276a3fa" />
   <img width="1919" height="691" alt="image" src="https://github.com/user-attachments/assets/cd322114-3296-4977-a9ca-b1a0c1ff5a3c" />

            Penjelasan Kode:
            <nav> untuk membuat area navigasi/link.
            <a href="..."> membuat link ke halaman lain
            <hr> membuat garis horizontal pemisah.
            
            Output:
            Link “Dasar HTML” mengarah ke file lab1_tag_dasar.html.
            Link “Halaman 2” mengarah ke file lab1_halaman2.html.
            Link “Halaman Web Eksternal Google” mengarah ke Google.
            Tampil garis horizontal di bawah link.

## Jawab Pertanyaan Berikut
    1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulis tag?
    2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
    3. Apa perbedaan atribut tittle dan alt pada tag <img>, berikan penjelasannya!
    4. Untuk mengatur ukuran gambar, digunakakan atribut width dan height. Agar tampilan gambar proposional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
    5. Pada link tambahkan atribut target dengan nilai atribut bervariasi (_blank, _self, _top, _parent), apa yang terjadi pada masing-masing nilai atribut tersebut?
 ### Jawaban :
 
      1. Perubahan kode & atribut
      	• Jika kita mengubah kode HTML dengan atribut/tag yang benar, maka browser akan menampilkan sesuai yang kita tulis.
      	• Tetapi jika salah menulis atribut/tag, HTML tidak akan memunculkan pop-up error. Browser hanya akan mengabaikan tag yang salah, dan hasil tampilan bisa berantakan atau tidak muncul (contoh: gambar tidak muncul).
      2. Perbedaan Tag
      	• <p> : Digunakan untuk membuat paragraf teks. Termasuk tag kontainer karena memiliki pembuka dan penutup <p>...</p>.
      	• <img> : Digunakan untuk menampilkan gambar pada halaman web.
      3. Perbedaan title dan alt pada <img>
      	• title : Memberikan informasi tambahan atau deskripsi ketika kursor diarahkan ke gambar. Teks ini muncul sebagai tooltip (kotak kecil) saat kursor hover di atas gambar.
      	• alt (alternative text) : Memberikan teks alternatif jika gambar tidak bisa dimuat (contoh: file hilang, koneksi lambat) dan membantu pembaca layar (accessibility). Teks ini muncul di area gambar kalau gambarnya gagal dimuat. Tidak muncul saat hover.
      4. Ukuran Gambar
      	• Jika hanya satu atribut (misalnya width) yang diisi, browser otomatis menyesuaikan tinggi sesuai proporsi asli (gambar tidak gepeng).
      	• Jika keduanya (width dan height) diisi dengan rasio berbeda dari gambar asli, maka gambar akan terdistorsi/gepeng.
      5. Atribut target pada <a>
      	• _blank : Membuka link di tab/jendela baru.
      	• _self : Membuka link di tab yang sama (default).
      	• _top : Membuka link di seluruh jendela penuh (keluar dari frame).
      	• _parent : Membuka link di jendela induk (jika halaman berada di dalam frame/iframe).


   
       





     
     

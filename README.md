Pertemuan 1 - Website Pertama Profil Mahasiswa

Jessica Jeslyn S - 535250093 - TI B

Di repository ini hasil praktik pembuatan halaman web sederhana dengan tema "Profil Mahasiswa"
Pembuatan web ini menggunakan HTML sebagai struktur halaman dan CSS untuk pengaturan tampilannya. 


Post-Test & Refleksi

1. Apa fungsi utama HTML?
HTML itu ibarat kerangka dari sebuah halaman web. Fungsinya untuk menyusun konten apa aja yang ada di halaman dan bagaimana urutannya.
Misalnya di praktik ini, saya menggunakan tag seperti `<header>`, `<nav>`, `<article>`, dan `<footer>` untuk membagi halaman menjadi bagian-bagian yang punya fungsi masing-masing.
Jadi secara keseluruhan HTML membangun struktur halaman web.​

2. Apa fungsi utama CSS?
Kalau HTML itu kerangkanya, CSS ini buat bikin visual dari web tersebut jadi menarik.
Jadi CSS yang mengatur tampilan halaman web.​
Contohnya di CSS ini saya bisa mengatur warna latar, jarak antar elemen (padding), perataan teks, sampai lebar maksimal dari sebuah bagian.
Kalau tidak ada CSS, halaman HTML bakal keliatan  polos, cuman teks hitam-putih tersusun dari atas ke bawah.

3. Mengapa external CSS digunakan?
Karna External CSS memisahkan struktur dan tampilan.​
Saya menggunakan external CSS (file style.css terpisah) tujuannya buat kode jadi lebih rapi dan mudah dibaca.
Dengan ini, file HTML saya cukup fokus buat mengurus struktur dan isi konten aja,
sementara semua urusan tampilan dikumpulin di satu file CSS.
Selain itu, kalau nanti saya punya lebih dari satu halaman HTML, saya cuman perlu menghubungkan semuanya ke satu file CSS yang sama,
jadi nga perlu menulis ulang kode style di setiap halaman.

4. Apa fungsi `<header>`, `<nav>`, `<article>`, dan `<footer>`? 
Fungsi dari ke empat tag tsb : 
`<header>` saya gunakan di bagian paling atas, berisi judul halaman dan ada keterangan tambahan sedikit.
`<nav>` saya gunakan untuk menampung menu navigasi, ada tiga link: Home, Profile, dan Contact.
`<article>`  bagian utama tempat saya menuliskan isi konten inti, seperti perkenalan diri, program studi, deskripsi singkat, keahlian, dan link profil GitHub saya.
`<footer>` saya letakkan di paling bawah, berisi informasi seperti hak cipta sederhana.

5. Sebutkan satu perubahan CSS yang Anda lakukan pada latihan.
Salah satu contoh perubahan yang saya lakukan adalah mengubah warna latar belakang (background) pada bagian header dan footer, dari yang semula 
#eeeeee di contoh dosen, saya ganti menjadi #dddddd agar sedikit lebih gelap.
Selain itu saya juga menambahkan properti color di beberapa bagian yang sebelumnya tidak ada di contoh,
seperti warna teks pada link navigasi supaya lebih menyatu dengan latar belakang gelap di bagian menu.

Refleksi
Dari praktik ini, bagian yang menurut saya sudah cukup saya kuasai adalah membuat struktur dasar HTML dan menghubungkannya dengan file CSS eksternal. 
Saya juga sudah cukup paham fungsi masing-masing tag semantik seperti header, nav, article, dan footer.
Sementara itu, bagian yang saya rasa masih perlu banyak dilatih adalah pemahaman CSS yang lebih kompleks, 
misalnya  mengatur layout menggunakan flexbox atau grid, karena di latihan ini saya baru menggunakan properti dasar seperti padding, background, dan text-align.


Hasil Akhir Web: 

<img width="1342" height="1097" alt="image" src="https://github.com/user-attachments/assets/6f61a5fd-55fd-41ac-8b18-fbe301fee5b3" />




Check Requirement :
 
 -Header  —  judul halaman dan subtitle 
 
 -Navigation (menu)  — tiga link: Home, Profile, Contact
 
 -Article  —  nama, program studi, deskripsi singkat, tiga keahlian dan satu link
 
 -Footer  —  keterangan hak cipta
 
 -External CSS  — file style.css terhubung lewat tag `<link>`
 
 -properti CSS  — padding, text-align, background, color, max-width, margin
 
 -bagian style dimodifikasi  — perubahan padding header,	background header,	color header,padding nav,	background nav,	color nav a, max-width article,	padding footer,	background footer,	color footer.
 
 -Tampilan satu kolom — semua bagian tersusun vertikal dari atas ke bawah
 
 -index.html dapat dibuka di browser — sudah diuji dan berhasil muncul
 
 -Struktur HTML dasar  — mencakup `<!DOCTYPE html>`, `<html>`, `<head>`, dan `<body>` yang lengkap

 - Penjelasan Kode — dijelaskan pada bagian Post-Test & Refleksi di atas

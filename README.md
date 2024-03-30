# Praktikum Pemrograman Web 1
-CSS
-HTML 
-Javascript

# HTML 
HTML singkatan dari Hyper Text Markup Language adalah file teks atau file ASCII yang berisi instruksi/script kepada web browser untuk menampilkan suatu tampilan grafis dari sebuah halaman web.
Berikut adalah contoh codingan membuat list menggunakan html:
<h1>Jenis Kendaraan</h1>

<p>Contoh kendaraan: </p>
<ol>
    <li>Mobil</li>
<ul>
    <li>Avanza</li>
    <li>Toyota</li>
    <li>Suzuki</li>
</ul>
    <li>Motor</li>
<ul>
    <li>Mio</li>
    <li>Scoopy</li>
    <li>Ninja</li>
</ul>
</ol>

-	Elemen H1 merupakan heading dengan ukuran 1
-	Elemen P itu untuk sebuah paragraf
-	ul mendefinisikan list yang tidak di order
-	ol mendefinisikan list yang di order
-	li mendefiniskan list apa saja yang di order

# CSS 
CSS Cascading Style Sheets (CSS) merupakan bahasa pemrograman yang digunakan untuk menentukan bagaimana dokumen dan website akan disajikan.
Berikut adalah contoh codingan mebuat tabel menggunakan css:
<!Doctype html>
<html>
<head>
<style>
#nama
  font-family:'Times New Roman', Times, serif;
  border-collapse: collapse;

}

#nama td, #customers th {
  border: 1px solid lightslategray;
  padding: 8px;
  text-align: left;
}

#nama tr:nth-child(even){background-color: lightcyan;}

#nama tr:hover {background-color: lightgoldenrodyellow;}

#nama th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: center;
  background-color: pink;
  color: black;
}
</style>
</head>
<body>

<h1>LIST IDOL</h1>

<table id="nama">
  <tr>
    <th>NAMA</th>
    <th>GROUP</th>
  <tr>
    <td>Jang Wonyoung</td>
    <td>ive</td>
  </tr>
  <tr>
    <td>Jung Ahyeon</td>
    <td>Baby Monster</td>
  </tr>
  <tr>
    <td>Seeun</td>
    <td>StayC</td>
  </tr>
  <tr>
    <td>Kim Chaewon </td>
    <td>Izone</td>
  </tr>
  <tr>
    <td>Eunha</td>
    <td> Vivis</td>
  </tr>

</table>
</body>
</html>

-	Elemen Head pada css berfungsi untuk membuat sebuah metadata yang memainkan peran penting dalam pembuatan website
-	Elemen style pada css berfungsi menambahkan sentuhan estetika pada elemen-elemen di halaman web.
-	#Nama itu sebagai id agar bisa terpanggil saat di body
-	Di dalam pembuatan style kita dapat menentukan border ( berfungsi untuk menentukan garis), padding ( jarak konten ke luar), font ( jenis teks), text-align ( penempatan teks ), background-color (warna latar belakan ), color (warna teks )
-	Tr nth-child (even)  Mewakili baris genap tabel HTML: 2, 4, 6, dst
-	Tr-hover berfungsi sebagai pengganti warna saat kursor meuju ke arah salah satu tabel
-	Elemen body dalam css berfungsi untuk  menentukan konten utama dari sebuah halaman web, seperti teks, gambar, audio, video, dan elemen lainnya.
-	Tag tr (tabel row) untuk membuat baris
-	Tag td (table data) untuk membuat sel
-	Tag th (table head) untuk membuat judul pada header

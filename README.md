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

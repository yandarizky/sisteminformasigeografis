
**RESUME PERTEMUAN 6 SISTEM INFORMASI GEOGRAFIS**

<p align="center">
  <img src="../../img/23.JPG" width="400px">
</p>

**Latar Belakang Masalah**

1. Bagaimana cara create data geometri Shapefile?
2. Bagaimana cara menghapus data geometri Shapefile?
3. Bagaimana cara mengedit data geometri Shapefile?
4. Bagaimana cara menampilkan data geometri Shapefile?

**ISI**

**Cara create data geometri Shapefile:**

1. Pertama-tama buka terlebih dahulu python nya melalu CMD
2. Selanjutnya import shapefile
3. Kemudian masukkan script ini, sf = shapefile.Writer(shapeType=1)
4. Selanjutnya untuk mengecek kita masukkan script ini, sf.shapeType
5. Selanjutnya tuliskan script ini, sf.field(&#39;NAMA&#39;,&#39;C&#39;,&#39;40&#39;)
6. Lalu masukkan script ini sf.field(&#39;PEMILIK&#39;,&#39;C&#39;,&#39;40&#39;)
7. Selanjutnya masukkan script ini, sf.record(&#39;WARTEG&#39;,&#39;Jajang Kusendar&#39;)
8. Pada langkah ini point bias diganti line atau polygon sesuai keinginan masing-masing dengan script ini, sf.point(10,10,0,0)
9. Kemudian jika sudah kita simpan dengan memasukkan script ini, sf.save(&#39;warteg.shp&#39;)

**Cara Menghapus data geometri Shapefile:**

1. Pertama-tama Buka terlebih dahulu python di command prompt
2. Kemudian lakukan import shapefile
3. Selanjutnya masukkan script ini, sf = shapefile.Editor(shapefile=&#39;warteg.shp&#39;)
4. Lalu masukkan script ini, sf.point(19,19,0,0)
5. Lalu masukkan script ini, sf.record(&#39;Warung Padang&#39;,&#39;Ucok&#39;)
6. Kemudian jika sudah kita simpan dengan memasukkan script ini, sf.save(&#39;warteg&#39;)

**Cara Mengedit data geomteri Shapefile:**

1. Pertama-tama Buka terlebih dahulu python di command prompt
2. Kemudian lakukan import import shapefile
3. Selanjutnya masukkan script ini, sf = shapefile.Editor(shapefile=&#39;warteg.shp&#39;)
4. Pada langkah ini point bias diganti line atau polygon sesuai keinginan masing-masing dengan script ini, sf.point(19,19,0,0)
5. Lalu masukkan script ini, sf.record(&#39;Warung Padang&#39;,&#39;Ucok&#39;)
6. Kemudian jika sudah kita simpan dengan memasukkan script ini, sf.save(&#39;warteg&#39;)

**Cara Menampilkan data geometri Shapefile:**

1. Pertama-tama Buka terlebih dahulu python di command prompt
2. Kemudian lakukan import shapefile
3. Selanjutnya masukkan script ini, sf = shapefile.Reader(&#39;warteg.shp&#39;)
4. record() -&gt; semua record
5. record(0) -&gt; record ke 1 pada data geometri shapefile
6. record(1) -&gt; record ke 2 pada data geometri shapefile
7. shapes()(0).points -&gt; script ini digunakan untuk menampilkan data geometri shapefile.

**PENUTUP**

**Kesimpulan**

Kesimpulan dari penjelasan-penjelasan diatas yaitu kita dapat dengan mudah melakukan create,edit,delete dan view pada data geometri shapefile dengan menggunakan python.

**Saran**

Saran yang dapat diberikan kita harus terus memperdalam materi mengenai membuat,menghapus mengedit serta menampilkan data geometri shapefile agar dapat lebih memahami mengenai materi ini.

Link github:

https://github.com/yandarizky/sisteminformasigeografis

Nama : yanda rizky prasetiya

NPM : 1144004

Kelas : 3C

Prodi : D4 Teknik Informatika

Mata Kuliah : Sistem Informasi Geografis

Link mata kuliah: www.awangga.net

referensi: https://id.wikipedia.org/wiki/Shapefile

Scan Plagiarisme:

1. https://drive.google.com/open?id=0ByZqhNt9UFJ2OENwU0N0WW5JM00

2. https://drive.google.com/open?id=0ByZqhNt9UFJ2SnB4VFF2ZW9sdWs

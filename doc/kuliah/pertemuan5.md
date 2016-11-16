**RESUME PERTEMUAN 5 SISTEM INFORMASI GEOGRAFIS**
<p align="center">
  <img src="../../img/47.jpg" width="400px">
</p>
**Latar Belakang Masalah**

1. Apa itu shapefile dan fungsinya?
2. Apa saja tools yang digunakan untuk melakukan create shapefile?
3. Apa saja file yang ada di shapefile?
4. Bagaimana cara menambah record pada shapefile?

**ISI**

**Shapefile yaitu** format dari suatu data geospasial yang umum digunakan untuk perangkat lunak Sistem Informasi Geografis. Shapefile ini merupakan kumpulan file yang berekstensi .shp .shx dan .dbf.fungsi dari shapefile ini sendiri yaitu untuk melakukan perhitungan jumlah kota yang ada pada ruang lingkup tertentu menggunakan beberapa sistem.

**Tools yang digunakan untuk melakukan create shapefile** yaitu python dan plugin pyshp dengan cara import shapefile dan inisialisasi a=Shapefile.Writer() pada python.

**File yang terdapat pada shapefile yaitu** SHP dan DBF, pada SHP terdapat 3 tipe shapefile yaitu, Point, Polyline dan Polygon. Pada DBF pertama field untuk atribut tabel, contoh &#39;a=field(&#39;kata&#39;,&#39;B&#39;,&#39;50&#39;)&#39;, kedua isinya pada method, contoh &#39;a.record(&#39;jakarta&#39;)&#39;, ketiga a.save(&#39;file.shp&#39;) dimana file.shp nama file shapefie yang sebelumnya diinputkan.

**Cara menambah record pada shapefile yaitu** Pada Point = &#39;a.point(x,y)&#39; atau &#39;a.point(x,y,0,0)&#39; dengan domain x dan y adalah koordinat,Pada Polyline = &#39;a.poly(shapefile=3,parts=[[[x1 ,y1 ,z1 ,w1],[x2 ,y2 ,z2 ,w2],[……]]])&#39;, Pada Polygon = &#39;a.poly)shapefile=5,parts=[[[…….],[…….]]])&#39;

**PENUTUP**

**Kesimpulan**

Kesimpulan dari penjelasan-penjelasan diatas yaitu proses penambahan record pada shapefile dengan menggunakan python dan pyshp sangat mudah mengingat script yang digunakan simpel dan mudah untuk dipahami.

**Saran**

Saran yang dapat diberikan agar materi ini lebih di perdalam lagi karena dapat menambah wawasan dan pengetahuan mengenai sistem informasi geografis

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

1. https://drive.google.com/open?id=0ByZqhNt9UFJ2eHcxX29Ddi10YWc

2. https://drive.google.com/open?id=0ByZqhNt9UFJ2WjZwUlUzdm5TTE0

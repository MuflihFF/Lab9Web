<b> Nama : Muflih Furqonudin Fahri
<p> NIM  : 312010105
<p> Kelas : TI.20.D.1 
<p> Langkah-Langkah Praktikum </b>

1.  Membuka dan menjalankan Aplikasi xampp terlebih dahulu, kemudian start Mysql dan Apache.

![1](https://user-images.githubusercontent.com/101880025/171388637-4900e600-5a97-4707-8df5-230b0e6add5e.png)

2.  Membuat folder baru dengan nama lab8_php_modular.

![6](https://user-images.githubusercontent.com/101880025/171388985-9044e5f0-2cb6-4964-9757-623dd5135724.png)

3.  Membuat header.php seperti berikut :

![2](https://user-images.githubusercontent.com/101880025/171389211-7fa0689c-952a-4842-9b57-f8378a8e4f6c.png)

4.  Membuat footer.php seperti berikut :

![3](https://user-images.githubusercontent.com/101880025/171389345-dd0a8121-353d-4a01-a894-a7a7118f1ab8.png)

5.  Membuat home.php seperti berikut :

![4](https://user-images.githubusercontent.com/101880025/171389417-a1082da5-ef7a-4e74-8c68-539f3f4a904f.png)

6.  Membuat about.php seperti berikut :

![5](https://user-images.githubusercontent.com/101880025/171389486-3c3c5c32-1d43-4fa1-aaff-a1766a89138b.png)

7.  Kemudian buka pada web browser dengan link : localhost/lab9_php_modular/home.php

![7](https://user-images.githubusercontent.com/101880025/171389890-c20f340d-8476-4b0d-900e-1cc86fd08eda.png)

<b>
<p> Pertanyaan dan Tugas !

Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama. </b>

1.  Langkah pertama membuat folder baru dengan nama tugas_modular pada folder lab9_php_modular.

![8](https://user-images.githubusercontent.com/101880025/171391361-789646ae-7938-4157-bd4b-7f4bf1606df1.png)

2.  Copy file koneksi.php dan hapus.php ditugas praktikum 8 kemudian simpan pada folder lab9_php_modular/tugas_modular.

![6](https://user-images.githubusercontent.com/101880025/171391941-46bbbede-2507-45f5-b0d1-c793a4b4803b.png)
![16](https://user-images.githubusercontent.com/101880025/171392092-62c29cc9-8cd6-495c-a6fc-344ad93864db.png)

3.  Kemudian buat file baru dengan nama header_index.php, kita ambil bagian header sesuai dengan yang dibutuhkan pada file index.php di praktikum 8.

![9](https://user-images.githubusercontent.com/101880025/171392625-b8f94643-09f8-443a-b9f8-9241c37b708c.png)

4.  Buat file footer_index.php yang kita ambil dari index.php pada praktikum 8.

![10](https://user-images.githubusercontent.com/101880025/171393444-c0936526-593a-4a0f-adcd-d469f4e3b5b3.png)

5.  Buat file index.php, kita ambil bagian body atau content dari index.php pada praktikum 8, dan kemudian tambahkan syntax <?php require('header_index.php'); ?> pada bagian atas body dan pada bagian bawah body index.php

![11](https://user-images.githubusercontent.com/101880025/171394226-e65b2ad8-35d0-49b5-b40c-eecdfc25fab7.png)
![12](https://user-images.githubusercontent.com/101880025/171394236-ab3f2b90-c8cc-419e-88c0-f99881c26889.png)

6.  Kemudian coba buka pada browser dengan link http://localhost/lab9_php_modular/tugas_modular/index.php

![13](https://user-images.githubusercontent.com/101880025/171396139-3cf36662-36f5-4fb6-87c8-5a74e42efd5b.png)

7.  Selanjutnya kita modularkan halaman tambah dengan membuat file baru header_tambah.php, kita ambil bagian header sesuai dengan yang dibutuhkan pada file tambah.php di praktikum 8.
<p>
 8.  Buat file footer_tambah.php yang kita ambil dari tambah.php pada praktikum 8
<p>
 9.  Kemudian coba buka pada browser dengan klik nav tambah atau dengan link : http://localhost/lab9_php_modular/tugas_modular/tambah.php  
  
![14](https://user-images.githubusercontent.com/101880025/171398038-1368ff21-fc4e-448b-a01f-5f2a43d1607d.png)

 10. Selanjutnya kita modularkan halaman ubah dengan membuat file baru header_ubah.php, kita ambil bagian header sesuai dengan yang dibutuhkan pada file ubah.php di  praktikum 8.
<p>  
 11. Buat file footer_ubah.php yang kita ambil dari ubah.php pada praktikum 8

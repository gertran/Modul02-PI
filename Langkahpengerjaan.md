1) Membuat direktori baru dengan nama UAP-Adsis dengan menggunakan perintah
“mkdir”
<img src="1.jpg">

2) Setelah itu, masuk ke dalam folder tersebut, dan buat file dengan nama catatanya-
ahmad.txt menggunakan perintah “touch”
<img src="Screenshots/Soal 1/2.jpg">

3) Mengisikan file yang telah dibuat dengan nama dan nim
<img src="Screenshots/Soal 1/3.jpg">

4) Lalu, memberikan permission view-only pada file yang telah dibuat menggunakan
perintah “chmod” menggunakan kode 644. Kode tersebut memiliki arti bahwa pemilik
akan memiliki akses untuk baca dan tulis, namun untuk user biasa hanya dapat
membacanya saja.
<img src="Screenshots/Soal 1/4.jpg">

5) Menggunakan perintah “ls -l” untuk menampilkan hasil file yang telah diberikan
permission only.
<img src="Screenshots/Soal 1/5.jpg">
Dapat dilihat bahwa file tersebut memiliki kode rw-r—r dimana kode tersebut
memiliki arti file hanya dapat baca dan diubah oleh pemiliki, dan user biasa hanya
dapat membaca saja

Soal 2
------------------------------------------------

1) Periksa antarmuka jaringan yang tersedia.
<img src="Screenshots/Soal 2/6.jpg">

2) konfigurasi alamat IP dan default gateway sementara
<img src="Screenshots/Soal 2/7.jpg">

3) memeriksa apakah konfigurasi alamat IP sementara dan default gateway berhasil dilakukan 
<img src="Screenshots/Soal 2/8.jpg">

Soal 3
------------------------------------------------


1) Membuat user baru dengan cara masuk ke halaman user and groups. Pada halaman
ini, kita akan membuat user baru dengan cara menekan tombol “create new user” untuk
membuat user baru, dan memasukkan nama user
<img src="Screenshots/Soal 3/10.jpg">
<img src="Screenshots/Soal 3/9.jpg">
Dapat terlihat bahwa user “ahmads” sudah berhasil dibuat.

2) Selanjutnya, membuat grup baru dengan nama “gertran” dengan cara menekan tombol
“create a new group”. Pada saat membuat grup, lakukan penambahan user yang
sebelumnya telah dibuat
<img src="Screenshots/Soal 3/12.jpg">

Soal 4
------------------------------------------------

1) Melakukan ping pada alamat IP 192.168.180.128
<img src="Screenshots/Soal 4/13.jpg">

2) Membuat rule baru untuk melakukan reject kepada request paket bertipe ICMP
<img src="Screenshots/Soal 4/14.jpg">


Soal 5
------------------------------------------------

1) Menjalankan perintah sudo crontab -e dan menuliskan perintah berikut untuk melakukan otomatisasi ping ke filkom.ub.ac.id

2) Setelah itu, dapat dilihat bahwa perintah ping telah terotomatisasi setiap 3 menit
<img src="Screenshots/Soal 5/15.jpg">

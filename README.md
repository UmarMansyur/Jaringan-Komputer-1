# Modul 1 Pengenalan Jaringan Komputer
### 1. Tugas Pendahuluan
a. Apakah yang dimaksud dengan jaringan komputer ?

b. Bagaimana implementasi jaringan komputer di dunia nyata ?

c. Apa saja manfaat jaringan komptuer ?
###2.	Tujuan
a.	Mahasiswa memahami konsep dasar jaringan komputer.

b.	Mahasiswa dapat mengetahui implementasi jaringan komputer.

c.	Mahasiswa dapat menjelaskan klasifikasi jaringan komputer berdasarkan jarak.

d.	Mahasiswa dapat mengetahui serta dapat menyebutkan topologi jaringan komputer.

e.	Mahasiswa dapat mengetahui manfaat jaringan komputer.
### 3.	Dasar Teori
Konsep jaringan komputer bermula pada tahun 1940-an di Amerika dari sebuah proyek pengembangan komputer di laboratorium Bell dan Group Riset dari Universitas Harvad yang di ketuai oleh Howard Aiken. Proyek tersebut awalnya hanya bertujuan untuk menghubungkan perangkat komputer yang harus dipakai bersama untuk mengurangi waktu kosong dari beberapa proses yang dikerjakan. 
#### a.	Pengertian Jaringan Komputer
Jaringan komputer adalah kumpulan dua komputer atau lebih yang dapat saling terhubung dengan menggunakan media transmisi baik dengan menggunakan kabel/wired seperti fiber optic ataupun nirkabel/wireless. Dua unit komputer dikatakan terkoneksi apabila keduanya dapat saling bertukar data/informasi serta berbagi resource yang dimiliki seperti file, printer, storage dan sebagainya.  Jaringan komputer  minimal membutuhkan dua unit komputer, dimana dari keduanya ada proses request (meminta) dan replay(mengirim). Pihak yang melakukan request disebut sebagai client, dan pihak penyedia layanan atau pengirim disebut sebagai server.
 
Gambar 1 Computer Network Illustration by Tanenbaum
Tiap komputer dan resource yang terhubung dalam jaringan di sebut dengan node(simpul). Node dapat terdiri dari puluhan atau bahkan ribuan komputer yang saling terkoneksi satu sama lain. Sistem koneksi antar node diklasifikasikan berdasarkan fungsi dan jarak. Klasifikasi jaringan berdasarkan jarak adalah sebagaiberikut:
1.	PAN (Personal Area Network)
PAN merupakan jenis jaringan komputer pribadi dengan cakupan wilayah 10 meter atau jenis jaringan komputer pribadi jarak dekat, biasanya digunakan untuk perangkat elektronik seperti PC, Laptop  dan sebagainya, contohnya adalah mouse wireless, keyboard wireless, speaker, headphone dan sebagainya.
2.	LAN ( Local Area Network)
LAN adalah jaringan komputer dengan luas wilayah terpendek kedua setelah PAN, LAN sendiri biasanya digunakan oleh perkantoran, sekolah, dan instansi tertentu.
3.	CAN (Cluster Area Network)
Jaringan komputer yang menghubungkan beberapa LAN namun tetap dalam satu wilayah disebut sebagai CAN, seperti antar fakultas dalam suatu universitas, pangkalan milter dan sebagainya.
4.	MAN (Metropolitan Area Network)
MAN adalah jenis jaringan komputer yang mencakup kota. MAN sendiri merupakan kumpulan dari beberapa CAN dan LAN yang terhubung.
5.	WAN (Wide Area Network)
Lebih luas dari MAN, WAN merupakan jenis jaringan komputer  yang cakupannya antar pulau, kota atau negara. 
6.	GAN (Global Area Network)
GAN merupakan jenis jaringan yang memungkinkan komunikasi perangkat mobile melalui berbagai wireless dalam jangkauan satelit.
Berdasarkan fungsi, jaringan komputer dapat diklasifikasikan sebagaimana berikut:
1.	Peer to Peer
Jaringan Peer to Peer adalah jaringan komputer yang setiap host dapat menjadi server dan juga menjadi client secara bersamaan. Jaringan Peer to Peer memperbolehkan pemakai dapat sharing resource dan file pada komputer. Jaringan Peer to Peer tidak mempunyai file server atau sumber manajemen yang terpusat. Dalam Jaringan Peer to Peer semua komputer di perlakukan sama, mereka semua mempunyai kemampuan yang sama untuk menggunakan resources yang tersedia pada jaringan. Jaringan Peer to Peer di tujukan bagi Local Area Network (LAN) kecil sampai menengah. Jadi, peer to peer merupakan jaringan komputer dimana setiap komputer dapat menjadi server dan client.
2.	Client - Server  
Client Server adalah jaringan komputer memiliki satu buah server dan lainya bertindak sebagai client. Client Server merupakan Jaringan yang memperbolehkan jaringannya untuk memusatkan fungsi dan aplikasi dalam satu atau lebih file server.
File server menjadi jantung dari sistem, menyediakan akses dan resources dan menyediakan keamanan. Individual workstation (client) memiliki akses ke resources yang tersedia pada file server. Untuk menggunakan Jaringan Client Server diperlukan sebuah media perantara berupa hub/switch.
 
Gambar 2 Ilustrasi Jenis Jaringan berdasarkan Fungsi (Client to Server & Peer to Peer)
Cara untuk mengkoneksikan komputer satu dengan yang lainnya disebut sebagai topologi. Secara umum topologi dibagi menjadi 5 macam, yaitu sebagaiberikut:
1.	Bus
Topologi bus adalah jenis topologi yang mengkoneksikan semua teminal dalam satu jalur komunikasi dimana setiap ujungnya ditutup dengan terinator. Topologi dapat di temukan apabila memiliki ciri-ciri sebagai berikut:
a.	Semua nodenya dihubungkan secara serial.
b.	Paket-Paket data saling bersimpangan.
c.	Tidak memerlukan Hub.
d.	Membutuhkan banyak connector pada setiap ethernet card.
 
Gambar 3 Topologi Bus
Keuntungan menggunakan topologi bus :
a.	Pemasangan yang sederhana.
b.	Tidak membutuhkan banyak kabel.
c.	Biaya yang lebih murah.
Kelemahan menggunakan topologi bus:
a.	Jika traffic padat maka akan memperlambat jalur bus.
b.	Jika terjadi kerusakan pada kabel utama mati, maka seluruh jaringan akan mati
c.	Membutuhkan terminator pada kedua sisi
d.	Sangat sulit dalam mencari kerusakan
e.	Topologi yang paling lambat
2.	Ring
Dalam arti bahasa ring merupakan cincin. Topologi ring adalah jenis topologi yang bentuknya seperti cincin. Setiap informasi akan melawati server dan komputer, ketika informasi tersebut sesuai dengan alamat yang dituju, maka komputer akan menerima informasi tersebut dan bila tidak maka hanya dilewati saja. Karakteristik topologi ring adalah sebagai berikut:
a.	Node dihubungkan serial dengan bentuk melingkar mirip cincin.
b.	Paket data mengalir satu arah antara ke kiri dan kekanan.
c.	Jika salah satu node rusak, maka jaringan ikut rusak
 
Gambar 4 Topologi Ring
Keuntungan menggunakan topologi ring :
a.	Collision(tabrakan) paket data dapat dihindarkan
b.	Aliran data yang lebih cepat
c.	Efisien dalam melayani kepadatan traffic data yang padat
Kelemahan menggunakan topologi bus:
a.	Sulit untuk melakukan pengaturan ulang
b.	Mengurangi serta menambah komputer akan mengacaukan jaringan.
3.	Star
Topologi star merupakan kumpulan node yang terhubung dengan node utama yang berada di tengah node lain. Karakteriktik topologi ring adalah sebagai berikut:
a.	Membutuhkan hub
b.	Jika salah satu komputer rusak, jaringan tidak ikut rusak
c.	Kecepatan dipengaruhi oleh kuantitas user





Gambar 5 Topologi Star

4.	Tree
Tree memiliki arti pohon, topologi tree adalah jenis topologi yang memiliki bentruk struktur bertingkat menyerupai pohon.
5.	Mesh
Topologi mesh adalah jenis topologi yang berupa gabungan dari topologi ring, star dan bus.
b.	Implementasi Jaringan Komputer
Dalam kehidupan sehari-hari, jaringan komputer paling sering digunakan untuk berkomunikasi jarak jauh, contohnya mengirim pesan menggunakan aplikasi WhattsApp, tentu pesan yang disampaikan oleh si pengirim ke si penerima tidak akan sampai jika tidak ada jaringan yang menghubungkan antar keduanya, contoh selanjutnya terdapat pada warnet di area perkotaan, ada banyak komputer yang digunakan namun printer yang digunakan untuk mencetak hanya terdapat satu saja, tapi semua komputer tersebut dapat menggunakan satu printer itu untuk mencetak, masalahnya bagaimana caranya semua komputer tersebut dapat terhubung dengan satu printer, mengingat kabel printer hanya tersedia untuk satu komputer saja, dalam hal inilah penggunaan jarngan menjadi solusi untuk mengatasi masalah tersebut. Untuk lebih jelasnya perhatikan gambar dibawah ini.
 
Gambar 6 Ilustrasi jaringan jaringan komputer
Pada gambar di atas, komputer server terhubung dengan printer, kemudian komputer lainnya dihubungkan pada komputer server baik secara kabel melalui kabel ke dalam sebuah switch (alat penghubung atau terminal antar komputer) dan nirkabel menggunakan wireless. Ketika PC 1 mengirim dokumen yang ingin di cetak maka, PC 1 akan mengirimkan instruksinya terlebih dahulu pada server kemudian, komputer server akan mengirimkan instruksi tersebut pada printer untuk dicetak.
Untuk saat ini jaringan komputer sudah dapat digunakan untuk lebih baik lagi, yaitu mengontrol komputer dari jarak jauh. Bahkan, windows sekarang sudah menyiapkan perangkat dimana perangkat itu dapat diakses oleh semua orang menggunakan smartphone ataupun komputer, namun akses itu berbayar.
c.	Tugas dan Evaluasi
a.	Dengan bahasa sendiri, apakah yang disebut dengan jaringan komputer ?
b.	Buatlah poin perbandingan topologi berdasarkan kelebihan, kelemahan dan karakteristiknya !
c.	Sebutkan manfaat jaringan komputer berdasarkan hiburan, sosial budaya, pemerintahan, dan kesehatan !
3.	Dasar Teori
Konsep jaringan komputer bermula pada tahun 1940-an di Amerika dari sebuah proyek pengembangan komputer di laboratorium Bell dan Group Riset dari Universitas Harvad yang di ketuai oleh Howard Aiken. Proyek tersebut awalnya hanya bertujuan untuk menghubungkan perangkat komputer yang harus dipakai bersama untuk mengurangi waktu kosong dari beberapa proses yang dikerjakan. 
a.	Pengertian Jaringan Komputer
Jaringan komputer adalah kumpulan dua komputer atau lebih yang dapat saling terhubung dengan menggunakan media transmisi baik dengan menggunakan kabel/wired seperti fiber optic ataupun nirkabel/wireless. Dua unit komputer dikatakan terkoneksi apabila keduanya dapat saling bertukar data/informasi serta berbagi resource yang dimiliki seperti file, printer, storage dan sebagainya.  Jaringan komputer  minimal membutuhkan dua unit komputer, dimana dari keduanya ada proses request (meminta) dan replay(mengirim). Pihak yang melakukan request disebut sebagai client, dan pihak penyedia layanan atau pengirim disebut sebagai server.
 
Gambar 1 Computer Network Illustration by Tanenbaum
Tiap komputer dan resource yang terhubung dalam jaringan di sebut dengan node(simpul). Node dapat terdiri dari puluhan atau bahkan ribuan komputer yang saling terkoneksi satu sama lain. Sistem koneksi antar node diklasifikasikan berdasarkan fungsi dan jarak. Klasifikasi jaringan berdasarkan jarak adalah sebagaiberikut:
1.	PAN (Personal Area Network)
PAN merupakan jenis jaringan komputer pribadi dengan cakupan wilayah 10 meter atau jenis jaringan komputer pribadi jarak dekat, biasanya digunakan untuk perangkat elektronik seperti PC, Laptop  dan sebagainya, contohnya adalah mouse wireless, keyboard wireless, speaker, headphone dan sebagainya.
2.	LAN ( Local Area Network)
LAN adalah jaringan komputer dengan luas wilayah terpendek kedua setelah PAN, LAN sendiri biasanya digunakan oleh perkantoran, sekolah, dan instansi tertentu.
3.	CAN (Cluster Area Network)
Jaringan komputer yang menghubungkan beberapa LAN namun tetap dalam satu wilayah disebut sebagai CAN, seperti antar fakultas dalam suatu universitas, pangkalan milter dan sebagainya.
4.	MAN (Metropolitan Area Network)
MAN adalah jenis jaringan komputer yang mencakup kota. MAN sendiri merupakan kumpulan dari beberapa CAN dan LAN yang terhubung.
5.	WAN (Wide Area Network)
Lebih luas dari MAN, WAN merupakan jenis jaringan komputer  yang cakupannya antar pulau, kota atau negara. 
6.	GAN (Global Area Network)
GAN merupakan jenis jaringan yang memungkinkan komunikasi perangkat mobile melalui berbagai wireless dalam jangkauan satelit.
Berdasarkan fungsi, jaringan komputer dapat diklasifikasikan sebagaimana berikut:
1.	Peer to Peer
Jaringan Peer to Peer adalah jaringan komputer yang setiap host dapat menjadi server dan juga menjadi client secara bersamaan. Jaringan Peer to Peer memperbolehkan pemakai dapat sharing resource dan file pada komputer. Jaringan Peer to Peer tidak mempunyai file server atau sumber manajemen yang terpusat. Dalam Jaringan Peer to Peer semua komputer di perlakukan sama, mereka semua mempunyai kemampuan yang sama untuk menggunakan resources yang tersedia pada jaringan. Jaringan Peer to Peer di tujukan bagi Local Area Network (LAN) kecil sampai menengah. Jadi, peer to peer merupakan jaringan komputer dimana setiap komputer dapat menjadi server dan client.
2.	Client - Server  
Client Server adalah jaringan komputer memiliki satu buah server dan lainya bertindak sebagai client. Client Server merupakan Jaringan yang memperbolehkan jaringannya untuk memusatkan fungsi dan aplikasi dalam satu atau lebih file server.
File server menjadi jantung dari sistem, menyediakan akses dan resources dan menyediakan keamanan. Individual workstation (client) memiliki akses ke resources yang tersedia pada file server. Untuk menggunakan Jaringan Client Server diperlukan sebuah media perantara berupa hub/switch.
 
Gambar 2 Ilustrasi Jenis Jaringan berdasarkan Fungsi (Client to Server & Peer to Peer)
Cara untuk mengkoneksikan komputer satu dengan yang lainnya disebut sebagai topologi. Secara umum topologi dibagi menjadi 5 macam, yaitu sebagaiberikut:
1.	Bus
Topologi bus adalah jenis topologi yang mengkoneksikan semua teminal dalam satu jalur komunikasi dimana setiap ujungnya ditutup dengan terinator. Topologi dapat di temukan apabila memiliki ciri-ciri sebagai berikut:
a.	Semua nodenya dihubungkan secara serial.
b.	Paket-Paket data saling bersimpangan.
c.	Tidak memerlukan Hub.
d.	Membutuhkan banyak connector pada setiap ethernet card.
 
Gambar 3 Topologi Bus
Keuntungan menggunakan topologi bus :
a.	Pemasangan yang sederhana.
b.	Tidak membutuhkan banyak kabel.
c.	Biaya yang lebih murah.
Kelemahan menggunakan topologi bus:
a.	Jika traffic padat maka akan memperlambat jalur bus.
b.	Jika terjadi kerusakan pada kabel utama mati, maka seluruh jaringan akan mati
c.	Membutuhkan terminator pada kedua sisi
d.	Sangat sulit dalam mencari kerusakan
e.	Topologi yang paling lambat
2.	Ring
Dalam arti bahasa ring merupakan cincin. Topologi ring adalah jenis topologi yang bentuknya seperti cincin. Setiap informasi akan melawati server dan komputer, ketika informasi tersebut sesuai dengan alamat yang dituju, maka komputer akan menerima informasi tersebut dan bila tidak maka hanya dilewati saja. Karakteristik topologi ring adalah sebagai berikut:
a.	Node dihubungkan serial dengan bentuk melingkar mirip cincin.
b.	Paket data mengalir satu arah antara ke kiri dan kekanan.
c.	Jika salah satu node rusak, maka jaringan ikut rusak
 
Gambar 4 Topologi Ring
Keuntungan menggunakan topologi ring :
a.	Collision(tabrakan) paket data dapat dihindarkan
b.	Aliran data yang lebih cepat
c.	Efisien dalam melayani kepadatan traffic data yang padat
Kelemahan menggunakan topologi bus:
a.	Sulit untuk melakukan pengaturan ulang
b.	Mengurangi serta menambah komputer akan mengacaukan jaringan.
3.	Star
Topologi star merupakan kumpulan node yang terhubung dengan node utama yang berada di tengah node lain. Karakteriktik topologi ring adalah sebagai berikut:
a.	Membutuhkan hub
b.	Jika salah satu komputer rusak, jaringan tidak ikut rusak
c.	Kecepatan dipengaruhi oleh kuantitas user





Gambar 5 Topologi Star

4.	Tree
Tree memiliki arti pohon, topologi tree adalah jenis topologi yang memiliki bentruk struktur bertingkat menyerupai pohon.
5.	Mesh
Topologi mesh adalah jenis topologi yang berupa gabungan dari topologi ring, star dan bus.
b.	Implementasi Jaringan Komputer
Dalam kehidupan sehari-hari, jaringan komputer paling sering digunakan untuk berkomunikasi jarak jauh, contohnya mengirim pesan menggunakan aplikasi WhattsApp, tentu pesan yang disampaikan oleh si pengirim ke si penerima tidak akan sampai jika tidak ada jaringan yang menghubungkan antar keduanya, contoh selanjutnya terdapat pada warnet di area perkotaan, ada banyak komputer yang digunakan namun printer yang digunakan untuk mencetak hanya terdapat satu saja, tapi semua komputer tersebut dapat menggunakan satu printer itu untuk mencetak, masalahnya bagaimana caranya semua komputer tersebut dapat terhubung dengan satu printer, mengingat kabel printer hanya tersedia untuk satu komputer saja, dalam hal inilah penggunaan jarngan menjadi solusi untuk mengatasi masalah tersebut. Untuk lebih jelasnya perhatikan gambar dibawah ini.
 
Gambar 6 Ilustrasi jaringan jaringan komputer
Pada gambar di atas, komputer server terhubung dengan printer, kemudian komputer lainnya dihubungkan pada komputer server baik secara kabel melalui kabel ke dalam sebuah switch (alat penghubung atau terminal antar komputer) dan nirkabel menggunakan wireless. Ketika PC 1 mengirim dokumen yang ingin di cetak maka, PC 1 akan mengirimkan instruksinya terlebih dahulu pada server kemudian, komputer server akan mengirimkan instruksi tersebut pada printer untuk dicetak.
Untuk saat ini jaringan komputer sudah dapat digunakan untuk lebih baik lagi, yaitu mengontrol komputer dari jarak jauh. Bahkan, windows sekarang sudah menyiapkan perangkat dimana perangkat itu dapat diakses oleh semua orang menggunakan smartphone ataupun komputer, namun akses itu berbayar.
c.	Tugas dan Evaluasi
a.	Dengan bahasa sendiri, apakah yang disebut dengan jaringan komputer ?
b.	Buatlah poin perbandingan topologi berdasarkan kelebihan, kelemahan dan karakteristiknya !
c.	Sebutkan manfaat jaringan komputer berdasarkan hiburan, sosial budaya, pemerintahan, dan kesehatan !

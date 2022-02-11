# MODUL III PROTOKOL
![image](https://user-images.githubusercontent.com/70986579/153551032-f1f48fa4-fbd6-49fe-b899-13cb0fd85adc.png)

## 1.	Tugas Pendahuluan
-	Apakah yang dimaksud dengan protokol jaringan?
-	Apa fungsi dari prokol jaringan ?
-	Sebutkan jenis-jenis protokol jaringan !
## 2.	Tujuan Praktikum
-	Mahasiswa memahami konsep dasar jaringan internet.
-	Mahasiswa dapat mengetahui cara kerja dari protokol.
-	Mahasiswa mampu menyebutkan jenis protokol dan fungsinya.
## 3.	Dasar Teori
![image](https://user-images.githubusercontent.com/70986579/153551085-807d0c9e-1989-41cf-bd12-ebc5a23db678.png)

Pada pembahasan sebelumnya dijelaskan bahwa jaringan komputer merupakan kumpulan komputer yang saling terhubung sehingga dapat melakukan komunikasi, berbagai resource serta dapat mentransfer file berupa video, audio dan sebagainya. Dalam proses menghubungkan jaringan komputer tentunya ada interaksi antara perangkat keras komputer dengan perangkat lunak antara komputer satu dengan yang lainnya. Ilustrasinya jika dalam suatu daerah menggunakan bahasa tertentu dalam komunikasi maka orang asing dapat berkomunikasi dengan orang di daerah itu harus menggunakan bahasa yang sama, atau dengan menggunakan bahasa nasional. 
Di dalam jaringan komputer hal yang demikian juga berlaku. Maka agar komputer dapat terhubung antara komputer satu dengan yang lainnya tentunya harus menggunakan bahasa yang sama dengan aturan tertentu. Mekanisme pengaturan bahasa yang dapat di pahami antar sistem dikenal dengan istilah protokol
### a.	Pengertian Protokol
Secara umum protokol jaringan memiliki arti aturan atau prosedur tertentu dalam jaringan. Arti lebih khususnya protokol merupakan sarana komunikasi antara mesin dengan jaringan yang terstandarisasi. Protokol digunakan untuk mendeteksi kesalahan, tipe kompresi dan bagaimana penerima mengindikasikan bahwa pesan diterima, protokol dapat memberikan deksripsi detail level bawah dari interface msein ke mesin seperti perintah bit dan byte yang ditransmisikan melalui kabel, atau pertukaran level atas antara program alokasi. Penggunaan protokol yang sama menyebabkan antar vendor yang berbeda dapat berkomunikasi pada jaringan yang sama. Protokol yang standar adalah (TCP/IP), WEB menggunakan server HTTP sehingga komputer dapat melakukan pencetakan, komunikasi dan beberapa layanan lain pada user.
Protokol-protokol internet yang sering digunakan adalah seperti, IP (Internet Protocol), TCP(Transmition Control Protocol), UDP(User Datagram Protocol), DNS (Domain Name System), HTTP(Hyper Text Transfer Protocol), HTTPS(Hyper Text Transfer Protocol Secure), SSH(Secure Shell), dan sebagainya.
### b.	Cara Kerja Protokol
“ The fundamental idea is that a particular piece of software (or hardware) provides a service to its users but keeps the details of its internal state and algorithms hidden from them” -  Andrew S. Tanenbaum

Pada dasarnya setiap software dan hardware yang menyediakan layanan tertentu pada user hanya menampilkan bagian sederhananya saja dan menyembukan kerumitannya seperti detail keadaan internal dan algoritma, bagitu pula dengan  jaringan maka untuk mengurangi kompleksitas desainya sebagian besar jaringan di atur sebagai tumpukan dari beberapa lapisan/layer atau level. Setiap layer memiliki fungsi dan tugasnya masing-masing, namun secara garis besar setiap layer memiliki tugas untuk berkomunikasi dengan layer di atasnya dan di bawahnya.
Protokol sebagaimana yang telah di sebutkan di atas mengacu terhadap kesepakatan antar pihak yang berkomunikasi, analoginya ketika pria diperkenalkan dengan seorang wanita, si wanita mungkin akan menjulurkan tangan, namun si pria dapat memustukan untuk menjabat tanganya dengan sedikit guncangan atau menjabat tangan dengan menciumnya hal ini tentu dapat diputuskan hal ini pasti tergantung dari jenis status sosialnya, jika si wanita merupakan seorang pengacara maka si pria akan menjabat tangannya, namun jika si wanita adalah seroang European princess at a formal ball maka dia akan menciumnya, setelah tahap perkenalan selesai, selanjunya proses komunikasi akan berlangsung. Namun apa yang akan terjadi jika si pria memutuskan jabat tangan tidak berdasarkan status sosialnya. Di dalam jaringan komputer, pelanggaran terhadap protokol membuat arus komunikasi menjadi lebih sulit.

![image](https://user-images.githubusercontent.com/70986579/153550335-b6d0781f-ff8d-45ab-a8b2-d8f8b6573565.png)

Analogi sederhana dalam cara kerja protokol sebagaimana pada gambar di atas, pada layer ke 3, bayangkan ada dua filsuf dimana keduanya menggunakan bahasa yang berbeda, filsuf A menggunakan bahasa Inggris sedangkan filsuf B mengerti bahasa Urdu, kemudian filsuf A ingin mengirimkan pesan ke secretary karena si secretary juga menggunakan bahasa yang berbeda maka butuh translator untuk menerjemahkannya begitu juga dengan filsuf B. Untuk mengetahui lebih jelasnya tentang cara kerja protokol akan di bahas pada modul selanjutnya. Pada modul selanjutnya, maksud dari layer/ lapisan akan di bahas secara umum dan terkait pembahasan layernya akan di bahas lebih rinci pada modul 5 sampai 11 dimana modul selanjutnya akan membahas model referensi OSI layer. Pada model OSI, terdapat beberapa lapisan yang menjelankan tugas dan fungsinya masing-masing serta setiap layernya memiliki protokol yang berbeda kecuali pada layer fisik dan tautan data.
## 4.	Tugas dan Evaluasi
-	Menurut pembahasan sendiri, apa yang dimaksud protokol ?
-	Apa keuntungan yang didapatkan jika menggunakan protokol yang sama ?
-	Apakah perbedaan antara protokol HTTP dengan HTTPS ?
-	Buatlah analogi sederhana dari cara kerja protokol, selain analogi di atas !
-	Sebutkan fungsi dari jenis prokol yang telah di sebutkan di atas !
## 5.	Referensi
Mulyanta , Edi S, Pengenalan Jaringan Wireless Komputer, Surabaya: Andi

Syafrizal, Melwin, 2020, Pengantar Jaringan Komputer, Surabaya: Andi


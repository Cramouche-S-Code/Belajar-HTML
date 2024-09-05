## Sebelum Belajar HTML Ada Baiknya Kita Mengetahui Basic Web Development Terlebih Dahulu

## Bagaimana Internet Bekerja ?

### Internet adalah jaringan global yang memungkinkan perangkat di seluruh dunia untuk saling terhubung dan bertukar informasi. Berikut penjelasan singkat tentang bagaimana internet bekerja:

1. Client-Server Model
   Internet bekerja berdasarkan model client-server, di mana:

Client adalah perangkat pengguna (misalnya, komputer, ponsel, tablet) yang mengakses informasi.
Server adalah perangkat yang menyimpan dan menyajikan informasi atau layanan (seperti halaman web) kepada client. 2. Protokol Komunikasi
Komunikasi di internet diatur oleh protokol atau aturan, di mana protokol utama adalah:

TCP/IP (Transmission Control Protocol / Internet Protocol): Protokol utama yang memastikan data dikirim dan diterima dengan benar melalui internet. TCP memecah data menjadi paket-paket kecil dan memastikan semua sampai di tujuan, sedangkan IP mengatur alamat dan pengiriman paket tersebut ke tujuan yang benar. 3. Alamat IP (Internet Protocol)
Setiap perangkat di internet memiliki alamat IP, seperti alamat rumah yang unik untuk mengidentifikasi perangkat tersebut. Alamat IP ini digunakan untuk mengirim dan menerima data.

Contoh alamat IP:

IPv4: 192.168.1.1
IPv6: 2001:0db8:85a3:0000:0000:8a2e:0370:7334 4. Domain Name System (DNS)
DNS adalah sistem yang menerjemahkan alamat domain (seperti www.google.com) menjadi alamat IP. Ketika Anda mengetik URL di browser, DNS menemukan alamat IP yang sesuai dengan domain tersebut dan mengarahkan permintaan Anda ke server yang tepat.

2. Data Traveling in Packets
   Data di internet dipecah menjadi paket-paket kecil. Setiap paket berisi:

Data itu sendiri (payload): Misalnya, bagian dari halaman web.
Header paket: Informasi seperti alamat pengirim, alamat penerima, dan urutan paket.
Paket-paket ini dikirimkan melalui berbagai jalur (routing) dan dapat melewati berbagai server (router) di seluruh dunia sebelum sampai di tujuan.

3. Routing dan Router
   Router adalah perangkat yang mengarahkan paket-paket data ke tujuan mereka. Setiap paket mungkin melewati banyak router sebelum sampai ke server atau perangkat client. Router memilih rute terbaik berdasarkan kecepatan dan kondisi jaringan.

4. HTTP/HTTPS (Hypertext Transfer Protocol/Secure)
   Ketika Anda mengunjungi sebuah website, browser mengirimkan permintaan melalui protokol HTTP atau HTTPS.

HTTP digunakan untuk mengirim permintaan dan menerima respons dari server web.
HTTPS adalah versi aman dari HTTP yang mengenkripsi data yang dikirim antara client dan server untuk mencegah penyadapan. 8. Pertukaran Data dan Respons
Ketika Anda mengetikkan alamat website di browser, permintaan dikirim ke server yang sesuai.
Server menerima permintaan tersebut, mencari halaman web yang diminta, dan mengirimkan data tersebut kembali ke client (browser) dalam bentuk file HTML, CSS, JavaScript, gambar, dan sebagainya. 9. Loading dan Rendering di Browser
Setelah data sampai di client (misalnya, browser Anda):

HTML memberi struktur halaman.
CSS menambahkan styling dan layout.
JavaScript menambahkan interaktivitas.
Semua file ini dirender oleh browser untuk menampilkan halaman web yang Anda lihat.

5. Keamanan dan Enkripsi
    Firewall: Melindungi perangkat dan jaringan dari akses yang tidak diinginkan.
    SSL/TLS: Protokol enkripsi yang digunakan oleh HTTPS untuk melindungi data sensitif, seperti informasi login atau transaksi keuangan.
6. Pengiriman Data Berkelanjutan
    Internet memungkinkan pengiriman data secara real-time atau mendekati real-time melalui berbagai teknologi seperti streaming, video call, dan game online.

## Ringkasan Proses Kerja Internet:

Anda mengetikkan alamat website (URL) di browser.
DNS menerjemahkan URL menjadi alamat IP dari server tujuan.
Permintaan (request) dikirim melalui berbagai router hingga mencapai server.
Server merespons dengan mengirim data (misalnya, file HTML).
Data dipecah menjadi paket-paket, dikirim melalui jaringan, dan diterima oleh client.
Browser menyusun kembali data dan menampilkan halaman web kepada Anda.
Itulah cara kerja internet secara singkat!

## Apa itu PORT dan WEB BROWSER ?

### Port dan Web Browser adalah dua konsep penting dalam dunia jaringan dan web. Berikut penjelasannya:

1. Port:
   Dalam konteks jaringan komputer, port adalah titik akhir atau jalur logis yang digunakan untuk mengatur komunikasi antara perangkat di jaringan. Setiap perangkat yang terhubung ke internet memiliki alamat IP yang digunakan untuk mengidentifikasi perangkat tersebut, namun untuk mengidentifikasi layanan atau aplikasi spesifik yang sedang digunakan, port digunakan.

Port Numbers (Nomor Port): Setiap layanan jaringan memiliki nomor port yang berbeda. Ini membantu perangkat mengetahui ke aplikasi atau layanan mana data yang diterima harus diarahkan. Misalnya, web server menggunakan port yang berbeda dengan server email.

Beberapa Port yang Umum:
Port 80: Untuk HTTP (Hypertext Transfer Protocol) – layanan web standar.
Port 443: Untuk HTTPS (Hypertext Transfer Protocol Secure) – layanan web aman yang menggunakan enkripsi.
Port 25: Untuk SMTP (Simple Mail Transfer Protocol) – layanan pengiriman email.
Port 21: Untuk FTP (File Transfer Protocol) – layanan transfer file.
Cara Kerja Port:
Ketika Anda mengunjungi sebuah situs web, permintaan (request) yang dikirim dari browser Anda akan menggunakan alamat IP dan nomor port untuk mencapai server tujuan. Port bertindak seperti pintu yang terbuka untuk aplikasi spesifik. Misalnya, jika Anda mengakses situs web aman, browser akan menggunakan port 443 (HTTPS).

Ilustrasi:
Jika sebuah komputer adalah sebuah gedung, alamat IP adalah alamat gedung tersebut, dan port adalah nomor pintu yang berbeda di gedung untuk layanan tertentu, seperti pintu 80 untuk HTTP, pintu 443 untuk HTTPS.

2. Web Browser:
   Web browser adalah perangkat lunak atau aplikasi yang digunakan untuk mengakses dan menampilkan halaman web dari internet. Browser berfungsi sebagai jembatan antara pengguna dan web server dengan menerjemahkan kode (seperti HTML, CSS, dan JavaScript) menjadi antarmuka visual yang dapat dilihat dan dinavigasi oleh pengguna.

Fungsi Utama Web Browser:

Mengirim Permintaan (Request): 
- Browser mengirim permintaan HTTP/HTTPS ke server web untuk mengakses halaman tertentu.

Menerima dan Menampilkan Data (Response):
- Setelah menerima respons dari server, browser akan memproses file yang diterima (HTML, CSS, JavaScript) dan menampilkan halaman web kepada pengguna.

Rendering: 
- Proses menerjemahkan kode web (HTML, CSS, JavaScript) menjadi tampilan yang bisa dinavigasi pengguna.

Menyimpan Cache: 
- Browser menyimpan salinan halaman web dan file statis (seperti gambar) untuk mempercepat akses di kemudian hari.

Beberapa Contoh Web Browser Populer:

Google Chrome: 
- Salah satu browser paling populer yang dikembangkan oleh Google.

Mozilla Firefox: 
- Browser open-source yang dikembangkan oleh Mozilla.

Microsoft Edge:
- Browser yang dikembangkan oleh Microsoft, penerus Internet Explorer.

Safari:
- Browser yang dikembangkan oleh Apple, digunakan pada perangkat macOS dan iOS.

Opera: 
- Browser yang dikenal dengan fitur kompresi datanya untuk akses internet yang lebih cepat.

Cara Kerja Web Browser:
   - Anda mengetik alamat URL (misalnya, www.google.com) di address bar browser.
   - Browser mengirimkan permintaan ke server menggunakan protokol HTTP atau HTTPS.
   - DNS menerjemahkan alamat URL menjadi alamat IP server.
   - Browser terhubung ke server melalui alamat IP dan nomor port yang sesuai (misalnya, port 80 atau 443).
   - Server mengirimkan file HTML, CSS, dan JavaScript yang diminta.
   - Browser memproses file-file tersebut dan menampilkan halaman web.
   - Komponen Penting pada Web Browser:
   - Rendering Engine: Bagian dari browser yang merender konten halaman web dan menerjemahkannya menjadi bentuk visual.
   - JavaScript Engine: Mengolah dan menjalankan skrip JavaScript di halaman web.
   - User Interface (UI): Komponen visual yang dilihat pengguna, termasuk address bar, tombol navigasi, dan jendela tampilan konten.
   - Ringkasan:
   - Port adalah jalur logis pada jaringan yang digunakan untuk mengatur lalu lintas data ke aplikasi atau layanan tertentu (misalnya, port 80 untuk HTTP, port 443 untuk HTTPS).
   - Web Browser adalah aplikasi yang digunakan untuk mengakses halaman web, berfungsi untuk mengambil, menerjemahkan, dan menampilkan konten web kepada pengguna.
   - Keduanya bekerja bersama: browser menggunakan port untuk berkomunikasi dengan server di internet dan menampilkan konten web ke pengguna.

## Bagaimana http Bekerja ?

### HTTP (Hypertext Transfer Protocol) adalah protokol komunikasi yang digunakan di internet untuk mentransfer data antara client (misalnya, web browser) dan server. Berikut ini adalah penjelasan tentang bagaimana HTTP bekerja:

1. Client-Server Model

   HTTP bekerja berdasarkan model client-server, di mana:

- Client adalah perangkat atau aplikasi yang mengirimkan permintaan HTTP untuk mengakses data. Contohnya, web browser (seperti Google Chrome, Firefox) adalah client.
- Server adalah perangkat atau aplikasi yang menyimpan dan menyajikan data ketika client memintanya. Server ini menyimpan file yang berisi konten website (misalnya, HTML, CSS, JavaScript, gambar).

2. Request-Response Cycle (Siklus Permintaan-Respons)

   Siklus kerja HTTP melibatkan dua komponen utama: permintaan (request) dan respons (response).

a. HTTP Request (Permintaan HTTP)
Ketika Anda mengetikkan URL di browser atau mengklik tautan, browser mengirimkan HTTP request ke server. Permintaan ini berisi:

- Metode HTTP: Menentukan tindakan yang diinginkan. Metode yang paling umum digunakan adalah:
- GET: Untuk meminta data dari server (misalnya, halaman web atau gambar).
- POST: Untuk mengirim data ke server (misalnya, data formulir).
- PUT: Untuk memperbarui data di server.
- DELETE: Untuk menghapus data di server.
- URL (Uniform Resource Locator): Alamat dari sumber daya yang diminta (misalnya, www.github.com).
- Headers: Informasi tambahan tentang permintaan, seperti jenis browser yang digunakan atau jenis data yang diharapkan.
- Body (opsional): Jika metode seperti POST digunakan, body mengandung data yang akan dikirim (misalnya, data formulir).

b. HTTP Response (Respons HTTP)
Setelah server menerima permintaan, server akan memprosesnya dan mengirimkan HTTP response kembali ke client. Respons ini berisi:

- Status Code (Kode Status): Menunjukkan hasil dari permintaan. Kode status umum meliputi:
- 200 OK: Permintaan berhasil dan data dikirimkan.
- 404 Not Found: Sumber daya yang diminta tidak ditemukan di server.
- 500 Internal Server Error: Ada kesalahan di sisi server.
- Headers: Informasi tambahan tentang respons, seperti jenis konten yang dikirim (HTML, JSON, gambar).
- Body (opsional): Data yang diminta oleh client (misalnya, halaman web HTML atau file gambar).

3. Langkah-Langkah Kerja HTTP

   Berikut adalah langkah-langkah rinci tentang bagaimana HTTP bekerja:

Pengguna Mengetik URL atau Mengklik Tautan:

Misalnya, ketika Anda mengetikkan www.example.com di browser, permintaan HTTP dikirim ke server dengan menggunakan metode GET.
DNS Lookup:

Browser menggunakan DNS (Domain Name System) untuk menerjemahkan nama domain (misalnya, www.example.com) menjadi alamat IP server.
Koneksi Terbentuk:

Setelah alamat IP ditemukan, browser membuat koneksi ke server melalui port 80 (untuk HTTP) atau port 443 (untuk HTTPS, yang merupakan versi aman HTTP).
Pengiriman HTTP Request:

Browser mengirimkan permintaan HTTP ke server, misalnya permintaan GET untuk meminta halaman web. Permintaan ini berisi URL halaman yang ingin diakses serta informasi tentang browser.
Server Menerima Permintaan dan Memprosesnya:

Server menerima permintaan, memprosesnya, dan mencari file yang diminta (misalnya, file HTML yang sesuai dengan halaman yang diminta).
Server Mengirimkan HTTP Response:

Server merespons dengan mengirimkan kode status, header, dan konten halaman web (file HTML, CSS, JavaScript, gambar) ke browser.
Browser Menerima dan Menampilkan Halaman Web:

Browser menerima respons dari server, memproses file yang diterima, dan menampilkan halaman web di layar pengguna.

4. Stateless Protocol (Protokol Tanpa Status)

   HTTP adalah stateless protocol, artinya setiap permintaan dan respons HTTP berdiri sendiri, tanpa mengingat permintaan sebelumnya. Ini berarti bahwa setelah satu permintaan selesai, koneksi antara client dan server terputus, dan permintaan baru akan membutuhkan koneksi baru.

Untuk menjaga sesi dan status pengguna (misalnya, saat login di situs web), teknologi seperti cookies dan sessions digunakan.

5. HTTP vs HTTPS

- HTTP (Hypertext Transfer Protocol): Data dikirimkan dalam format plain text, sehingga lebih rentan terhadap penyadapan.
- HTTPS (Hypertext Transfer Protocol Secure): Versi aman dari HTTP yang menggunakan SSL/TLS (Secure Sockets Layer / Transport Layer Security) untuk mengenkripsi data yang dikirim antara client dan server. Ini sangat penting saat mengirimkan informasi sensitif seperti kata sandi atau data keuangan.

6. Headers dan Body dalam HTTP

- Headers: Bagian dari HTTP yang berisi metadata atau informasi tambahan tentang permintaan atau respons. Contoh header:
- Content-Type: Menyatakan jenis konten dalam respons (misalnya, text/html, application/json).
- User-Agent: Menyatakan jenis browser atau perangkat yang mengirim permintaan.
- Body: Isi utama dari data yang dikirim dalam permintaan atau respons, terutama digunakan untuk metode seperti POST dan PUT.

7. HTTP Status Codes (Kode Status HTTP)

Kode status HTTP adalah respons standar dari server yang menunjukkan hasil dari permintaan client. Contoh kode status yang sering digunakan:

- 1xx Informational: Permintaan diterima dan sedang diproses (jarang terlihat pengguna).
- 2xx Success: Permintaan berhasil diproses.
- 200 OK: Permintaan berhasil dan data dikirim.
- 3xx Redirection: Permintaan diarahkan ke URL yang berbeda.
- 301 Moved Permanently: Sumber daya telah dipindahkan secara permanen.
- 4xx Client Errors: Kesalahan dari sisi client.
- 404 Not Found: Halaman yang diminta tidak ditemukan.
- 401 Unauthorized: Pengguna perlu login terlebih dahulu.
- 5xx Server Errors: Kesalahan dari sisi server.
- 500 Internal Server Error: Ada masalah di server.

Ringkasan Cara Kerja HTTP:

1. Client (browser) mengirim permintaan HTTP ke server.
2. Server memproses permintaan dan mengirimkan respons HTTP.
3. Client menerima respons dan menampilkan halaman web.

## HTTP adalah protokol sederhana dan fleksibel yang memungkinkan pertukaran data di web. Penggunaan HTTPS semakin disarankan untuk menjaga keamanan komunikasi, terutama dalam transfer data yang sensitif.

# Apa Itu Domain & Hosting ?

## Domain dan Hosting adalah dua komponen penting yang berperan dalam membuat sebuah situs web bisa diakses di internet. Meskipun keduanya saling terkait, mereka memiliki fungsi yang berbeda. Berikut penjelasan masing-masing:

1. Domain:

   Domain adalah alamat unik yang digunakan untuk mengakses sebuah situs web di internet. Ini adalah nama yang pengguna ketikkan di browser (misalnya, https://portfolio-guntur.vercel.app) untuk mengunjungi suatu situs. Domain adalah representasi teks dari alamat IP yang sebenarnya digunakan oleh server, sehingga lebih mudah diingat dan digunakan oleh manusia.

### Komponen Domain:

Nama Domain: Ini adalah nama yang dipilih untuk situs web Anda, seperti example dalam www.github.com.

- Ekstensi Domain (TLD - Top-Level Domain): Ini adalah bagian akhir dari domain yang menunjukkan jenis atau tujuan situs, seperti:

  - .com: Digunakan untuk situs komersial (umum).
  - .org: Digunakan untuk organisasi (biasanya nirlaba).
  - .net: Awalnya untuk jaringan tetapi sekarang lebih umum.
  - .edu: Digunakan oleh institusi pendidikan.
  - .go: Digunakan oleh pemerintah.

- Proses Kerja Domain:

  - Ketika seseorang mengetikkan nama domain di browser, DNS (Domain Name System) menerjemahkan domain tersebut menjadi alamat IP yang terkait dengan server hosting situs web.
  - Dengan menggunakan alamat IP ini, browser dapat mengakses server tempat situs di-host dan menampilkan halaman web.

2. Hosting:

   Hosting adalah layanan yang menyediakan tempat (server) untuk menyimpan file dan data situs web sehingga situs tersebut bisa diakses oleh pengguna melalui internet. Dengan kata lain, web hosting adalah "rumah" bagi situs web Anda di internet. Semua file situs web (HTML, CSS, gambar, video, dan lain-lain) disimpan di server hosting ini.

   1. Jenis-Jenis Web Hosting:
      Shared Hosting: Hosting bersama di mana beberapa situs web berbagi satu server fisik yang sama. Ini lebih murah tetapi kinerjanya bisa lebih lambat jika ada banyak situs yang berbagi server.

   2. VPS Hosting (Virtual Private Server): Hosting di mana server fisik dibagi menjadi beberapa server virtual. Setiap situs web memiliki sumber daya yang lebih terisolasi, yang meningkatkan performa dan keamanan.

   3. Dedicated Hosting: Situs web memiliki server fisik sendiri, yang tidak dibagi dengan situs lain. Ini menawarkan kinerja terbaik tetapi lebih mahal.

   4. Cloud Hosting: Hosting yang menggunakan beberapa server untuk menyimpan dan mengelola data situs web, meningkatkan skalabilitas dan keandalan.

   5. Managed Hosting: Layanan hosting di mana penyedia hosting juga mengelola semua aspek teknis situs web, seperti pembaruan, backup, dan keamanan.

   Fungsi Utama Hosting:

   - Menjaga Situs Tetap Online: Hosting memastikan situs web Anda dapat diakses kapan saja oleh pengunjung dari seluruh dunia.
   - Menyimpan Data: Semua file yang terkait dengan situs web (misalnya, teks, gambar, video, dan database) disimpan di server hosting.
   - Bandwidth dan Traffic: Hosting juga menyediakan bandwidth, yaitu jumlah data yang bisa ditransfer antara server dan pengunjung situs. Lebih banyak pengunjung biasanya memerlukan hosting dengan bandwidth lebih tinggi.

   Contoh Penyedia Hosting:

   - Bluehost
   - Hostinger
   - SiteGround
   - AWS (Amazon Web Services)
   - Google Cloud Platform
   - Vercel
   - Netlify

Ilustrasi:
Bayangkan domain sebagai alamat rumah dan hosting sebagai rumah itu sendiri. Tanpa alamat (domain), orang tidak akan tahu ke mana harus pergi. Dan tanpa rumah (hosting), tidak ada tempat untuk menyimpan barang-barang Anda (file situs web).

Ringkasan:

- Domain: Alamat unik yang digunakan untuk mengakses situs web (seperti www.google.com).
- Hosting: Layanan yang menyediakan server untuk menyimpan file situs web dan membuatnya dapat diakses di internet.

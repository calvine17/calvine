# calvine
<h2>Ini contoh program Socket Programming dengan Web Scoket yang saya modifikasi</h2>

<h2>Cukup Install XAMPP Control Panel Versi Terbaru</h2>
<h3>Link <a href="https://www.apachefriends.org/download.html">Install</a>, Pilih sesuai dengan kebutuhan anda</h3>

<h2>Selanjutnya Jalankan XAMPP Control Panel Dengan Start 2 Paling Atas</h2>

![control-panel](https://user-images.githubusercontent.com/72307737/111792284-ae262580-88f6-11eb-8b10-9de7ea15177a.jpg)

<h2>Kemudian pilih Shell dan jalankan script di bawah ini</h2>

php -q htdocs/demo/src/chatws.php

![Untitled](https://user-images.githubusercontent.com/72307737/111792787-2c82c780-88f7-11eb-8c92-63896af724dd.png)

Apabila terjadi error, maka ke php.ini

![Untitled42141](https://user-images.githubusercontent.com/72307737/111793572-fb56c700-88f7-11eb-819b-60d01ae23f34.png)

Kemudian ctrl+f dan search socket, hilangkan titik koma dari seleksi biru tersebut

![421414](https://user-images.githubusercontent.com/72307737/111793641-0ad61000-88f8-11eb-9a26-c1e15d1902f5.png)

Berikut ini tampilan setelah titik koma dihapus

![Untitled4124141](https://user-images.githubusercontent.com/72307737/111795972-47a30680-88fa-11eb-9a55-aae58203260f.png)

Kemudian tekan Ctrl+S..

Ulangi lagi buka shell dan masukkan php -q htdocs/demo/src/chatws.php

Setelah selesai, maka buka browser dan ketikkan http://localhost/demo/index.php maka tampilan aplikasi chatting web socket akan muncul

![WhatsApp Image 2021-03-19 at 9 23 05 PM](https://user-images.githubusercontent.com/72307737/111795047-6bb21800-88f9-11eb-8eb4-b5f3ec1b0ad2.jpeg)

Itulah web socket programming sederhana yang saya modifikasi...




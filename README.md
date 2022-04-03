### Lab 4 Web
## Web Layout
# Membuat Box Element

Buat file dengan nama lab4_box.html, kemudian ketik struktur tag HTML berikut.

![Gambar 1](screenshot1/ss1a.png)

Kemudian tambahkan kode untuk membuat box element dengan tag div dab di bungkus dengan tag `<section>` seperti berikut.

![Gambar 2](screenshot1/ss1b.png)

Ini tampilannya di browser.

![Gambar 3](screenshot1/ss1c.png)

Kemudian tambahkan CSS pada kode tersebut.

![Gambar 4](screenshot1/ss1d.png)

Ini tampilannya di browser.

![Gambar 5](screenshot1/ss1e.png)

# Mengatur Clearfix Element

Clearfix digunakan untuk mengatur element setelah float element. Property clear digunakan untuk 
mengaturnya.
Tambahkan element div lainnya seteleah div3 seperti berikut.

![Gambar 6](screenshot1/ss2a.png)

Kemudian atur property clear pada CSS, seperti berikut

![Gambar 7](screenshot1/ss2b.png)

Ini tampilannya di browser.

![Gambar 8](screenshot1/ss2c.png)

Jika nilai property clear diganti dengan both, maka tampilannya akan sama dengan yang diatas. Kemudian Jika nilai property clear diganti dengan right, tampilannya akan seperti ini.

![Gambar 9](screenshot1/ss2d.png)

# Membuat Layout Sederhana

Pertama-tama yaitu buat folder baru dengan nama lab4_layout, kemudian buatlah file baru didalamnya dengan nama 
home.html, dan file css dengan nama style.css.

Pada file home.html ketikan tag HTML sebagai berikut.
Pada tag `<body>` tambahkan tag `<div>`dengan ID Container.

![Gambar 10](lab4_layout/screenshot2/ss1a.png)

Kemudian tuliskan kode berikut.

![Gambar 11](screenshot2/ss1b.png)

Ini tampilannya di browser.

![Gambar 12](screenshot2/ss1c.png)

Setelah itu untuk mendeklarasikan CSS, tambahkan tag `<link>` pada tag `<head>`.

![Gambar 13](screenshot2/ss1d.png)

Kemudian tuliskan kode berikut pada file CSS. Dan tambahkan juga reset CSS agar mudah mengatur ukurannya, karena secara default tag-tag pada HTML sudah memiliki ukuran atau jarak.

![Gambar 14](screenshot2/ss1e.png)

Ini tampilannya di browser.

![Gambar 15](screenshot2/ss1f.png)

# Membuat Navigasi

Tambahkan kode berikut pada file CSS.

![Gambar 16](screenshot2/ss2a.png)

Ini tampilannya di browser.

![Gambar 17](screenshot2/ss2b.png)

# Membuat Hero Panel

Untuk menambahkan hero panel gunakan tag `<section>` dengan ID hero pada tag `<div>` dengan ID Container.

![Gambar 18](screenshot2/ss3a.png)

Tambahkan juga CSSnya.

![Gambar 19](screenshot2/ss3b.png)

Ini tampilannya di browser.

![Gambar 20](screenshot2/ss3c.png)

# Mengatur Layout Main dan Sidebar

Tambahkan CSS float.

![Gambar 21](screenshot2/ss4aa.png)

Dan Tambahkan element lain dalam sidebar. 

![Gambar 22](screenshot2/ss4a.png)

Kemudian tambahkan CSS.

![Gambar 23](screenshot2/ss4b.png)

Ini tampilannya di browser.

![Gambar 24](screenshot2/ss4c.png)

# Mengatur Footer

Tambahkan CSS sebagai berikut.

![Gambar 25](screenshot2/ss5a.png)

Ini tampilannya di browser.

![Gambar 26](screenshot2/ss5b.png)

# Menambahkan Elemen lainnya pada Main Content

Tambahkan tag-tag HTML sebagai berikut.

![Gambar 27](screenshot2/ss6a.png)

Tambahkan juga CSS sebagai berikut.

![Gambar 28](screenshot2/ss6b.png)

![Gambar 29](screenshot2/ss6b1.png)

Ini tampilannya di browser.

![Gambar 30](screenshot2/ss6c.png)

# Menambahkan Content Artikel

Tambahkan HTML sebagai berikut.

![Gambar 31](screenshot2/ss7a.png)

Tambahkan juga CSS sebagai berikut.

![Gambar 32](screenshot2/ss7b.png)

Ini tampilannya di browser.

![Gambar 33](screenshot2/ss7c.png)

## Pertanyaan dan Tugas
1. Tambahkan Layout untuk menu About

=> buat single layout yang berisi deskripsi, portfolio, dll

2. Tambahkan layout untuk menu Contact

=> yang berisi form isian: nama, email, message, dll

JAWAB :

1. Untuk menambahkan layout pada menu About yang berisi deskripsi dan portofolio, buat file HTML dengan nama about.html dan buat file CSS dengan nama styleAbout.css seperti berikut.

![Gambar 34](screenshot2/ss8a.png)

Kemudian isi file HTML tadi dengan kodingan ini.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
    <link rel="stylesheet" href="styleAbout.css">
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Tentang Saya</h1>
        </div>
        <div class="navigasi">
            <a href="home.html">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </div>
        <div class="content">
            <img src="image/foto-profile.jpg" alt="Foto Rahmat">
            <p>Halo, saya adalah seorang Front End Developer yang berasal dari Cikarang Bekasi. 
            Saat ini saya sedang belajar di Universitas Pelita Bangsa. Saya lulus kuliah tahun 2023 sebagai cumlaude, 
            ini merupakan pencapaian terbaik saya. Saya menguasai berbagai macam bahasa pemrograman berbasis web. 
            Mulai dari HTML, CSS, Javascript dan masih banyak lagi. 
            <br> <br> Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Enim iste dolorem nostrum fuga autem? Animi tempore doloremque explicabo, beatae maxime dolor aperiam ullam 
            repudiandae ad nisi molestias reprehenderit sequi veritatis? Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Obcaecati sequi aspernatur soluta rerum quod voluptatum amet sunt, 
            unde quidem dolor facere neque sint animi nihil quos recusandae quia 
            ipsum odio.
            </p>
        </div>
        <div class="portofolio">
            <h2>My portofolio</h2>
            <p>Jika ingin melihat portofolio saya, silahkan klik pilihan dibawah.
            Anda akan langsung di arahkan ke github untuk melihat kodenya.</p>
            <ul>
                <li><a href="http://github.com/Rahmat2303" target="_blank" rel="noopener noreferrer">Games Ular ga Tangberbasis web</a></li>
                <li><a href="http://github.com/Rahmat2303" target="_blank" rel="noopener noreferrer">Web E-commerce</a></li>
                <li><a href="http://github.com/Rahmat2303" target="_blank" rel="noopener noreferrer">Sistem penerimaan Mahasiswa Baru</a></li>
                <li><a href="http://github.com/Rahmat2303" target="_blank" rel="noopener noreferrer">Sistem Pembayaran SPP</a></li>
                <li><a href="http://github.com/Rahmat2303" target="_blank" rel="noopener noreferrer">Sistem Informasi Desa</a></li>
            </ul>
        </div>
        <footer>
            <p>&copy;2022 - Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>

Dan tambahkan CSS seperti dibawah ini.

/* import google font */
@import 
url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
@import 
url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0,300;0,700;1,300&display=swap');

/* Reset CSS */
*{
    margin: 0;
    padding: 0;
}
/* \Body */
body {
    line-height: 1;
    font-size: 100%;
    font-family: 'open sans', sans-serif;
    color: #5a5a5a;
}
/* Container */
.container {
    width: 980px;
    margin: 0 auto;
    box-shadow: 0 0 1em #cccccc;
}
/* Header */
.header {
    padding: 20px;
}
.header h1 {
    margin: 20px 10px;
    color: #b5b5b5;
}
/* Navigasi */
.navigasi {
    display: block;
    background-color: #1f5faa;
}
.navigasi a {
    padding: 15px 30px;
    display: inline-block;
    color: #fff;
    font-size: 14px;
    text-decoration: none;
    font-weight: bold;
}
.navigasi a.active,
.navigasi a:hover {
    background-color: #2b83ea;
}
/* Content */
.content {
    background-color: #e0e0e0;
    width: 950px;
    margin: -5px 15px;
}
.content img {
    display: block;
    width: 170px;
    height: 170px;
    vertical-align: middle;
    border-radius: 50%;
    margin: 20px auto;
    position: relative;
    top: 20px;
}
.content p {
    padding: 20px 25px;
    font-size: 17px;
    line-height: 23px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    text-align: justify;
    word-spacing: 1px;
}

/* Portofolio */
.portofolio {
    width: 950px;
    height: 345px;
    background-color: #e0e0e0;
    margin: 20px auto;

}
.portofolio h2 {
    position: relative;
    top: 15px;
    padding-bottom: 30px;
    padding-right: 330px;
    padding-left: 340px;
    font-size: 40px;
}
.portofolio p {
    padding: 15px 30px;
    color: black;
    line-height: 20px;
}
.portofolio ul {
    list-style-type:none;
    border: 2px solid rgb(0, 0, 0);
    border-bottom: 1px solid rgb(0, 0, 0);
    margin-left: 30px;
    margin-bottom: 50px;
    margin-right: 30px;
}
.portofolio li {
    border-bottom:1px solid rgb(0, 0, 0);
    background-color: rgb(196, 196, 196);
}
.portofolio a {
    text-decoration: none;
    padding:10px 20px;
    color:#333;
    display:block;
}
.portofolio li:hover a {
    background-color: rgb(255, 255, 255);
}
/* footer */
footer {
    clear: both;
    background-color:#1d1d1d;
    padding:20px;
    color:#eee;
}

Ini tampilannya di browser.

![Gambar 35](screenshot2/ss9a.png)
![Gambar 36](screenshot2/ss9b.png)

Ketika di klik pada menu About, akan muncul seperti diatas.

2. Untuk menambahkan layout pada menu Contact yang berisi form isian, buat file HTML dengan nama kontak.html dan buat file CSS dengan nama styleKontak.css seperti berikut.

![Gambar 37](screenshot2/ss10a.png)

Kemudian isi file HTML tadi dengan kodingan ini.

`<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact</title>
    <link rel="stylesheet" href="styleKontak.css">
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Contact Us</h1>
        </div>
        <div class="navigasi">
            <a href="home.html">Home</a>
            <a href="artikel.html">Artikel</a>
            <a href="about.html">About</a>
            <a href="kontak.html">Kontak</a>
        </div>
        <div class="contact">
            <form action="">
                <p>
                    <label for="nama">Nama :</label>
                    <input type="text" id="nama" name="Nama">
                </p>
                <p>
                    <label for="email">Email  :</label>
                    <input type="text" id="email" name="email">
                </p>
                <p>
                    <label for="pesan" class="pesan">Pesan</label>
                    <textarea name="pesan" id="pesan" cols="30" rows="10"></textarea>
                </p>
                <p>
                    <input type="submit" value="Kirim Data">
                </p>
            </form> 
        </div>
        <div class="sosmed">
            <h4>Kunjungi sosial media kami :</h4>
            <div>
                <a href="http://www.instagram.com" target="_blank"><img src="image/logo-ig.jpg" alt="Instagram"></a>
                <a href="http://www.facebook.com" target="_blank"><img src="image/logo-fb.jpeg" alt="facebook"></a>
                <a href="http://www.twitter.com" target="_blank"><img src="image/logo-twitter.png" alt="twitter"></a>
                <a href="http://www.tiktok.com" target="_blank"><img src="image/logo-tiktok.jpeg" alt="tiktok"></a>
            </div>
        </div>
        <footer>
            <p>&copy;2022 - Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>`

Dan tambahkan CSS seperti dibawah.

`/* import google font */
@import 
url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
@import 
url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0,300;0,700;1,300&display=swap');
/* Reset CSS */
*{
    margin: 0;
    padding: 0;
}
/* \Body */
body {
    line-height: 1;
    font-size: 100%;
    font-family: 'open sans', sans-serif;
    color: #5a5a5a;
}
/* Container */
.container {
    width: 980px;
    margin: 0 auto;
    box-shadow: 0 0 1em #cccccc;
}
/* Header */
.header {
    padding: 20px;
}
.header h1 {
    margin: 20px 10px;
    color: #b5b5b5;
}
/* Navigasi */
.navigasi {
    display: block;
    background-color: #1f5faa;
}
.navigasi a {
    padding: 15px 30px;
    display: inline-block;
    color: #fff;
    font-size: 14px;
    text-decoration: none;
    font-weight: bold;
}
.navigasi a.active,
.navigasi a:hover {
    background-color: #2b83ea;
}
/* contact */
.contact {
    width: 950px;
    height: 205px;
    background-color: rgb(218, 218, 218);
    margin: 15px auto;
}
.contact form {
    margin: 15px;
    position: relative;
    top: 15px;
}
form p > label {
    display: inline-block;
    width: 100px;
}
form input[type="text"], form textarea {
    border: 1px solid #8b8b8b;
}
form p {
    margin: 10px 5px;
} 
form textarea {
    width: 300px;
    height: 80px;
}
form input[type="submit"] {
    background-color: #1f5faa;
    color: #fff;
    border: 1px solid #03356d;
    padding: 5px 10px;
    font-weight: bold;
    margin-left: 105px;
}
/* sosmed */
.sosmed h4 {
    margin: 30px 360px;
}
.sosmed div{
    margin: -15px 222px 20px;
}
.sosmed img {
    width: 70px;
    height: 70px;
    margin: 25px;
}
.sosmed div img:active,
.sosmed div img:hover {
    width: 85px;
    height: 85px;
}
/* footer */
footer {
    clear: both;
    background-color:#1d1d1d;
    padding:20px;
    color:#eee;
}`

Kemudian ini tampilannya di browser.

![Gambar 38](screenshot2/ss10b.png)




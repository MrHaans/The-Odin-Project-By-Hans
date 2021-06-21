# What is HTML, CSS, Javascript

## Question to Answer

Chapter I

* What is the role of HTML in a web page?
    * Answer : Berguna untuk melampirkan, atau membungkus, berbagai bagian konten untuk membuatnya tampak dengan cara tertentu, atau bertindak dengan cara tertentu.
* What is the role of CSS in a web page?
    * Answer : Berguna untuk mendesain elemen HTML secara selektif.
* What is the role of JavaScript in a web page?
    * Answer : Berguna untuk menambahkan interaktivitas ke situs web.
* Which language is responsible for the semantic structure of a document?
    * Answer : HTML / Hypertext Markup Language.
* Which language can change the font, text-size, or background-color of an element?
    * Answer : CSS / Cascading Style Sheets.
* Name a few behaviors that javascript can be responsible for on a website.
    * Answer : 1). Antarmuka Pemrograman Aplikasi Browser ( API ) dibangun ke dalam browser web, menyediakan fungsionalitas seperti membuat HTML secara dinamis dan mengatur gaya CSS; mengumpulkan dan memanipulasi aliran video dari webcam pengguna, atau membuat grafik 3D dan sampel audio. 2). API pihak ketiga yang memungkinkan pengembang untuk menggabungkan fungsionalitas di situs dari penyedia konten lain, seperti Twitter atau Facebook. 3). Kerangka kerja dan pustaka pihak ketiga yang dapat Anda terapkan ke HTML untuk mempercepat pekerjaan membangun situs dan aplikasi.
* What is the purpose of an opening tag and closing tag in an HTML element?
    * Answer : Karena memiliki struktur yang semantik. Maka opening tag berguna untuk memberitahu browser ketika akan  menampilkan dokumen mulai dari tag pembuka, dan ditutup dengan closing tag yang merupakan tag penutup dari isi suatu dokumen.
* What is the selector in a CSS ruleset?
    * Answer : Selector adalah salah satu element html yang kita pilih yang akan diberikan style oleh css nantinya.
* What is the property and property value in a CSS ruleset?
    * Answer : Property adalah cara kita untuk memberikan suatu gaya dalam element html, misal pada tag html {p} kita akan memberikan gaya color {untuk warna}, font {untuk gaya huruf}. Sedangkan property value adalah nilai yang kita berikan didalam sebuah property, misal pada tag html {p} kita akan memberikan gaya color {untuk warna} berupa warna merah {value : red}.
* What is the declaration in a CSS ruleset?
    * Answer : Declaration adalah aturan tunggal seperti {color: red}. Untuk menentukan element dari property mana yang ingin diberikan gaya.
* How do you reference a file in the same directory as your HTML file?
    * Answer : 
* How do you reference a file in a directory below your HTML file?
    * Answer : 
* How do you reference a file in the directory above your HTML file?
    * Answer : 

Chapter II

* What is the difference between HTML and CSS?
    * Answer : 
* For accessibility in HTML, what is the attribute used to describe an image (on screen readers or if it fails to load)?
    * Answer : 
* What is the difference between CSS Grid and Flexbox?
    * Answer : 
* For a responsive website, should it be designed mobile-first or desktop-first?
    * Answer : 
* Describe the components of the CSS Box Model.
    * Answer : 
* In CSS, what is a breakpoint?
    * Answer : 
* What is a div and how are they used?
    * Answer : 
* What are the two main groups of CSS properties that control typography style?
    * Answer : 
* What is the “query string” in a URL and what does it do?
    * Answer : 
* What is the difference between “pixels” and “em”?
    * Answer : 
* How does inheritance work for CSS styles, i.e. how does an element get its “default” styles?
    * Answer : 
* What are two CSS attributes you can change to push an element around on the page?
    * Answer : 
* What are the three different ways to include a CSS stylesheet in your project or use CSS to style a particular element?
    * Answer : 
* What is the “default stylesheet” or “user agent stylesheet”?
    * Answer : 
* What is the purpose of a CSS reset file?
    * Answer : 

## HTML Cheat Sheet

* !-- --
    * Untuk membuat komentar pada html.
* p /p
    * Adalah paragraf.
* h1 /h1, h2 /h2, h3 /h3 --> 6
    * adalah header.
* a /a
    * Adalah anchor yang berguna untuk menautkan link secara eksternal ataupun internal.
        Atribut :
        * href="link" : Sebagai tempat untuk menempelkan suatu link untuk eksternal ataupun hastag untuk internal.
        * target="*" : Sebagai cara untuk membuka link, bisa dilakukakan didalam ataupun diluar tab.
* img
    * Adalah image yang berguna untuk memberikan image pada html.
        Atribut :
        * src="link" : Source sebagai tempat untuk menempelkan link dari suatu gambar yang akan diambil.
        * alt="Messege" : Alternatif sebagai sesuatu yang akan ditampilkan jika tautan dari gambar rusak/hilang. Sehingga hanya menampilkan nama sesuai yang ditulis didalam alt.
* ul /ul
    * Berguna untuk membuat list tidak berurutan pada html.
        Content : 
        * li /li : Untuk membuat beberapa list.
* ol /ol
    * Berguna untuk membuat list berurutan pada html.
        Content :
        * li /li : Untuk membuat beberapa list.
* Nest Anchor
    * Adalah link yang berada didalam suatu paragraf, ex : Liat beberapa dari list game saya {disini}. Yang disini merupakan link yang bisa diklik.
* Internal Anchor #
    * Adalah link internal yang digunakan untuk menautkan ke link yang terdapat dalam suatu konten yang sama.
        Rumus : anchor; a href="#personal" /a , konten; p {id ="personal"} Nik KTP saya adalah 093294983724932/p
* main /main
    * Berfungsi untuk membantu mesin pencari dan developer menemukan konten utama dari halaman kita.
* input
    * Berfungsi untuk mendapatkan input dari pengguna.
        Atribut : 
        * type="text" : Sebagai bentuk dari input pengguna nantinya.
        * placeholder="Input NIK" : Sebagai apa yang ditampilkan di input elemen sebelum pengguna melakukan input.
        * required : Berfungsi sebagai bidang yang wajib diisi oleh pengguna, jika tidak maka tombol button tidak akan bisa berfungsi.
* form /form
    * Berfungsi sebagai field yang menyediakan informasi yang bisa di input oleh pengguna.
        Atribut :
        * action="Server Name" : Berfungsi untuk mengirim input dari pengguna ke server yang anda punya.
* button /button
    * Berfungsi untuk membuat tombol yang bisa diklik oleh penngguna.
        Atribut :
        * type="Submit" : Berfungsi untuk mengirimkan data dari formulir Anda ke URL yang Anda tentukan dengan action atribut formulir Anda.
* input
    * Berfungsi untuk membuat opsi input user berupa checkbox dan radio.
        Atribut :
        * type="radio" : Berfungsi untuk membuat opsi pilihan berupa radio button yang hanya dapat dipilih 1 bagian. Dengan menerapkan id pada input, dan for pada label dan disesuaikan dengan nama yang diterapkan pada seluruh radio.
        * type="checkbox" : Berfungsi untuk membuat opsi pilihan berupa checkbox yang dapat dipilih beberapa bagian.
        * value="indoor" : Berfungsi untuk mengirimkan pilihan user ke server sesuai nama value yg diberikan. Isi value sesuai dengan nama dari label agar mudah dipahami ketika user menginput.
        * checked : Berfungsi sebagai opsi centang default pada inputan baik checkbox maupun radio.
* label /label
    * Berfungsi untuk membuat sebuah nama pada sebuah inputan, seperti pada checkbox dan radio.
* div /div
    * Berfungsi sebagai wadah untuk menampung berbagai element dalam html. Atau bisa disebut pengelompokkan.

## CSS Cheat Sheet

* h2 style="color: red;" /h2
    * Berfungsi untuk memberikan warna tertentu pada suatu paragraf di html.
* style p{color: red;} /style
    * Berfungsi untuk mempermudah pemberian warna hanya dengan memberikan deklarasi dan value didalam blok style.
* style .blue-text{color: blue;} /style
    * .blue-text adalah class yang diberikan pada elemnt di html dan dipanggil pada css dengan memiliki awalan titik (.).
* 
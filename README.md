# Catering app
## About Author:

-nama: eka
-kelas: Backend
-motivasi: ingin belajar

**belajar hari ini:**

- [v] implementasi scrum di asana
- [v] Belajar Git basic
- [x] Belajar colaborasi git

Contoh:

```java
class HelloWorld{
    public static void main(String[] argumen){
        System.out.println("Selamat datang di dunia per git an, wkwkwkw!");
    }
}
```

author Ahmad Muhardian • 22 Jan 2018
Panduan Lengkap Belajar Menulis dengan Markdown untuk Pemula
#Markdown #HTML
Tutorial Markdown untuk Pemula
Bagi yang sering bermain di Github dan web serupa, pasti sering melihat markdown. Biasanya markdown digunakan untuk menuliskan dokumentasi.

Pada dasarnya markdown sama seperti HTML. Namun, lebih sederhana dan mudah dibaca.

Saat ini markdown sudah digunakan untuk:

Dokumentasi;
SSG (Static Site Generator);
CMS seperti Ghost, Wordpress, Tumblr, dll.;
Penulisan Buku;
Format teks pada chat: Telegram, WA, Facebook;
dll.
Pada kesempatan ini, kita akan belajar dasar-dasar format markdown hingga format tingkat lanjut.

Apa itu Markdown?
Markdown adalah (lightweight markup language) bahasa markup yang lebih ringan dari HTML untuk formatting teks.

Markdown bisa dikonversi ke dalam HTML menggunakan beberapa aplikasi. Biasanya menggunakan markdown editor itu sendiri.

Markdown dibuat pada tahun 2004 oleh John Gruber. Tujuannya untuk mempermudah penulisan dokumen web—mudah ditulis dan mudah dibaca—Karena menulis langsung HTML terasa melelahkan dan susah dibaca.

Contoh:

Aku *sedang* belajar **menulis** dengan [markdown](https://en.wikipedia.org/wiki/Markdown).
Teks ini akan dikonversi ke HTML menjadi seperti ini:

Aku sedang belajar menulis dengan markdown.

Aku <em>sedang</em> belajar <strong>menulis</strong> dengan <a href="https://en.wikipedia.org/wiki/Markdown">markdown</a>.
Menurutmu mana yang lebih mudah ditulis?

Pasti banyak yang akan menjawab markdown.

Saya sendiri sudah merasakan perbedaannya.

Waktu menulis di Blogger, saya menulis langsung HTML di setiap artikel. Rasanya melelahkan 😫…

Ketika sudah mirgrasi ke Hugo, saya menulis dengan markdown dan terasa lebih cepat dan produktif dibandingkan HTML.

Editor untuk Menulis Markdown
Ada banyak sekali software atau editor untuk menulis markdown. Silahkan pilih yang kamu sukai.

Markdown Editor di Mac OSX
Mou - Free
iA Writer - $19.99
Desk - $29.99
ByWord - $11.99
Day One - $9.99
SublimeText - $70
Markdown Editor di Windows
WriteMonkey - Free
MarkdownPad - Free + $14.99 Pro version
Texts - $14.50
SublimeText - $70
Markdown Editor di Linux
Remarkable - Free
Haroopad - Free
ReText - Free
UberWriter
Mark My Words
Pilih yang mana?

Saya sendiri memilih VS Code dengan plug-in Mardkwon All in One.

Markdown di VS Code
File Markdown
File markdown dapat kita simpan dengan ekstensi .markdown atau .md.

Contoh: belajar-menulis.md atau belajar-menulis.markdown

Format dasar Markdown
Sekarang mari kita coba menulis format-format dasar markdown. Pertama, mari kita mulai dari:

Membuat Heading
Heading atau judul di markdown dapat dibuat dengan tanda pagar #.

Contoh:

# Heading 1
## Heading 2
### Heading 3
Maka akan menghasilkan:

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
Heading ini sampai level 6 seperti pada HTML. Jumlah tanda pagar di depannya menandakan levelnya.

Selain menggunakan tanda pagar, ada juga yang menggunakan simbol minus (-) dan samadengan (=) seperti ini:

Ini Headeing Level 1
====================

ini paragraf, bla bla bla...

Ini heading level 2
-------------------

ini paragraf, bla bla bla...
Format Teks
Jika kamu ingin menulis teks tebal, miring, dan strikeline, maka bisa dilakukan seperti ini:

**Tebal**
*miring*
~~strikeline~~
Selain menggunakan tanda bintang, untuk teks tebal dan miring bisa juga menggunakan garis bawah (underscore) seperti ini:

__teks tebal__
_teks miring_
Membuat Link
Link dapat kita buat dengan tanda kurung seperti ini:

[link ke petanikode](https://www.petanikode.com/)
Hasilnya:

link ke petanikode

Kita juga bisa menambahkan title untuk tooltips:

[link ke petanikode](https://www.petanikode.com/ "Pergi ke petanikode.com")
Hasilnya:

link ke petanikode

Selain menggunakan tanda kurung, kita juga bisa membuat link langsung dengan menuliskan URL lengkapnya.

Contoh:

https://en.wikipedia.org/wiki/Markdown
Maka akan menghasilkan:

https://en.wikipedia.org/wiki/Markdown

Menyisipkan Gambar
Caranya hampir sama dengan membuat link. Kita tinggal tambahkan tanda seru (!) di depannya.

Contoh:

![Gambar teks editor VS Code](https://www.petanikode.com/img/markdown/markdown-vscode.png)
Hasilnya:

Gambar teks editor VS Code
Membuat List
List dapat kita buat seperti ini:

* Milk
* Bread
    * Wholegrain
* Butter


1. Tidy the kitchen
2. Prepare ingredients
3. Cook delicious things
Hasilnya:

Milk
Bread
Wholegrain
Butter
Tidy the kitchen
Prepare ingredients
Cook delicious things
Untuk unordered list, kita bisa menggunakan tanda bintang (*) dan juga minus (-).

Contoh:

- item 1
- item 2
- item 3
Membuat Todo List atau Checklist
Sebenarnya ini pengembangan dari markdown. Tidak semua editor mendukung fitur ini.

Contoh:

**Tugas hari ini:**

- [x] Menulis artikel tentang markdown
- [ ] Belajar Git di Petanikode
- [ ] Belajar Bahasa pemrograman Rust
- [x] Membuat template blog dengan bootstrap
Maka akan menghasilkan seperti ini:

Tugas hari ini:

 Menulis artikel tentang markdown
 Belajar Git di Petanikode
 Belajar Bahasa pemrograman Rust
 Membuat template blog dengan bootstrap
Menyisipkan Quote
Pada HTML, kita mengenal tag <blockquote> untuk membuat kutipan. Pada markdown, kita bisa membuatnya seperti ini:

> To be or not to be, that is the question.
Hasilnya:

To be or not to be, that is the question.

Format Markdown Tingkat Lanjut
Format markdown yang baru saja kita pelajari adalah format dasar yang harus diingat. Masih ada beberapa format lagi:

Menulis Inline Code
Inline code sangat sering saya gunakan dalam teks. Cara membuatnya dengan menggunakan tanda (`).

Contoh:

Perintah `apt-get` adalah perintah untuk menginstall paket di Ubuntu.
Hasilnya:

Perintah apt-get adalah perintah untuk menginstall paket di Ubuntu.

Menulis Source Code
Source code sering saya tulis dengan markdown. Lalu menggunakan Prism.js untuk syntax higlighting.

Contoh:

```java
class HelloWorld{
    public static void main(String[] argumen){
        System.out.println("Hello World!");
    }
}
```
Hasilnya:

class HelloWorld{
    public static void main(String[] argumen){
        System.out.println("Hello World!");
    }
}
Tanda ``` berfungsi untuk menulis source code. Lalu pada pembuka kita tambahkan nama bahasanya agar teksnya berwarna (syntax highligting).

Membuat Tabel
Tabel di markdown dapat dibuat dengan cara sperti ini:

| Name  | Age |
| ----- | --- |
| udin   | 17  |
| Lintang | 19  |


---
| Nama      | Aditya Bani Isro |
| ----------- | ----------- |
| NIM     | 312010134       |
| Kelas   | TI.20.A.1        |

## Langkah langkah praktikum 5
Disini saya menggunakan texy editor Visual Studio Code

![imgmulai!](assets/img/mulai.PNG)

Persiapan membuat dokumen HTML dengan nama file Lab5_javascript.html seperti berikut.

![img1!](assets/img/1.PNG)
![img2!](assets/img/2.PNG)

## Javascript Dasar
Pemakaian Alert sebagai property window.

![img3!](assets/img/3.PNG)
![img4!](assets/img/4.PNG)

Pemakaian method dalam objek

![img5!](assets/img/5.PNG)
![img6!](assets/img/6.PNG)

Pemakaian Prompt

![img7!](assets/img/7.PNG)
![img8!](assets/img/8.PNG)
![img9!](assets/img/9.PNG

Pembuatan fungsi dan cara pemanggilannya

![img10!](assets/img/10.PNG)
![img11!](assets/img/11.PNG)

## Dasar Pemrograman Di Javascript
Operasi dasar aritmatika

![img12!](assets/img/12.PNG)
![img13!](assets/img/13.PNG)

Seleksi kondisi (if..else)

![img14!](assets/img/14.PNG)
![img15!](assets/img/15.PNG)

Penggunaan operator switch untuk seleksi kondisi

![img16!](assets/img/16.PNG)
![img17!](assets/img/17.PNG)
![img18!](assets/img/18.PNG)

## Pembuatan Form
Form Input

![img19!](assets/img/19.PNG)
![img20!](assets/img/20.PNG)

Form Button.

![img21!](assets/img/21.PNG)
![img22!](assets/img/22.PNG)

## HTML DOM
Pilihan menggunakan checkbox dengan perhitungan otomatis

![img23!](assets/img/23.PNG)
![img24!](assets/img/24.PNG)

## Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form

## Jawaban
Membuat validasi nama, No.Telp, Email

## 1. Nama
Disini saya akan memberikan validasi berupa inputan hanya boleh menggunakan Huruf/Alphabet saja. Contoh : Bani (benar), Bani04 (salah)

![img25!](assets/img/25.PNG)

Penjelasan
- Membuat nama function Alphabet, dengan parameter dinamis yaitu (nilai,pesan)
- Data yang boleh dimasukkan adalah berupa "a-zA-Z"
- Jika selain data "a-zA-Z" ini dimasukkan, maka akan muncul pesan Alert "alert(pesan);"

![img26!](assets/img/26.PNG)

## No. Telp
Pada bagian ini akan saya berikan validasi berupa hanya angka saja yang boleh di inputkan, contoh: 12345 (benar), 123AB (salah).

![img27!](assets/img/27.PNG)

Penjelasan:

- var numberExp = /^[0-9]+$/; merupakan variabel numberExp yang diberi batasan validasi angka 0-9
- Arti Match pada "if(nilai.value.match(numberExp))" adalah string.match(), mencari string menggunakan Regular Expression (Regex)
- Jika salah atau inputan tidak benar maka akan ada pesan alert "alert(pesan);"

![img28!](assets/img/28.PNG)

## Email
Pada email akan diberikan validasi masih berupa Regular Expression. Contoh: adityabani@gmail.com (benar), adityabani@gmail. (salah).

![img29!](assets/img/29.PNG)

Penjelasan:

- membuat variabel email " var email = /^([a-zA-Z0-9_.+-])+@(([a-zA-Z0-9-])+.)+([a-zA-Z0-9]{2,4})+$/; " berupa huruf, angka dan simbol yang diperbolehkan dalam input sebuah email. Jika email salah maka akan ada pesan alert "alert(pesan);"

![img30!](assets/img/30.PNG)

## Berikut Penulisan form yang benar

![img31!](assets/img/31.PNG)
![img32!](assets/img/32.PNG)
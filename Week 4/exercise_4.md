# Kamis - Mengenal Tipe data String dan Konsep Looping atau Perulangan

Hari ini mari kita berkenalan dengan string dan perulangan, atau sering disebut juga sebagai looping atau iteration di JavaScript.

Materi & Referensi :
- :notebook_with_decorative_cover:
[Memahami Tipe Data String pada JavaScript](../modules/js-string-reference.md)
- :notebook_with_decorative_cover:
[Memahami Perulangan atau Looping](../modules/js-first-time.md#loopiteration)
- :notebook_with_decorative_cover:
[Memahami Built-in Object Math](../modules/math-object-js.md)

Setelah kalian membaca materi diatas maka selanjutnya kita asah kemampuan kita dengan mengerjakan Soal di bawah ini :

# String
Soal latihan string ini memiliki 4 nomor. Simpan dengan nama seperti berikut :
- exercise_4_string_1.js
- exercise_4_string_2.js
- exercise_4_string_3.js
- exercise_4_string_4.js

## 1. Let's Form a Sentence

### Problem

Pada tugas ini kamu diminta untuk melakukan penambahan string menggunakan simbol +. Disediakan variable word. Tambahkan nilai word satu per satu dengan nilai variable lain untuk membentuk sebuah kalimat. Jangan lupa menambahkan spasi di setiap kata, dan tampilkan di console hasil penggabungannya! **Kamu tidak perlu membuat variable baru!**

### Skeleton Code

```javascript
var word = 'JavaScript';
var second = 'is';
var third = 'awesome';
var fourth = 'and';
var fifth = 'I';
var sixth = 'love';
var seventh = 'it!';
```

### Output

```
JavaScript is awesome and I love it!
```

## 2. Index Accessing - 1 by 1

### Problem

Pada tugas ini kamu diminta untuk "memecah" sebuah kalimat dan menampilkan setiap kata didalamnya. Untuk soal nomor ini, gunakan akses satu per satu karakter dari string untuk mengambil setiap huruf dalam kata. Terasa manual? Tidak apa-apa, kita coba ini dulu untuk saat ini.

### Hints

Saat kamu mendapatkan tiap huruf, untuk membentuk setiap kata kamu tinggal menggunakan simbol + untuk membentuk kata tersebut!

### Skeleton Code

```javascript
var word = 'wow JavaScript is so cool';
var exampleFirstWord = word[0] + word[1] + word[2];
var secondWord; // do your own!
var thirdWord; // do your own!
var fourthWord; // do your own!
var fifthWord; // do your own!

console.log('First Word: ' + exampleFirstWord);
console.log('Second Word: ' + secondWord);
console.log('Third Word: ' + thirdWord);
console.log('Fourth Word: ' + fourthWord);
console.log('Fifth Word: ' + fifthWord);
```

### Output

```
First Word: wow
Second Word: JavaScript
Third Word: is
Fourth Word: so
Fifth Word: cool
```

## 3. Breaking Sentence (Again) using Substring

### Problem

Mirip seperti soal nomor 2, namun kali ini gunakan substring untuk mengambil potongan dari tiap kata!

### Skeleton Code

```javascript
var word3 = 'wow JavaScript is so cool';
var exampleFirstWord3 = word.substring(0, 3);
var secondWord3; // do your own!
var thirdWord3; // do your own!
var fourthWord3; // do your own!
var fifthWord3; // do your own!

console.log('First Word: ' + exampleFirstWord);
console.log('Second Word: ' + secondWord);
console.log('Third Word: ' + thirdWord);
console.log('Fourth Word: ' + fourthWord);
console.log('Fifth Word: ' + fifthWord);
```

### Output

```
First Word: wow
Second Word: JavaScript
Third Word: is
Fourth Word: so
Fifth Word: cool
```

## 4. Breaking Sentence (yet Again) and Count Each Length

### Problem

Mirip seperti soal nomor 3, tapi tampilkan juga panjang kata masing-masingnya!

### Skeleton Code

Buatlah variable-variable baru untuk menyimpan panjang string, dan ubah console dibawah untuk menampilkan nya.

```javascript
var word4 = 'wow JavaScript is so cool';
var exampleFirstWord4 = word.substring(0, 3);
var secondWord4; // do your own!
var thirdWord4; // do your own!
var fourthWord4; // do your own!
var fifthWord4; // do your own!

var firstWordLength = exampleFirstWord4.length;
// create new variables around here

console.log('First Word: ' + exampleFirstWord + ', with length: ' + firstWordLength);
console.log('Second Word: ' + secondWord);
console.log('Third Word: ' + thirdWord);
console.log('Fourth Word: ' + fourthWord);
console.log('Fifth Word: ' + fifthWord);
```

### Output

```
First Word: wow, with length: 3
Second Word: JavaScript, with length: 10
Third Word: is, with length: 2
Fourth Word: so, with length: 2
Fifth Word: cool, with length: 4
```


# Looping 1

Soal looping ini memiliki 3 nomor. Simpan dengan nama seperti berikut :
- exercise_4_looping1_1.js
- exercise_4_looping1_2.js
- exercise_4_looping1_3.js

## 1. Melakukan *Looping* Menggunakan `While`

### Problem

Pada tugas ini kamu diminta untuk melakukan looping dalam JavaScript dengan menggunakan syntax while. Untuk membuat tantangan ini lebih menarik, kamu juga diminta untuk membuat suatu looping yang menghitung maju dan menghitung mundur. Jangan lupa tampilkan di console juga judul 'LOOPING PERTAMA' dan 'LOOPING KEDUA'.

### Output

```
LOOPING PERTAMA
2 - I love coding
4 - I love coding
6 - I love coding
8 - I love coding
10 - I love coding
12 - I love coding
14 - I love coding
16 - I love coding
18 - I love coding
20 - I love coding
LOOPING KEDUA
20 - I will become fullstack developer
18 - I will become fullstack developer                                                                              
16 - I will become fullstack developer
14 - I will become fullstack developer
12 - I will become fullstack developer
10 - I will become fullstack developer
8 - I will become fullstack developer
6 - I will become fullstack developer
4 - I will become fullstack developer
2 - I will become fullstack developer
```

## 2. Melakukan *Looping* Menggunakan `For`

### Problem

Pada tugas ini kamu diminta untuk melakukan *looping* dalam JavaScript dengan menggunakan *syntax* `for`. Untuk membuat tantangan ini lebih menarik, kamu juga diminta untuk membuat suatu *looping* yang menghitung maju dan menghitung mundur. Jangan lupa tampilkan di console juga judul 'LOOPING PERTAMA' dan 'LOOPING KEDUA'.

### Hints

> Operator `++` disebut dengan operator *Increment*
> Operator `--` disebut dengan operator *Decrement*

### Output

```
LOOPING PERTAMA
1 - I love coding
2 - I love coding
3 - I love coding
4 - I love coding
5 - I love coding
6 - I love coding
7 - I love coding
8 - I love coding
9 - I love coding
10 - I love coding
11 - I love coding
12 - I love coding
13 - I love coding
14 - I love coding
15 - I love coding
16 - I love coding
17 - I love coding
18 - I love coding
19 - I love coding
20 - I love coding
LOOPING KEDUA
20 - I will become fullstack developer
19 - I will become fullstack developer
18 - I will become fullstack developer
17 - I will become fullstack developer
16 - I will become fullstack developer
15 - I will become fullstack developer
14 - I will become fullstack developer
13 - I will become fullstack developer
12 - I will become fullstack developer
11 - I will become fullstack developer
10 - I will become fullstack developer
9 - I will become fullstack developer
8 - I will become fullstack developer
7 - I will become fullstack developer
6 - I will become fullstack developer
5 - I will become fullstack developer
4 - I will become fullstack developer
3 - I will become fullstack developer
2 - I will become fullstack developer
1 - I will become fullstack developer
```

## 3. Angka Ganjil dan Genap

Hint: kamu akan menggunakan kondisional juga di kasus ini.

### Problem

1. Buatlah sebuah perulangan 1 - 100 dengan pertambahan *counter* sebanyak 1
2. Di dalam perulangan, periksa setiap angka *counter*:
    - Apabila angka *counter* adalah angka genap, tuliskan **GENAP**
    - Apabila angka *counter* adalah angka ganjil, tuliskan **GANJIL**
3. Buatlah 3 perulangan baru dari 1 - 100, dengan pertambahan *counter* sebesar 2, 5, dan 9.
4. Pada 3 perulangan baru ini periksa setiap angka *counter*:
    - Apabila bukan kelipatan yang ditentukan tidak perlu menuliskan apa-apa
    - Apabila angka *counter* adalah kelipatan 3 dengan pertambahan 2, kelipatan 6 dengan pertambahan 5, dan kelipatan 10 dengan pertambahan 9, tuliskan:
    - `"3 kelipatan 3"` dan seterusnya.


### output

```javascript
//contoh - ganjil genap
//counter sekarang = 1,
//output
"GANJIL"
//counter sekarang = 2,
//output
"GENAP"
// dan seterusnya :)

//contoh - untuk pertambahan counter 2
//counter sekarang = 1,
//output
""
//counter sekarang = 3,
//output
"3 KELIPATAN 3"
// dan seterusnya :)

//contoh - untuk pertambahan counter 5
//counter sekarang = 1,
//output
""
//counter sekarang = 6,
//output
"6 KELIPATAN 6"
// dan seterusnya :)

//contoh - untuk pertambahan counter 9
//counter sekarang = 1,
//output
""
//counter sekarang = 10,
//output
"10 KELIPATAN 10"
// dan seterusnya :)
```

# Looping 2

Soal looping - asterisk ini memiliki 3 nomor. Simpan dengan nama seperti berikut :
- exercise_4_looping2_1.js
- exercise_4_looping2_2.js
- exercise_4_looping2_3.js

## 1. Menyusun Barisan Bintang

### Problem

Pada tugas ini kamu diminta untuk melakukan looping dalam JavaScript untuk menampilkan di console barisan asterisks (bintang). Setiap baris memiliki 1 simbol '*'.

### Skeleton Code

```javascript
var rows1; // input the number of rows

// do loops to display asterisks in the console.
```
### Output

jika rows1 = 5

```
*
*
*
*
*
```

## 2. Menyusun Barisan Bintang Dengan Nested Looping

### Problem

Pada tugas ini kamu diminta untuk melakukan looping dalam JavaScript untuk menampilkan di console barisan asterisks (bintang). Setiap baris memiliki jumlah simbol '*' sesuai dengan jumlah baris. Manfaatkan **nested loop** atau loop di dalam loop untuk menyelesaikan kasus ini.

### Skeleton Code

```javascript
var rows2; // input the number of rows

// do loops to display asterisks in the console.
```
### Output

jika rows2 = 5

```
*****
*****
*****
*****
*****
```

## 3. Menyusun Barisan Tangga Bintang Dengan Nested Looping

### Problem

Pada tugas ini kamu diminta untuk melakukan looping dalam JavaScript untuk menampilkan di console barisan asterisks (bintang) dalam bentuk tangga. Setiap baris memiliki jumlah simbol '*' sesuai dengan nomor baris. Baris pertama, hanya ada satu bintang. Baris kedua, dua bintang, baris ketiga tiga bintang, dan seterusnya. Manfaatkan **nested loop** atau loop di dalam loop untuk menyelesaikan kasus ini.

### Skeleton Code

```javascript
var rows3; // input the number of rows

// do loops to display asterisks in the console.
```
### Output

jika rows3 = 5

```
*
**
***
****
*****
```

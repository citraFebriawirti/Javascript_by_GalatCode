# Operator

Operator adalah simbol yang digunakan untuk melakukan operasi pada suatu nilai dan variabel.

Operator dalam pemrograman terbagi dalam 6 jenis:

1. Operator aritmatika;
2. Operator Penugasan (Assignment);
3. Opeartor relasi atau perbandingan;
4. Operator Logika;
5. Operator Bitwise;
6. Operator Ternary;

## 1. Operator aritmatika

Operator aritmatika merupakan operator untuk melakukan operasi aritmatika seperti penjumlahan, pengurangan, pembagian, perkalian, dsb.

adapun soal yang dapat kita terapkan sebagai berikut :

```
let a = 3
let b = 5
let c = 15
```

| Nama Operator   | Simbol | Contoh                           |
| --------------- | ------ | -------------------------------- |
| **Penjumlahan** | +      | `` console.log(`${a} + ${b}`)``  |
| **Pengurangan** | -      | `` console.log(`${c} - ${b}`)``  |
| **Perkalian**   | \*     | `` console.log(`${a} * ${b}`)``  |
| **Pemangkatan** | \*\*   | `` console.log(`${a} ** ${b}`)`` |
| **Pembagian**   | /      | `` console.log(`${c} + ${b}`)``  |
| **Sisa Bagi**   | %      | `` console.log(`${c} % ${3}`)``  |

Adapun soal yang sesuai denga aritmatika dapat dilihat sebagai berikut :

!! Latihan

```
Perintah :
Buatlah sebuah logika perhitungan dengan menggunakan operator aritmatika
dengan hasil penjumlahan sama dengan 15 dan hasil pengurangan dengan sama dengan 1
yang terlebih dahulu dibuatkan dalam varible let dulu, selamat mengerjakan !! 😎
```

```
Buat jawaban di replit kirimkan linknya ke kak citra

```

## 2. Operator Penugasan

Operator penugasan adalah operator yang digunakan untuk memberikan tugas kepada variabel. Biasanya digunakan untuk mengisi variabel.

| Nama Operator                 | Simbol | Contoh                     |
| ----------------------------- | ------ | -------------------------- |
| **Pengisian Nilai**           | =      | ` let nilai = 100`         |
| **Pengisian dan Penambahan**  | +=     | ` console.log(nilai += 5)` |
| **Pengisian dan Pengurangan** | -=     | ` console.log(nilai -= 5)` |
| **Pengisian dan Perkalian**   | \*=    | ` console.log(nilai *= 5)` |
| **Pengisian dan Pemangkatan** | \*\*=  | ` console.log(nilai **=5)` |
| **Pengisian dan Pembagian**   | /=     | ` console.log(nilai /= 5)` |
| **Pengisian dan Sisa bagi**   | %=     | ` console.log(nilai %= 5)` |

Adapun soal yang sesuai dengan penugasan dapat dilihat sebagai berikut :

!! Latihan

```
Perintah :
let nama = "Senja"
let nilai = 80

maka logika dengan operator penugasan dengan menggunakan (pengisian dan penjumlahan),
semangat ya mengerjakannya !! 🤑

```

## 3. Operator Perbandingan

Operator relasi atau perbandingan adalah operator yang digunakan untuk membandingkan dua nilai.

Operator perbandingan akan menghasilkan sebuah nilai boolean `true` dan `false.`

| Nama Operator               | Simbol      |
| --------------------------- | ----------- |
| **Lebih Kecil**             | <           |
| **Lebih besar**             | >           |
| **Sama Dengan**             | == atau === |
| **Tidak Sama dengan**       | !=          |
| **Lebih Besar Sama dengan** | >=          |
| **Lebih Kecil Sama dengan** | <=          |

contoh soal yang menerapkan operator perbandingan yaitu sebagai berikut :

### 1. Lebih kecil dan lebih kecil sama dengan

```
var a = 3;
var b = 4;
console.log(a < b); // true
console.log(a <= b); // true

var a = 5;
var b = 5;
console.log(a < b); // false
console.log(a <= b); // true
```

### 2. Lebih besar dan lebih besar sama dengan

```
var a = 3;
var b = 4;
console.log(a > b); // false
console.log(a >= b); // false

var a = 5;
var b = 5;
console.log(a > b); // false
console.log(a >= b); // true
```

### 3. Tidak sama dengan

```
var a = true;
var benar = true;
console.log(a !== benar); // false

var a = 12;
var b = 4;
console.log(a !== b); // true

var a = 7;
var b = "7";
console.log(a !== b); // true !

var a = "7";
var b = "7";
console.log(a !== b); // false
```

### 4. Sama dengan

```
var a = true;
var benar = true;
console.log(a == benar); // true

var a = 12;
var b = 4;
console.log(a == b); // false

var a = 7;
var b = "7";
console.log(a == b); // true
```

```
var a = true;
var benar = true;
console.log(a === benar); // true

var a = 12;
var b = 4;
console.log(a === b); // false

var a = 7;
var b = "7";
console.log(a === b); // false !

var a = "7";
var b = "7";
console.log(a === b); // true
```

## 4. Operator Logika

Operator logika digunakan untuk melakukan operasi terhadap dua nilai `boolean.`

| Nama Operator | Simbol |
| ------------- | ------ |
| **AND**       | &&     |
| **OR**        |        |
| **Negasi**    | ~      |

adapun contoh soal yang menerapkan operator logika, yaitu sebagai berikut :

```
var a = true;
var b = false;

var hasil1 = a && b;
console.log(hasil1); //false

var hasil2 = a && a;
console.log(hasil2); //true

var hasil3 = a || b;
console.log(hasil3); //true

var hasil4 = !a;
console.log(hasil4); //false
```

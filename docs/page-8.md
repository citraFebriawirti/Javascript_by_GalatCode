# Tipe Data

![Teks alternatif](./asset/image/tipe%20data.png)

Dalam pemrograman, tipe data merupakan konsep penting. Untuk dapat beroperasi pada variabel, penting untuk mengetahui sesuatu tentang tipenya. Tanpa tipe data, komputer tidak dapat menyelesaikan masalah di bawah ini:

```
var x = 11 + "Alvin";
```

Apakah masuk akal untuk menambahkan "Alvin" dengan sebelas? Apakah akan menghasilkan kesalahan atau akan memberikan hasil? JavaScript akan memperlakukan contoh di atas sebagai berikut:

```
var x = "11" + "Alvin";
```

## 1. Tipe Data Primitiv

Kali ini kita akan membahas beberapa basic tipe data yaitu tipe data primitif.

=> Primitif (nilai primitif, tipe data primitif) adalah data yang bukan objek dan tidak memiliki method. Dalam JavaScript, ada 6 tipe data primitif: string, number, boolean, null, undefined, symbol (ECMAScript 2015).

Adapun 6 tipe data priitif dapat dijelaskan sebagai berikut :

### 1. Number

Value dari tipe data number adalah nilai numerik. Dalam program JavaScript, tipe data number ditulis sebagai berikut:

```
50; // bilangan int
```

```
3.14; // bilangan desimal
```

Pengunaannya : `let umur = 20`

### 2. String

Tipe data dasar berikutnya adalah string. String digunakan untuk merepresentasikan teks. String ditulis dengan melampirkan kontennya dalam tanda kutip.

Kita dapat menggunakan single quotes, double quotes, atau backticks untuk menandai string, selama tanda kutip di awal dan akhir string cocok.

```
'Ini adalah kelas javascript'
```

```
"Ini adalah kelas javascript"
```

```
`Ini adalah kelas javascript`
```

Tanda kutip yang didahului oleh backslash tidak akan mengakhiri string tetapi menjadi bagian darinya. Ketika karakter "n" muncul setelah backslash (\n), itu ditafsirkan sebagai baris baru. Demikian pula, "t" setelah backslash (\t) berarti karakter tab.

```
"Ini baris pertama\nDan ini baris kedua";

//Output:
Ini baris pertama
Dan ini baris kedua
```

Bagaimana dengan penulisan "Tambahkan dengan \n" ?

```
"Tambahkan dengan \"\\n\""
```

Bagimana dengan penulisan "Hari ini adalah hari Jum'at" ?

```
"Hari ini adalah hari Jum'at"
```

### 3. Boolean

Boolean seringkali digunakan untuk nilai yang hanya memiliki dua kemungkinan, seperti "yes" dan "no" atau "on" dan "off". Untuk tujuan ini, JavaScript memiliki tipe Boolean, yang hanya memiliki dua nilai, true dan false.

```
console.log(3 > 2);
// → true
console.log(3 < 2);
// → false
```

## Tipe Data Non Primitiv

1. Object
2. Array
3. Function

kok ga dijelaskan ? simak yok

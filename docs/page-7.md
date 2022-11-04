# Variabel

[![Analogi Variabel](https://www.petanikode.com/img/js/var/piring-variabel.png)](hhttps://images.app.goo.gl/UFjV1eqknuoBC1Me6)

### Pengertian Variable

Variabel umumnya digunakan untuk menyimpan informasi, data atau nilai yang akan dikelola dalam sebuah program

[![Analogi Variabel](https://www.petanikode.com/img/c/var/variabel-tipe-data.webp)](https://images.app.goo.gl/dEbDypNU9UzR788e9)

Pada JavaScript setidaknya ada tiga cara untuk mendeklarasikan sebuah variabel, yaitu menggunakan keyword var, let, dan const. Pada versi ECMAScript 2015 (ES6) dikenalkan deklarasi variabel dengan let dan const untuk menggantikan var yang dinilai kontroversial dan rawan menimbulkan bug.

## Ketentuan dalam variable

Berikut beberapa aturan dalam penamaan variabel yang perlu Anda ketahui:

> - Harus dimulai dengan huruf atau underscore (\_).
> - Dapat terdiri dari huruf, angka, dan underscore (\_) dengan berbagai kombinasi.
> - Tidak boleh mengandung spasi (whitespace). Jika penamaan variabel lebih dari dua kata, tuliskan secara camelCase. Contoh firstName, lastName, catName, dll.
> - Tidak boleh mengandung karakter spesial (! . , / \ + \* = dll.)

## Jenis-jenis Variable dalam Javascript

Adapun berbedaan Var, Let dan const dapat dilihat di bawah ini
[![Analogi Variabel](https://miro.medium.com/max/1400/0*mYuuRwjUfUOAdHpo.jpg)](https://images.app.goo.gl/EjrEzZWJznJUAV5f6)

|               | Var             | let          | Const             |
| ------------- | --------------- | ------------ | ----------------- |
| **Penugasan** | Bisa diubah     | Bisa diubah  | Tidak Bisa diubah |
| **Scope**     | function-scoped | block-scoped | block-scoped      |

Penjelasan detail yaitu sebagai berikut : 😍

#### 1. Penugasan

**Var**

_[Lihat code ](https://playcode.io/1003106)_

```
var kelas = "javascript"
kelas = "javascript di kafekoding"
console.log(kelas)

// Output
javascript di kafekoding
```

**Let**

_[Lihat code ](https://playcode.io/1003115)_

```
let nama = "senja"
nama = "sunrise"
nama = "Bintang"

console.log(nama)

// output :
Bintang
```

**Const**

_[Lihat code ](https://playcode.io/1003124)_

```
const nama = "Citra Febriawirti"
nama = "Senja anugrah"

console.log(nama)

// Output :
Cannot assign to "nama" because it is a constant
```

### 2. Scope

**Var**

_[Lihat code ](https://playcode.io/1003129)_

```
for(var i=1; i<6; i++){
  console.log(i)
}
console.log(i)

// Output :
1
2
3
4
5
6
```

**Let**

_[Lihat code ](https://playcode.io/1003140)_

```
for(let i=1; i<6; i++){
  console.log(i)
}
console.log(i)

// Output :
1
2
3
4
5
error : i is not defined
```

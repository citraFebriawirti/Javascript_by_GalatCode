# Variabel

[![Analogi Variabel](https://www.petanikode.com/img/js/var/piring-variabel.png)](hhttps://images.app.goo.gl/UFjV1eqknuoBC1Me6)

### Pengertian Variable

Variabel umumnya digunakan untuk menyimpan informasi, data atau nilai yang akan dikelola dalam sebuah program

[![Analogi Variabel](https://www.petanikode.com/img/c/var/variabel-tipe-data.webp)](https://images.app.goo.gl/dEbDypNU9UzR788e9)

Pada JavaScript setidaknya ada tiga cara untuk mendeklarasikan sebuah variabel, yaitu menggunakan keyword var, let, dan const. Pada versi ECMAScript 2015 (ES6) dikenalkan deklarasi variabel dengan let dan const untuk menggantikan var yang dinilai kontroversial dan rawan menimbulkan bug.

Adapun berbedaan Var, Let dan const dapat dilihat di bawah ini
[![Analogi Variabel](https://miro.medium.com/max/1400/0*mYuuRwjUfUOAdHpo.jpg)](https://images.app.goo.gl/EjrEzZWJznJUAV5f6)

|               | Var             | let          | let          |
| ------------- | --------------- | ------------ | ------------ |
| **Penugasan** | Bisa diubah     | Bisa diubah  | Bisa diubah  |
| **Scope**     | function-scoped | block-scoped | block-scoped |
| 3             | Codewars        |              |              |
| 4             | Leetcode        |              |              |

Penjelasan detail yaitu sebagai berikut : 😍

#### 1. Penugasan

**Var**

```
var kelas = "javascript"
kelas = "javascript di kafekoding"
console.log(kelas)

// Output
javascript di kafekoding
```

**[Lihat code ](https://playcode.io/1003106)**

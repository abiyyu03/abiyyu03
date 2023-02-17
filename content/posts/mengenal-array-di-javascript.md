---
title: "Mengenal Array Di Javascript Bagian 1"
date: 2022-08-22T10:50:31+07:00
tags: ["javascript","programming"]
draft: false
---
![](https://images.unsplash.com/photo-1544396821-4dd40b938ad3?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=873&q=80)
Photo by Viktor Talashuk from unsplash
 
<!-- ## Apa Itu Array ?

## Mengapa Menggunakan Array ?

## Macam-macam Array

## Penerapan Array Di Javascript -->


Artikel kali ini akan membahas salah satu struktur data yang umum digunakan, yaitu Array. Kita juga akan mengenal lebih dalam tentang istilah dan konsep array.

## Pengertian Array
Array adalah salah satu jenis struktur data yang menyimpan sekelompok nilai. Array dapat menyimpan lebih dari satu nilai dengan tipe data yang berbeda-beda. Untuk menuliskan Array, kita perlu menambahkan tanda ```[]``` sebagai pembungkus nilai Array.
```js
//contoh array
[1,2,3,4]
```
### Angka Index
Setiap nilai di dalam Array mempunyai identitas unik berupa angka index. angka Index dimulai dari angka 0, untuk nilai array pertama, index 1 untuk nilai array kedua, dan seterusnya. 

Supaya lebih mudah memahami, lihatlah contoh array dibawah ini :

```js
['satu','dua','tiga']
```
index dari nilai **satu** adalah **0**

index dari nilai **dua** adalah **1**

index dari nilai **tiga** adalah **2**

Angka Index diibaratkan sebagai identitas yang mewakili nilai suatu nilai array.

### Menuliskan Array di Javascript

Sebagai contoh, kita akan menuliskan nama-nama hewan didalam sebuah array
```js
['kucing','kelinci','kuda','sapi']
```

Dalam penerapannya, biasanya array akan dimasukan kedalam sebuah variabel atau konstanta. Maka kita bisa menuliskannya seperti berikut ini

```js
const namaHewan = ['kucing','kelinci','kuda','sapi']
```

Bagaimana jika kita ingin mengambil salah satu atau beberapa nilai di dalam array ?, misalnya kita ingin mengambil hewan yang bernama kucing. maka caranya adalah dengan mengakses index dari element yang akan kita ambil nilainya. seperti yang kita tahu sebelumnya, bahwa index array dimulai dari angka 0. Dan kita tahu bahwa element 'kucing' berada pada index 0, maka kita bisa menampilkan element kucing dengan cara :
```js
namaHewan[0]
```


## Referensi
- https://www.geeksforgeeks.org/introduction-to-arrays/
- https://medium.com/@audira98/what-is-array-2393965d047f

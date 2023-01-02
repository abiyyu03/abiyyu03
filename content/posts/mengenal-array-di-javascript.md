---
title: "Mengenal Array Di Javascript"
date: 2022-08-22T10:50:31+07:00
tags: ["struktur-data","javascript","konsep-dasar","array"]
draft: false
---
![](https://images.unsplash.com/photo-1544396821-4dd40b938ad3?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=873&q=80)
Photo by Viktor Talashuk from unsplash
 
<!-- ## Apa Itu Array ?

## Mengapa Menggunakan Array ?

## Macam-macam Array

## Penerapan Array Di Javascript -->

Array adalah salah satu jenis struktur data yang menyimpan sekelompok nilai. Array dapat menyimpan lebih dari satu nilai dengan tipe data yang berbeda-beda. Untuk menuliskan Array, kita perlu menambahkan tanda ```[]``` sebagai pembungkus nilai Array.
```
["satu",2,3,"empat"]
```
### Angka Index
Setiap nilai di dalam Array mempunyai identitas unik berupa angka index. Angka Index dimulai dari angka 0, untuk nilai array pertama, index 1 untuk nilai array kedua, dan seterusnya. Dari sini, bisa kita ketahui bahwa jumlah angka index adalah **jumlah nilai array - 1**. 
 

Supaya lebih mudah memahami, lihatlah contoh array dibawah ini :

```
['satu','dua','tiga']
```
index dari nilai **satu** adalah **0**

index dari nilai **dua** adalah **1**

index dari nilai **tiga** adalah **2**

Angka Index diibaratkan sebagai ID yang mewakili nilai suatu nilai array. Misalnya kita ingin mengambil suatu nilai di dalam array, maka kita tidak perlu menuliskan nilai apa yang akan kita ambil, tetapi cukup dengan menuliskan angka index dari nilai array tersebut. 

### Menuliskan Array di Javascript

Untuk menuliskan array di javascript, 

sebagai contoh, kita akan menuliskan nama-nama hewan didalam sebuah array
```
['kucing','kelinci','kuda','sapi']
```

Di dalam penerapannya, biasanya array akan dimasukan kedalam sebuah variabel, maka kita bisa menuliskannya seperti berikut ini

```
const namaHewan = ['kucing','kelinci','kuda','sapi']
```

Pertanyaan berikutnya, bagaimana kita mengambil salah satu atau beberapa nilai di dalam array ?, misalnya kita ingin mengambil hewan yang bernama kucing. maka caranya adalah dengan mengakses index dari element yang akan kita ambil nilainya. seperti yang kita tahu sebelumnya, bahwa index array dimulai dari angka 0. Dan kita tahu bahwa element 'kucing' berada pada index 0, maka kita bisa menampilkan element kucing dengan cara :
```
console.log(namaHewan[0])
```


## Referensi
- https://www.geeksforgeeks.org/introduction-to-arrays/
- https://medium.com/@audira98/what-is-array-2393965d047f

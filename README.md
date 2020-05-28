# 04-JAVASCRIPT-TUGAS-MANIPULASI-DERET-ANGKA
Tugas Manipulasi Deret Angka Javascript Niomic
<hr>
Hallo Teman-Teman, Sekarang teman-teman memiliki tantangan untuk membuat sebuah function “deretAngka” yang menerima satu parameter (n) berupa integer dan akan menghasilkan deret angka dari satu sampai panjangnya sesuai dengan parameter (n) yang diinputkan tersebut,<br>
Dimana hasil deret angka tersebut memiliki ketentuan sebagai berikut :<br>

1. Jika angka dalam deret angka tersebut adalah kelipatan 3, maka nilai tersebut akan diganti menjadi “NIO”
2. Jika angka dalam deret angka tersebut adalah kelipatan 5, maka nilai tersebut akan diganti menjadi “MIC”
3. Jika angka dalam deret angka tersebut adalah kelipatan 3 dan 5, maka nilai tersebut akan diganti menjadi “NIOMIC”
4. Jika angka dalam deret angka tersebut BUKAN Kelipatan 3 dan 5, maka nilai angka tersebut tidak diganti.
<br>

__Contoh :__
- Angka 3, 6 dan 9 menjadi “NIO” karena adalah kelipatan 3
- Angka 5 dan 10 menjadi “MIC” karena adalah kelipatan 5
- Angka 15 menjadi “NIOMIC” karena merupakan kelipatan 3 dan 5.

<br>
Sekarang kita akan menuliskan code dasarnya: <br>

```
function deretAngka(n) {
 // tulis code jawabanmu di sini
}


console.log(deretAngka(10))
console.log(deretAngka(20))
console.log(deretAngka(30))
```
<br>

Lengkapilah code diatas, sehingga ketika dijalankan akan menghasilkan seperti dibawah ini : <br>
```

1 2 NIO 4 MIC NIO 7 8 NIO MIC

1 2 NIO 4 MIC NIO 7 8 NIO MIC 11 NIO 13 14 NIOMIC 16 17 NIO 19 MIC

1 2 NIO 4 MIC NIO 7 8 NIO MIC 11 NIO 13 14 NIOMIC 16 17 NIO 19 MIC NIO 22 23 NIO MIC 26 NIO 28 29 NIOMIC
```
 

# Langkah-langkah Membuat Media Pembelajaran Volume Kerucut

Media ini bertujuan untuk menunjukkan ke peserta didik bahwa volume kerucut sama dengan sepertiga dari volume tabung. Langkah-langkah di Geogebra ialah sebagai berikut.

## *Langkah 1: Membuat variabel tinggi dan radius*

tinggi dan radius akan disubstitusi pada *command* kerucut dan tabung.

*Commannd*-nya adalah sebagai berikut.

**tinggi = Slider(0, 10)**

**radius = Slider(0, 10)**

```
tinggi = Slider(0, 10)
```



## *Langkah 2: Membuat Kerucut*

Untuk dapat membuat kerucut, kita dapat menggunakan *command*  sebagai berikut.

**Cone(A, B, radius)**

*Command* tersebut akan menghasilkan kerucut dengan titik puncak di B.

Untuk membuat titik A, kita akan membuatnya misalnya di titik **(0, 0, 0)**, dan titik B di titik **(0, 0, tinggi)**



## *Langkah 3: Membuat Tabung*

Untuk dapat membuat tabung, kita dapat menggunakan *command* sebagai berikut.

**Sylinder(C, D, radius)**

*Command* tersebut akan menghasilkan tabung dengan titik puncak di D.

Kita ingin agar jarak antara kerucut dan tabung misalnya berjarak 1, sehingga titik C dan D berturut-turut **(2radius + 1, 0, 0)** dan (**2radius + 1, 0, tinggi)**



## *Langkah 4: Membuat teks dinamis*

Buat teks yang menampilkan **radius, tinggi, volume kerucut dan volume tabung**.



## *Langkah 5: Kostumisasi style*






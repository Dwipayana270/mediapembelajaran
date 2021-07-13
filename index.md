# Langkah-langkah Membuat Media Pembelajaran Volume Kerucut

Media Pembelajaran ini bertujuan untuk menunjukkan ke peserta didik bahwa volume kerucut sama dengan sepertiga dari volume tabung. Langkah-langkah di Geogebra ialah sebagai berikut.

Klik tautan si bawah untuk membuka Media Pembelajaran Volume Kerucut.

[Link Tautan]: https://www.geogebra.org/classic/mr4nh259	"Link Geogebra Volume Kerucut"



## *Langkah 1: Membuat variabel tinggi dan radius*

tinggi dan radius akan disubstitusi pada *command* kerucut dan tabung.

*Commannd*-nya adalah sebagai berikut.

```
tinggi = Slider(0, 10)
```

```
radius = Slider(0, 10)
```

Command ini

## *Langkah 2: Membuat Kerucut*

Untuk dapat membuat kerucut, kita dapat menggunakan *command*  sebagai berikut.

```
Cone(A, B, radius)
```

*Command* tersebut akan menghasilkan kerucut dengan titik puncak di B.

Untuk membuat titik A, kita akan membuatnya misalnya di titik **(0, 0, 0)**, dan titik B di titik **(0, 0, tinggi)**

sehingga kita bisa mengetik command sebagai berikut.

```
(0, 0, 0)
```

```
(0, 0, tinggi)
```

## *Langkah 3: Membuat Tabung*

Untuk dapat membuat tabung, kita dapat menggunakan *command* sebagai berikut.

```
Cylinder(C, D, radius)
```

*Command* tersebut akan menghasilkan tabung dengan titik puncak di D.

Kita ingin supaya tabung memiliki tinggi dan radius yang sama dengan kerucut, kita dapat membuat supaya tabung memiliki alas dan tinggi yang sama dengan kerucut. Command yang dapat di-*input* sebagai berikut.

```
Cylinder(A, B, radius)
```

## *Langkah 4: Membuat teks dinamis*

Buat teks yang menampilkan **radius, tinggi, volume kerucut dan volume tabung** dengan menggunakan fitur *text*.



Jika semua langkah sudah selesai, kita dapat menyesuaikan tampilan pada *applet* Geogebra sehingga mendukung media pembelajaran.

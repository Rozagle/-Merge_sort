# -Merge_sort

Verilen dizi: [16, 21, 11, 8, 12, 22]

1) Diziyi ikiye bölerek alt dizilere ayrılır.
[16, 21, 11] | [8, 12, 22]

2) Alt dizileri sırala:

a.Sol alt dizi: [16, 21, 11]

[16] | [21, 11]
[16] | [11, 21]
[11, 16, 21]

b.Sağ alt dizi: [8, 12, 22]

[8] | [12, 22]
[8] | [12, 22]
[8, 12, 22]

3) Birleştirme
   [11, 16, 21] | [8, 12, 22]  = >  [8, 11, 12, 16, 21, 22]

Big-O Gösterimi:
Merge Sort O(n log n)

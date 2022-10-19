# www.patika.dev-projeleri
Insertion Sort Projesi www.patika.dev projeleri
[Patika.dev](https://www.patika.dev/tr)

https://app.patika.dev/sercanalper

`[22,27,16,2,18,6]` Insertion Sort'u

A-) Sort Türü Aşamaları 

`[2,27,16,22,18,6]`  ### En küçük sayı tespit edilir, ilk sıradakiyle yer değiştirir.

`[2,6,16,22,18,27]`  ### Proses bu şekilde en küçük sayıyı tespit edip yer değiştirerek devam eder.

`[2,6,16,22,18,27]`  ### 16'nın kendisi istenilen değer olduğu için yer değiştirme yapılmadı.

`[2,6,16,18,22,27]`  ### Proses bu şekilde en küçük sayıyı tespit edip yer değiştirerek devam eder.

`[2,6,16,18,22,27]`  ### 22'nin kendisi istenilen değer olduğu için yer değiştirme yapılmadı.

`[2,6,16,18,22,27]`  ### 27  son değer olduğu için yer değiştirme yapılmadı. 


`[2,6,16,18,22,27]`  ### Son hal.


B-) "Big-O" Gösterimi

"**O(n^2)**"


C-) Time Complexity; Average Case,  Worst Case, Best Case.  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


`[2,6,16,18,22,27]`  ### Son hal. Buna göre "18" değeri ortada yer aldığı için **Average Case** 'dir.



D-) `[7,3,5,8,2,9,4,15,6]` dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

`[2,3,5,8,7,9,4,15,6]` ### En küçük sayı tespit edildi (2), ilk sıradakiyle yer değişti.

`[2,3,5,8,7,9,4,15,6]` ### 3'ün kendisi istenilen değer olduğu için yer değiştirme yapılmadı.

`[2,3,4,8,7,9,5,15,6]` ### 4 ile 5 yer değiştirdi.

`[2,3,4,5,7,9,8,15,6]` ### 5 ile 8 yer değiştirdi.

`[2,3,4,5,6,9,8,15,7]` ### 6 ile 7 yer değiştirdi.

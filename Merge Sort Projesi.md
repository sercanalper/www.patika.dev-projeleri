[Patika.dev](https://www.patika.dev/tr)

https://app.patika.dev/sercanalper

`[16,21,11,8,12,22]` Merge Sort'u

A-) Sort Türü Aşamaları 

**BÖLÜNME**

`[16, 21, 11, 8, 12, 22]` ### Önce dizinin içerdiği değerler 2'ye ayrılır.

`[16, 21, 11]` `[8, 12, 22]` ### Elde edilen 2 dizin de 2'ye bölünürler. Tek sayılı olması önemli değil, rastgele parçalanma devam eder. 

`[16]` `[21, 11]` `[8, 12]` `[22]` ### Bu dizinler de, her bir dizin tek bir değer içerene kadar bölünmeye devam eder.

`[16]` `[21]` `[11]` `[8]` `[12]` `[22]` ### Burada bölünme işlemi tamamlanmıştır. Sonrasında tekrar gruplaşma başlayacak.

**TEKRAR BİRLEŞME**

`[16]` `[11, 21]` `[8, 12]` `[22]` ### Tek değerli kalmış dizinler birbirleriyle birleşirlerken küçük değere sahip olan başa geçer.

`[11, 16, 21]` `[8, 12, 22]` ### Birleşme bölünme aşamalarında olduğu gibi devam eder; tabi küçük olan değer başa geçerek.

`[8, 11, 12, 16, 21, 22]` ### Nihayetinde tüm dizinler birleşmiş ve değerler kendi içerisinde küçükten büyüğe sıralanmış olur.

B-) Big-O gösterimi

Bölünme ve tekrar birleşmede toplam 6 işlem (aşama) olduğundan; O(n*(logn)) --> `O(6*(log6))` olur.

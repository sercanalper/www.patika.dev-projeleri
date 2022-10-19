[Patika.dev](https://www.patika.dev/tr)

https://app.patika.dev/sercanalper


[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Binary Search Tree'si

Önce Root'umuzu belirlemeliyiz. Sonraki değerler Root'tan büyük ve küçük olmalarına göre sırasıyla sağa veya sola konumlandırılmalılar.

Root = 7 için;

5 sayısı 7'den küçük olduğundan 7'nin soluna gider.

```
   7
5
```

1 sayısı hem 5'ten hem 7'den küçük olduğu için ikisinin de soluna gider.

```
      7
   5
1
```

8 sayısı 7'den büyük olduğu için sağına eklenir.

```
      7
   5    8
1
```

3 sayısı 7'den ve 5'ten küçük olduğu için 5'in soluna; 1'den büyük olduğu için 1'in sağına eklenir.

```
         7
      5    8
1
   3
```

6 sayısı 7'den küçük olduğundan soluna, 5'ten büyük olduğundan 5'in sağına ekledik.

```
           7
      5     8
1       6
   3
```


0 sayısı 7, 5 ve 1'den küçük olduğu için bunların soluna eklenir.

```
              7
         5      8
    1       6
0     3
```

9 sayısı 7'den ve 8'den büyük olduğu için 8'in sağına gider.

```
              7
         5      8
    1       6     9
0     3
```

4 sayısı 7'den ve 5'ten küçük olduğu için 5'in soluna; 1'den ve 3'ten büyük olduğu için 3'ün sağına gider.

```
              7
         5      8
    1       6     9
0     3
          4
```

2 sayısı 7'den ve 5'ten küçük olduğu için 5'in soluna; 1'den büyük olduğu için 1'in sağına; 3'ten küçük olduğu için de 3'ün soluna eklendi.

```
               7
          5      8
     1       6     9
 0     3
    2     4
```

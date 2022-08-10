# Insertion Projesi

## [22,27,16,2,18,6]

1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.


```
1.Aşama:[2,27,16,22,18,6]
2.Aşama:[2,6,16,22,18,27]
3.Aşama:[2,6,16,18,22,27]
```
2.Big-O gösterimini yapınız.
```
Yapılacak işlemler n+(n-1)+(n-2).....+1 olarak gideceği için (n*(n+1))/2 toplam formülünden Big-O Notation bazında sonuç 
(n2 + n)/2 'den O(n2) olur.

```

3.Time Complexity; -Average Case: Aradığımız sayının ortada olması, -Worst Case: Aradığımız sayının sonda olması, -Best Case: Aradığımız sayının dizinin en başında olması. Doğrudan dizimize baktığımızda
```
18 sayısı 4.sırada ve Average Case kapsamına girer.
```

4.**[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

```
Adım 1:[2,3,5,8,7,9,4,15,6]
Adım 2:[2,3,4,8,7,9,5,15,6]
Adım 3:[2,3,4,5,7,9,8,15,6]
Adım 4:[2,3,4,5,6,9,8,15,7]
```




# Proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
***
Bu yöntemde sıralanacak dizinin ikinci
elemanından başlanarak mevcut eleman uygun konumuna
(araya ekleme) getirilerek sıralama yapılmaktadır.
``` 
[22,27,16,2,18,6]
[22,27,16,2,18,6]
[16,22,27,2,18,6]
[2,16,22,27,18,6]
[2,16,18,22,27,6]
[2,6,16,18,22,27]
```
Yukarıdaki adımlar sırası ile uygulandığında dizi verilen sorta göre sıralanmış olur.
***
Big-O gösterimini yazınız.
``` 
Big-O = n ^ 2
```
***
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
``` 
18 sayısı, dizi sıralandığında dizinin tam ortasındadır. Bu yüzden Average Case kapsamındadır.
```
***
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
``` 
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
```
Bu dört adımdan sonra üç adım daha aynı işlemler uygulanarak dizi sıralanmış olur.

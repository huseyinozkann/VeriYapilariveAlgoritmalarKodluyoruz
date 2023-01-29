# Proje 2

[16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
***
Bu sıralama yönteminde böl ve yönet yaklaşımına
dayanır. Sıralanması istenen dizi elemanları önce 2 alt diziye
ayrılır. Alt kümelere ayırma işlemine alt kümelerdeki bir tane
eleman kalana kadar devam edilir. Alt kümelerde 1 tane eleman
kalmışsa rekürsif çağırma geriye doğru dönmeye başlar ve geri
dönülürken alt kümeler elemanları sıralı olacak şekilde
birleştirilir.
***
Bir tane eleman kalıncaya kadar ayırma işlemi yapıyoruz.
```
[16,21,11,8,12,22]
[16,21,11]    [8,12,22]
[16,21]   [11]   [8,12]   [22]
[16]   [21]   [11]   [8]   [12]   [22]
```
***
Şimdi tüm alt kümelerde 1 eleman kaldığı için dizi geriye doğru sıralı bir şekilde dönmeye başlar.
```
[16]   [21]   [11]   [8]   [12]   [22]
[16,21]   [11]   [8,12]   [22]
[11,16,21]   [8,12,22]
[8,11,12,16,21,22]
```
Böylece dizi sıralanmış olur.
***
Big-O gösterimini yazınız.
```
Big-O = nlogn
```

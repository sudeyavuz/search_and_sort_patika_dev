# Search_and_Sort_Patika_Dev
Patika Dev ile Selection Sort, Merge Sort ve Binary Search Tree projesi.
## Selection Sort
[22,27,16,2,18,6]
### Dizinin Sort türüne göre aşamaları:
```
1)[22,27,16,2,18,6]
2)[2,27,16,22,18,6]
3)[2,6,16,22,18,27]
4)[2,6,16,18,22,27]
```
### Big-O gösterimi:
```
n+(n-1)...+1
n*(n+1)/2
(n^2+n)/2 bu sort'un Big-O o(n) gösrerimi O(n^2) şeklindedir.
```
### Zaman Karmaşıklığı:
```
[2,6,16,18,22,27] sıralı dizisinde 18 ortada bulunduğu için Average Case olarak adlandırılır.
```
### Örnek dizinin ilk dört adımı:
```
1)[7,3,5,8,2,9,4,15,6]
2)[2,3,4,8,7,9,5,15,6]
3)[2,3,4,5,7,9,8,15,6]
4)[2,3,4,5,6,9,8,15,7]
```
## Merge Sort 
[16,21,11,8,12,22]
### Dizinin sort türüne göre aşamaları:
```
[16,21,11] ve [8,12,22] 
[16,21] ve [11] ; [8,12] ve [22]
İkili dizilerideki küçükten büyüğe sıralama doğru olduğu için herhangi bir değişiklik yapmıyoruz.
Dizileri geri birleştiriyoruz.
[11,16,21] ve [8,12,22]
  [8,11,12,16,21,22]
  ```
  ### Big-O gösterimi:
  ```
  n*log(n)
  ```
## Binary Search Tree
  [7,5,1,8,3,6,0,9,4,2]
  ### Dizinin search türüne göre ağacı:
  ```
  root=7
                   7
                /     \
               5        8 
              /  \        \
             1    6        9
           /  \
          0    3
             /   \
            2     4
```

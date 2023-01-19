# **Proje 1**
## **1.Soru**
`[22,27,16,2,18,6]` -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- Big-O gösterimini yazınız.

- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

 1. Average case: Aradığımız sayının ortada olması
 2. Worst case: Aradığımız sayının sonda olması
 3. Best case: Aradığımız sayının dizinin en başında olması.


## **2.Soru**
- `[7,3,5,8,2,9,4,15,6]` dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

-------
## **1.Soru Cevabı**
`Insertion Sort`: Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. Sonraki sayıları da bu şekilde sıralıyor.

Buna göre aşamaları:
1. `[22,27,16,2,18,6]` -> `[2,27,16,22,18,6]` En küçük eleman bulundu ve yer değiştirildi.
2. `[2,27,16,22,18,6]` -> `[2,6,16,22,18,27]` 2.En küçük eleman bulundu ve yer değiştirildi.
3. `[2,6,16,22,18,27]` -> `[2,6,16,22,18,27]` 3. En küçük eleman sırası aynı olduğu için bir işlem yapılmadı
4. `[2,6,16,22,18,27]` -> `[2,6,16,18,22,27]`  4. En küçük eleman sırası aynı olduğu için bir işlem yapılmadı
5. `[2,6,16,18,22,27]` -> `[2,6,16,18,22,27]`  5. En küçük eleman sırası aynı olduğu için bir işlem yapılmadı
6. `[2,6,16,18,22,27]` -> `[2,6,16,18,22,27]` 6. En küçük eleman sırası aynı olduğu için bir işlem yapılmadı

- Big O Gösterimi =  `O(n^2)`
- Time Complexity = `Average case`: Aradığımız sayının ortada olması

## **2.Soru Cevabı**

 1. Adım `[2, 3, 5, 8, 7, 9, 4, 15, 6] `
 2. Adım `[2, 3, 4, 8, 7, 9, 5, 15, 6] `
 3. Adım `[2, 3, 4, 5, 7, 9, 8, 15, 6] `
 4. Adım `[2, 3, 4, 5, 6, 9, 8, 15, 7] `
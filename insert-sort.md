# Insert_Sort_Projesi
[Patika.dev](https://www.patika.dev/tr)

## [22,27,16,2,18,6] -> Insertion Sort

## 1) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
      1.Aşama: [22,27,16,2,18,6] Başlangıç  n
      2.Aşama: [2,27,16,22,18,6] (Listenin en küçük elemanı(2) bulundu ve listedeki ilk eleman(22) ile yerleri değiştirildi.)  n-1
      3.Aşama: [2,6,16,22,18,27] (27 ile 6 yer değiştirdi.)  n-2
      4.Aşama: [2,6,16,18,22,27] (18 ile 22 yer değiştirdi.)  1

## 2) Big-O gösterimini yazınız.
      (n.(n+1))/2
      (n^2+n)/2
      Big-O gösterimi ----> 0(n^2)

## 3)Time Complexity: 
     Average case: Aradığımız sayının (2) ortada olması ---> [22,27,16,2,18,6]
     Worst case: Aradığımız sayının (2) sonda olması ---> [22,27,16,6,18,2]
     Best case: Aradığımız sayının (2) dizinin en başında olması ---> [2,27,16,22,18,6]

## 4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
      Average case.

## 5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
      1.Adım: [2,3,5,8,7,9,4,15,6] (2 ile 7 yer değiştirir.)
      2.Adım: [2,3,5,8,7,9,4,15,6] (Hiçbir sayı yer değiştirmez.)
      3.Adım: [2,3,4,8,7,9,5,15,6] (4 ile 5 yer değiştirir.)
      4.Adım: [2,3,4,5,8,7,9,8,15,6] (8 ile 5 yer değiştirir.)
  

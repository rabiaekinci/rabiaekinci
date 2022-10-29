# Binary Search Tree Projesi
[Patika.dev](https://www.patika.dev/tr)

## [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

## 1.Aşama: Root=7 seçilir.
                  7
## 2.Aşama: 5, 7'den küçük olduğu için 7'nin soluna eklenir. 
                  7
                 /
                5
## 3.Aşama: 1, 5 ve 7'den küçük olduğu için 5'in soluna eklenir.
                  7
                 /
                5
               /
              1
## 4.Aşama: 8, 7'den büyük olduğu için 7'nin sağına eklenir.
                  7
                 / \	
                5   8
               /
              1
## 5.Aşama: 3, 7 ve 5'ten küçük olduğu için 5'in soluna, 1'den büyük olduğu için 1'in sağına eklenir.
                  7
                 / \	
                5   8
               /
              1
               \	
                3
## 6.Aşama: 6,7'den küçük olduğu için 7'nin soluna, 5'ten büyük olduğu için 5'in sağına eklenir.
                  7
                 / \	
                5   8
               / \	
              1   6
               \	
                3
## 7.Aşama: 0, 7,5 ve 1'den küçük olduğu için 1'in soluna eklenir.
                  7
                 / \	
                5   8
               / \	
              1   6
             / \	
            0   3
## 8.Aşama: 9, 7 ve 8'den büyük olduğu için 8'in sağına eklenir.
                  7
                 / \	
                5   8
               / \	 \	
              1   6   9
             / \	
            0   3
## 9.Aşama: 4, 7 ve 5'ten küçük olduğu için 5'in soluna, 1'den ve 3'ten büyük olduğu için 3'ün sağına eklenir. 
                  7
                 / \	
                5   8
               / \	 \	
              1   6   9
             / \	
            0   3
                 \	
                  4
## 10.Aşama: 2, 7 ve 5'ten küçük olduğu için 5'in soluna, 1'den büyük olduğu için 1'in sağına ve 3'ten küçük olduğu için 3'ün soluna eklenir.
                  7
                 / \	
                5   8
               / \	 \	
              1   6   9
             / \	
            0   3
               / \	
              2   4

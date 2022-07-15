# binary_search_tree
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları:

-Root 7'dir. Root'un sağına 7'den büyük olan 8 ve 9 gelmelidir.
9 8'den büyük olduğu için 8'in sağına yazılmalıdır.
-Root'un soluna önce 5 yazarız. 5'in soluna 1, sağına 6 gelmelidir. 
Çünkü 6 5'ten büyük, 7'den küçüktür.
-1'in soluna küçük olan 0'ı, sağına 1'den büyük olan 3'ü yazarız.
-3'ün soluna küçük olan 2'yi, sağına 3'den büyük olan 4'ü yazarız.
-Gösterimi aşağıdaki gibidir:
           7
         /   \
        5     8
       / \     \
      1   6     9  
     /  \
    0    3
        /  \
        2   4

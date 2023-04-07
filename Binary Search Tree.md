Aşağıdaki şekilde [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin binary search tree aşamaları gösterilmiştir:

             7
           /   \
          5     8
         / \     \
        1   6     9
       / \       /
      0   3     9
         / \
        2   4



1. İlk olarak 7, kök düğüm (root) olarak seçildi
2. 5, 7'nin soluna yerleştirildi çünkü 5 < 7
3. 1, 5'in soluna yerleştirildi çünkü 1 < 5
4. 8, 7'nin sağına yerleştirildi çünkü 8 > 7
5. 3, 5'in sağına yerleştirildi çünkü 3 < 5
6. 6, 5'in sağına yerleştirildi çünkü 6 > 5
7. 0, 1'in soluna yerleştirildi çünkü 0 < 1
8. 9, 8'in sağına yerleştirildi çünkü 9 > 8
9. 2, 3'ün soluna yerleştirildi çünkü 2 < 3
10. 4, 3'ün sağına yerleştirildi çünkü 4 > 3

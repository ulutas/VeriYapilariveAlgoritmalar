## Insertion Sort:

[22, 27, 16, 2, 18, 6]

[22, 27, 16, 2, 18, 6] -> 22 sıralı
[16, 22, 27, 2, 18, 6] -> 16 doğru pozisyona yerleştirildi
[2, 16, 22, 27, 18, 6] -> 2 doğru pozisyona yerleştirildi
[2, 16, 18, 22, 27, 6] -> 18 doğru pozisyona yerleştirildi
[2, 6, 16, 18, 22, 27] -> 6 doğru pozisyona yerleştirildi

Big-O gösterimi: O(n^2)

Dizi sıralandıktan sonra 18 sayısı "Average Case" kapsamına girer.

[7, 3, 5, 8, 2, 9, 4, 15, 6]

[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6]
[2, 3, 4, 5, 6, 9, 8, 15, 7]
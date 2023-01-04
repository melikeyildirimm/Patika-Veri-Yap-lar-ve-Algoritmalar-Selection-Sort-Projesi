# Patika-Veri-Yap-lar-ve-Algoritmalar-Selection-Sort-Projesi

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamaları:
En küçük eleman (2) en baştaki sayı (22) ile yer değiştirir.
-[2,27,16,22,18,6]
İkinci en küçük eleman (6) ile ikinci sıradaki sayı (27) yer değiştirir.
-[2,6,16,22,18,27]
Üçüncü en küçük eleman (16) zaten üçüncü sırada olduğu için yer değiştirme olmaz.
Dördüncü en küçük eleman (18) ile dördüncü sıradaki sayı (22) yer değiştirir.
-[2,6,16,18,22,27]
Beşinci en küçük eleman (22) zaten beşinci sırada, altıncı en küçük eleman (27) de zaten altıncı sırada olduğu için başka yer değiştirme olmaz.
Yani son hali:
-[2,6,16,18,22,27] olur.

Big-O gösterimi: O(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı en ortada olduğu için 18 sayısı Avarage Case'e girer.


[2, 6, 16, 18, 22, 27]

Insertion sort algoritmasının çalışma mantığına göre sıralama işlemi adım adım gerçekleştirilir:

1. [22, 27, 16, 2, 18, 6] -> ilk eleman sabit kabul edilir.
2. [22, 27, 16, 2, 18, 6] -> 2. eleman (27) birinci elemandan (22) büyük olduğu için yer değiştirilmez.
3. [16, 22, 27, 2, 18, 6] -> 3. eleman (16) 2. elemandan (27) küçük olduğu için 2. ve 3. elemanların yerleri değiştirilir.
4. [2, 16, 22, 27, 18, 6] -> 4. eleman (2) 3. elemandan (22) küçük olduğu için 2. ve 3. elemanlar tekrar yer değiştirir, ardından 1. ve 2. elemanlar da yer değiştirir.
5. [2, 16, 18, 22, 27, 6] -> 5. eleman (18) 4. elemandan (27) küçük olduğu için 4. ve 5. elemanların yerleri değiştirilir.
6. [2, 6, 16, 18, 22, 27] -> Son eleman (6) önceki elemanlardan küçük olduğu için önceki elemanlarla sırayla karşılaştırılır, en uygun yere yerleştirilir.

Big-O gösterimi: O(n^2)

18 sayısı dizi sıralandıktan sonra 5. sırada yer almaktadır, yani average case kapsamına girer.

[7, 3, 5, 8, 2, 9, 4, 15, 6]

Selection sort algoritmasının çalışma mantığına göre sıralama işlemi adım adım gerçekleştirilir:

1. [2, 3, 5, 8, 7, 9, 4, 15, 6] -> En küçük eleman (2) dizinin başına taşınır.
2. [2, 3, 4, 8, 7, 9, 5, 15, 6] -> En küçük eleman (3) dizinin ikinci sırasına taşınır.
3. [2, 3, 4, 5, 7, 9, 8, 15, 6] -> En küçük eleman (5) dizinin üçüncü sırasına taşınır.
4. [2, 3, 4, 5, 6, 9, 8, 15, 7] -> En küçük eleman (6) dizinin dördüncü sırasına taşınır.

İlk 4 adım sonucunda dizinin durumu şu şekildedir:


1. [2, 3, 4, 5, 6, 9, 8, 15, 7] -> En küçük eleman (7) dizinin beşinci sırasına taşınır.
2. [2, 3, 4, 5, 6, 7, 8, 15, 9] -> En küçük eleman (8) dizinin altıncı sırasına taşınır.
3. [2, 3, 4, 5, 6, 7, 8, 15, 9] -> En küçük eleman (9) dizinin yedinci sırasına taşınır.
4. [2, 3, 4, 5, 6, 7, 8, 9, 15] -> En küçük eleman (15) dizinin sekizinci sırasına taşınır.

Dizi son hali itibariyle [2, 3, 4, 5, 6, 7, 8, 9, 15] olarak sıralanmıştır.

Not: Selection Sort ve Insertion Sort gibi quadratic time complexity'e sahip sıralama algoritmaları büyük boyutlu verilerde kullanılmaması önerilir. Bunun yerine merge sort veya quick sort gibi daha hızlı sıralama algoritmaları tercih edilebilir.




İlk önce, verilen diziyi sıralamamız gerekiyor. Sıralanmış bir dizi, Binary Search Tree'ye dönüştürüldüğünde, ağaç dengeli hale getirilirse en iyi sonucu verecektir. 

Dizi sıralandıktan sonra, ağaç oluşturulabilir:
 
1. İlk eleman olan 7, root olarak atanır.
2. Root'un sağında 8 ve solunda 1 bulunur. 1, root'un sol çocuğu olarak atanır ve 8, root'un sağ çocuğu olarak atanır.
3. 1'in sağında 5 ve solunda 0 bulunur. 0, 1'in sol çocuğu olarak atanır ve 5, 1'in sağ çocuğu olarak atanır.
4. 8'in sağında 9 ve solunda 3 bulunur. 3, 8'in sol çocuğu olarak atanır ve 9, 8'in sağ çocuğu olarak atanır.
5. 3'ün sağında 6 ve solunda 2 bulunur. 2, 3'ün sol çocuğu olarak atanır ve 6, 3'ün sağ çocuğu olarak atanır.
6. 9'un solunda 4 bulunur. 4, 9'un sol çocuğu olarak atanır.

Bu şekilde Binary Search Tree aşamaları aşağıdaki gibidir:

- Root: 7
- Root'un solunda 1, sağında 8 var.
- 1'in solunda 0, sağında 5 var.
- 8'in solunda 3, sağında 9 var.
- 3'ün solunda 2, sağında 6 var.
- 9'un solunda 4 var.

[16,21,11,8,12,22] -> Merge Sort
Görev 1: Yukarýdaki dizinin sort türüne göre aþamalarýný yazýnýz.
1) 16,21,11 ve 8,12,22 olarak ikiye ayrýlýr.
2) 16,21,11 => 16 ve 21,11 olarak, 8,12,22 => 8 ve 12,22 olarak 2'ye ayrýlýr.
3) Ardýndan 21,11 11,21 olarak ve 12,22 12,22 olarak aralarýnda sýralanýr.
4)  Ardýndan 16 11,21 ile birleþir ve aralarýnda 11,16,21 olarak sýralanýr.
5) 8 ise 12,22 ile birleþir ve aralarýnda 8,12,22 olarak sýralanýr.
6) Son olarak 11,16,21 ve 8,12,22 birleþir ve 8,11,12,16,21,22 olarak aralarýnda sýralanýr.
Görev 2: Big-O gösterimini yazýnýz.
O(n*logn)
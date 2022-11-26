[16,21,11,8,12,22] -> Merge Sort
Görev 1: Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
1) 16,21,11 ve 8,12,22 olarak ikiye ayrılır.
2) 16,21,11 => 16 ve 21,11 olarak, 8,12,22 => 8 ve 12,22 olarak 2'ye ayrılır.
3) Ardından 21,11 11,21 olarak ve 12,22 12,22 olarak aralarında sıralanır.
4)  Ardından 16 11,21 ile birleşir ve aralarında 11,16,21 olarak sıralanır.
5) 8 ise 12,22 ile birleşir ve aralarında 8,12,22 olarak sıralanır.
6) Son olarak 11,16,21 ve 8,12,22 birleşir ve 8,11,12,16,21,22 olarak aralarında sıralanır.

Görev 2: Big-O gösterimini yazınız.
O(n*logn)

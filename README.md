# Proje2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Tüm dizi tek elemanlı olacak şekilde 2'ye ayrılır.

- [16,21,11] [8,12,22]
- [16,21] [11] [8,12] [22]
- [16] [21] [11] [8] [12] [22]

İki adet dizi birleştirilir. Birleştirilirken sıralanır.

- [16,21] [8,11] [12,22]

Tekrar birleştirilir ve sıralanır.

- [8,11,16,21] [12,22]
- [8,11,12,16,21,22]

ve sıralanmış olur.

Big-O gösterimi ise **O(nlogn)** olarak gösterilir.
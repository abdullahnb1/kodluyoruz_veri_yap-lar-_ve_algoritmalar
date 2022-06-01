## Merge Task

[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    >                 [16,21,11] ---- [8,12,22]
    >           [16,21] --- [11] ---- [8] --- [12,22]
    >       [16] -- [21] -- [11] ---- [8] -- [12] -- [22]
    >                 [11,16,21] ---- [8,12,22]
    >                     [8,11,12,16,21,22]
- Big-O gösterimini yazınız.
    > Kendini sürekli çağırarak diziyi hep ikiye bölmektedir. Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından big-O(n*(logn))

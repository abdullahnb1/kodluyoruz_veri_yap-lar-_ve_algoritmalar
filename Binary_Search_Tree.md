## Binary Search Tree Task

- [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

- Binary search tree algoritmasındaki temel mantık alınan değer eğerki root değerinden düşük ise sola büyük ise sağa gönderilir. Daha sonra o sayı gittiği kolda tekrar aynı işlemlerden geçer.

    > Root = 7
    
    >ilk sayı 5. Rootun değerinden düşük olduğu için sola yazılır.    
    
    >                                                                   7
    >                                                                 /  
    >                                                                5                                         
    
    > Bu işlemleri sırası ile devam ettirirsek ağacımız şu aşağıdaki gibi olacaktır.

    >                                                                   7
    >                                                                 /   \
    >                                                                5     8
    >                                                              /   \     \
    >                                                             1     6     9
    >                                                           /   \
    >                                                          0     3
    >                                                              /   \
    >                                                             2     4

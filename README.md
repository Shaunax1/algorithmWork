# algorithmWork
Insertion Sort-Merge Sort-Binary Search Tree

1- Insertion Sort

[22,27,16,2,18,6]

a- Yukarıdaki dizinin sort aşamaları

1-[2,22,27,16,18,6]
2-[2,6,22,27,16,18]
3-[2,6,16,22,27,18]
4-[2,6,16,18,22,27]

b- Big o gösterimi => O(n^2)

c- Avarage Case kapsamına girer çünkü 18 sayısı ortada kalıyor.

d- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

    [2, | 3, 5, 8, 7, 9, 4, 15, 6]
    [2, 3, | 5, 8, 7, 9, 4, 15, 6]
    [2, 3, 4, | 8, 7, 9, 5, 15, 6]
    [2, 3, 4, 5, | 7, 9, 8, 15, 6]
    ---
    [2, 3, 4, 5, 6, | 9, 8, 15, 7]
    [2, 3, 4, 5, 6, 7, | 8, 15, 9]
    [2, 3, 4, 5, 6, 7, 8, | 15, 9]
    [2, 3, 4, 5, 6, 7, 8, 9, | 15]

2- Merge Sort

[16,21,11,8,12,22] 

Q- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

a- [16,21,11] - [8,12,22]
    [16] [21,11] - [8] [12,22]
    [16] [21] [11] - [8] [12] [22]
    [16] [11,21] - [8] [12,22]
    [11,16,21] - [8,12,22]
    [8,11,12,16,21,22]

Q- Big-O gösterimini yazınız.

b- Big o gösterimi => O(nlogn)

3- Binary Search Tree

Q-[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Root => 7
                           7
                5                       8  
        1             6                        9
    0       3    
          2    4


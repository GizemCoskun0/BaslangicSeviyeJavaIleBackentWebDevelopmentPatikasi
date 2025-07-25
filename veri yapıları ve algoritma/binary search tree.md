## Binary Search Tree
### Verilen Dizi: [7,5,1,8,3,6,0,9,4,2]
Root 7

5<7 -> 7'nin solunda 5 yazılır

1<7, 1<5 -> 5'in soluna 1 yazılır

8>7 -> 7'nin sağına yazılır

3<7, 3<5, 3>1 -> 1'in sağına 3 yazılır

6<7, 6>5 -> 5'in sağına 6 yazılır

0<7, 0<5, 0<1 -> 1'in soluna 0 yazılır

9>7, 9>8 -> 8'in sağına 9 yazılır

4<7, 4<5, 4>1, 4>3 -> 3'ün sağına 4 yazılır

2<7, 2<5, 2>1, 2<3 -> 3'ün soluna 2 yazılır


                7
              /   \
             5     8
            / \     \
           1   6     9
          / \
         0   3
            / \
           2   4

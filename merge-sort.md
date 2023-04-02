# Merge Sort Projesi
## Problem
<br>

[16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- Big-O gösterimini yazınız.
<br><br><br>

Merge sort bir listeyi her adımda parçaya ayırıp tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde bize sunuyor.

## Çözüm
1. Sıralama işlemi
    
        ---[16,21,11,8,12,22]---

        1.  [16,21,11]    [8,12,22]
        2. [16] [11,21]  [8] [12,22]
        3.  [11,16,21]    [8,12,22]
        4.    [8,11,12,16,21,22]  

2. Big-O gösterimi

         O(n*logn)






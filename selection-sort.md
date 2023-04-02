# Selection Sort Projesi
## Problem
<br>
[22,27,16,2,18,6] -> Selection Sort
<br><br>

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

- Big-O gösterimini yazınız.

- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
<br><br>

Average case: Aradığımız sayının ortada olması

Worst case: Aradığımız sayının sonda olması

Best case: Aradığımız sayının dizinin en başında olması.

<br><br><br>

## Çözüm

**1) İlk olarak [22,27,16,2,18,6] dizisini Selection sort a göre sıralayalım.**

Selection sort'a göre sıralama işlemi: Dizinin küçükten büyüğe doğru sıralanmasıdır. Dizideki en küçük eleman bulur ve ilk sıraya yerleştirir. Devamında ise ikinci küçük elemanı bulur ve ikinci sıraya yerleştirir, bu şekilde diziyi sıralar.

    ---[22,27,16,2,18,6]---

    1. [2,27,16,22,18,6]
    2. [2,6,16,22,18,27]
    3. [2,6,16,18,22,27]

<br><br>

**2)Big-O gösterimini yazınız.**

    Big O notation --> O(n^2^)
<br><br>

**3) Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.**

    Avarage Case

<br><br>

**4) [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.**

    ---[7,3,5,8,2,9,4,15,6]---

    1. [2,3,5,8,7,9,4,15,6]
    2. [2,3,4,8,7,9,5,15,6]
    3. [2,3,4,5,7,9,8,15,6]
    4. [2,3,4,5,6,9,8,15,7]
    5. [2,3,4,5,6,7,8,15,9]
    6. [2,3,4,5,6,7,8,9,15]
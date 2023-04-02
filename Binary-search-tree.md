# Binary Search Tree Projesi
## Problem
<br>

[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.
<br><br><br>

## Çözüm
  [7,5,1,8,3,6,0,9,4,2]

1. İlk olarak dizimizin root kökünü belirlememiz lazım, root kök olarak 3'ü seçiyorum.
2. Dizimizdeki ilk rakamdan başlayarak root rakamımızdan büyük olan sayıları soluna küçük olanları sağına ekliyoruz.
3. Her rakam için öncelikle root sayımızdan büyük mü karşılaştırıyoruz, büyükse sağa küçükse sola ekliyoruz.
4. Root rakamından sonra gelen rakamı sayımız ile aynı şekilde karşılaştırıp büyükse sağa küçükse soluna ekliyoruz.

                3
            /        \
           1          7
          /  \       /  \
         0    2     5    8
                   /  \     \
                  4    6      9             
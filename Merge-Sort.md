# Merge Sort Odevi
[Patika Hesabım](https://app.patika.dev/yavuzeroglu)
------

## 1. Soru: 
[16,21,11,8,12,22] **Merge Sort** aşamaları;

                    [16,21,11,8,12,22]

           [16,21,11]                               [8,12,22]

        [16]    [21,11]                         [8,12]      [22]

        [16]   [21]  [11]                      [8] [12]     [22]

                Buraya kadar bölme işlemi yapıldı.
                Bundan sonra ise ikili sonrasında üçlü
                olacak şekilde sıralayıp en son da 
                sıralı dizimizi elde ediyoruz.

        [16]    [11,21]                         [8,12]      [22]

          [11,16,21]                               [8,12,22]

                         [8,11,12,16,21,22]


-----
## 2. Soru 

**Big-O** gösterimi; 
 
 -O(n(logn)) --> O(6(log6)) 
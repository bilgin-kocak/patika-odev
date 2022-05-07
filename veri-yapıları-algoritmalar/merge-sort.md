# Merge Sort

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

                [16,21,11,8,12,22]
                        |
                        |
            [16,21,11]    [8,12,22]
                        |
                        |
      [16]      [21,11]    [8]  [12,22]
       |           |        |      |
      [16]    [21]  [11]   [8]  [12]  [22]
             |                  |
       [11,16,21]            [8,12,22]
            |                   |
                       |
                       |
              [8,11,12,16,21,22]

Big- O Gösterimi: Recursive fonksiyon türünde olduğunda kendini çağırarak diziyi ikiye bölmektedir.
Her bölünmüş dizinin Merge Sort'unda dizinin uzunluğu olan n işlem yapıldığından O(n*(logn)) --> O(6*(log6)) olacaktır.

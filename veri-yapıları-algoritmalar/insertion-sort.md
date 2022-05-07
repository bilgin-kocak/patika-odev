# Insertion Sort

[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2.Big-O gösterimini yazınız.
3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

CEVAPLAR

1.  1-[22,27,16,2,18,6]
    2-[2,27,16,22,18,6]
    3-[2,6,16,22,18,27]
    4-[2,6,16,18,22,27]
    5-[2,6,16,18,22,27]
    6-[2,6,16,18,22,27]

2.  Big-O Notation Gösterimi: Sırasıyla n, (n-1), (n-2).....,1 şeklinde devam eder. Bu sebeple 1'den n'e kadar sayıların toplamı n\*(n+1)/2 işleminin sonucu verir.
    Yani O(n^2)dir.

3.  Time Complexity:
4.  Average Case: Aradığımız sayının ortada olması : O(n^2)dir.
5.  Worst Case: Aradığımız sayının sonda olması: O(n^2)dir.
6.  Best Case: Aradığımız sayının en başında olması: O(n)dir.

7.  18 sayısı ortalama değere en yakın sayılardan biri olduğu için Average Case'e girer.

8.  [7,3,5,8,2,9,4,15,6] Insertion Sort'a göre ilk 4 adımı:

1-[3,7,5,8,2,9,4,15,4]
2-[3,5,7,8,2,9,4,15,4]
3-[3,5,7,8,2,9,4,15,4]
4-[2,3,5,7,8,9,4,15,6]

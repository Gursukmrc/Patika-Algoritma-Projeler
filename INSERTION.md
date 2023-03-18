Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

CEVAP:
{22,27,16,2,18,6}
{16,22,27,2,18,6}
{2,16,22,27,18,6}
{2,16,18,22,27,6}
{2,6,16,18,22,27}
Big O = O(n^2)



Soru: Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

CEVAP: 18, average case dir.

SORU: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

{7,3,5,8,2,9,4,15,6} O(n) 
{2,3,5,8,7,9,4,15,6} O(n-1) 1. islem
{2,3,4,8,7,9,5,15,6} O(n-2) 2. islem
{2,3,4,5,7,9,8,15,6} O(n-3) 3, islem
{2,3,4,5,6,9,8,15,7} O(n-4) 4. islem
{2,3,4,5,6,7,8,15,9} O(n-5) 5. islem
{2,3,4,5,6,7,8,9,15}    1   6.islem
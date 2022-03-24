## ***Proje 1 Insertion Sort Projesi***
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
1. Big-O gösterimini yazınız.
2. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
3. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

---

## ***Çözüm:***
1. Big-O = O(n^2)
2. Worst case : bu durumda dizinin her bir elemanı bir gerisindekinden küçük olacaktır. Dolayısıyla 1inci eleman için iç döngü 0 2 eleman için geriye doğru 1, 3. eleman için iki daha sonra 3 4 5 6… n kadar geriye hareket yapacaktır. Yani 0+1+2+3+4…..+n-1 = [n*(n-1)]/2   :  O(n^2). **Best case** : n tane sayinin üzerinden birer defa geçer ve hiç birini geriye doğru ilerletme gereği olmadığı için bu tek geçişle kalır. Yani O(n). **Avarage case** : Worst case ile best casein ortalamasını aldığımızda   O(n^2) olarak buluruz.
3.  Dizi sıralandıktan sonra 18 sayısı Avarage case kapsamına girer.


[7,3,5,8,***2***,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adım

[7,3,5,***2***,8,9,4,15,6]
[7,3,***2***,5,8,9,4,15,6]
[7,***2***,3,5,8,9,4,15,6]
[***2***,7,3,5,8,9,4,15,6]


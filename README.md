[22,27,16,2,18,6] -> Insertion Sort

1 - ) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2 - ) Big-O gösterimini yazınız.

        Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The      number we are looking for is at the beginning of the series.
3 - ) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4 -) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1 - Cevabı:
Main List: [22,27,16,2,18,6]
- Adım 1 -> En küçük sayı 2 (tüm listede).  2 ile 22 yer değiştirir.
        New list : [2,(27,16,22,18,6)]
        ---> (...) is locked.
- Adım 2 -> 6 en küçük sayı.  Yani, 6 ile 27 yer değiştirir.
        New list : [2,6,(16,22,18,27)] 
- Adım 3 ->  16 bir sonraki en küçük sayı. Yani, 16 is already where it should be.
        New list : [2,6,16,(22,18,27)]
- Adım 4 -> Bir sonraki küçük sayı 18. Yani, 18 ile 22 yer değiştirir.
        New list : [2,6,16,18,(22,27)]
- Adım 5 -> Bir sonraki en küçük sayı 22. Yani, 22 zaten durması gereken yerde.
        New list : [2,6,16,18,22,27]
- ~ Bitiş ~
- 
2 - Cevabı:
Total Process -> n + (n-1) + (n-2) + ... + 1 = n(n+1)/2 = (n^2+n)/2
        O((n^2+n)/2) ~ O(n^2)
        
3 - Cevabı:
Dizi sıralandıktan sonra 18 sayısı dizinin ortasında olduğu için; "Ortalama(Average) Durum" kapsamına girer.

4 -Cevabı:
        [7,3,5,8,2,9,4,15.6] (Quicksilver mod aktif)
- Steps - Result 1 - [2,(3,5,8,7,9,4,15.6)] 2 - [2,3,(5,8,7,9,4,15.6)] 3 - [2,3,4,(8,7,9,5,15.6)] 4 - [2,3,4,5,(7,9,8,15.6)] 5 - [2,3,4,5,7,(9,8,15.6)] 6 - [2,3,4,5,7,8,(9,15.6)]

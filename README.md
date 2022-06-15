[22,27,16,2,18,6] -> Insertion Sort
1 - ) Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2 - ) Big-O gösterimini yazınız.

        Time Complexity: Average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The      number we are looking for is at the beginning of the series.
3 - ) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4 -) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1 - Answer:
Main List: [22,27,16,2,18,6]
Step 1 -> Smallest number (in the entire list) is 2. So, change 2 to 22 places.
        New list : [2,(27,16,22,18,6)]
        ---> (...) is locked.
Step 2 -> Smallest number is 6. So, change 6 to 27 places.
        New list : [2,6,(16,22,18,27)] 
Step 3 -> Smallest number is 16. So, 16 is already where it should be.
        New list : [2,6,16,(22,18,27)]
Step 4 -> Smallest number is 18. So, change 18 to 22 places.
        New list : [2,6,16,18,(22,27)]
Step 5 -> Smallest number is 22. So, 22 is already where it should be.
        New list : [2,6,16,18,22,27]
~ Finito ~
2 - Answer:
Total Process -> n + (n-1) + (n-2) + ... + 1 = n(n+1)/2 = (n^2+n)/2
        O((n^2+n)/2) ~ O(n^2)
3 - Answer:
After the array is sorted, since the number 18 is in the middle of the array; It falls under the "Average Case".

4 - Answer:
        [7,3,5,8,2,9,4,15.6] (Quicksilver mode active!)
Steps - Result 1 - [2,(3,5,8,7,9,4,15.6)] 2 - [2,3,(5,8,7,9,4,15.6)] 3 - [2,3,4,(8,7,9,5,15.6)] 4 - [2,3,4,5,(7,9,8,15.6)] 5 - [2,3,4,5,7,(9,8,15.6)] 6 - [2,3,4,5,7,8,(9,15.6)]

#INSERTIONSORT
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

###insertion sort; verilen dizideki en küçük elemanı bularak başa yazdıktan sonra dizideki elemanların yerini değiştirerek küçükten büyüğe sıralama yapmamızı istemektedir. ve her eleman sadece yer değiştirip kendinden daha küçük bir elaman gelen dek yer tutmaktadır.

[22,27,16,2,18,6] n

[2,27,16,22,18,6] n-1

[2,6,16,22,18,27] n-2

[2,6,16,18,22,27] 1

###Big-0 gösterimi     yaptığımız işlem sayısı ve zaman ölçümüne yarıyordu. 
yani karşılaştırabilir bir yapı ve çıktılarımızı analiz imkanı sunuyordu.

[n.(n+1)] / 2

(n^2+n)/2

O(n^2)

###Time Comp.

Average case:  [2,6,16,18,22,27]       aradığımız sayının (18) dizinin ortasında olmasıydı

Worst case:    [27,22,18,16,6,2]       aradığımız sayının (2) dizinin sonunda olmasıydı

Best case:     [2,6,16,18,22,27]       aradığımız sayının (2) dizinin en başında olmasıydı.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6] n

[2,3,4,8,7,9,5,15,6] n-1

[2,3,4,5,7,9,8,15,6] n-2

[2,3,4,5,6,9,8,15,7] n-3

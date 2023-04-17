# patika
Patika
Proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

    Average case: Aradığımız sayının ortada olması
    Worst case: Aradığımız sayının sonda olması
    Best case: Aradığımız sayının dizinin en başında olması.

.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.


Cevap:
index olarak bakar 

big O Notation u O(n^2)dir. Çünkü her seferinde indexteki elemanları diğer elemanlarla karşılaştırır.

18 elemanı 4. indexte olduğu için 

İlk indexi en küçük kabul eder program sonra tek tek diğer indexlerle karşılaştırır. 
Daha küçük bir indeks ulunca onu tutar sonra karşılaştırmaya devam eder taa ki en küçüğü bulana kadar bulunca ilk indexle swap yapar. 

1- 22 yi en küçük kabul edip ilk 27 ile karşılaştırır. 22 daha küçük olduğu için hala onu tutar. 22 ve 16 yı karşılaştırır. 16 daha küçük olduğu için onu tutar. 16 ve 2 yi karşılaştırır.
2 yi diğerleriyle karşılaştırıp en küçük o olduğu için başa koyar. Tüm elemanları gezer yani n kere run eder. 2,22,27,16,18,6

2- İkinci aşamada 2 yi yerine koyup o index olmadan arama yapar. Yani 1. indexe bakar 22 yi karşılaştırmaya başlar. 6 yı bulana kadar yani baktığımız indexlerden en küçüğünü bulana kadar 
run eder. n-1 kere run edilecek. 2,6,22,27,16,18

3- Bu şekilde devam edecek sıradaki stepler olacak:
2,6,16,22,27,18 n-2

4- 2,6,16,18,22,27 n-3

5- 2,6,16,18,22,27 n-4

1 den n e kadar olan sayıların toplamı n*(n-1)/2  ani n^2 kere iterasyon edilecek.


18 ortada olduğundan average case i simgeler. 

[7,3,5,8,2,9,4,15,6]

1- 2,7,3,5,8,9,4,15,6

2- 2,3,7,5,8,9,4,15,6

3- 2,3,4,7,5,8,9,15,6

4- 2,3,4,5,7,8,9,15,6

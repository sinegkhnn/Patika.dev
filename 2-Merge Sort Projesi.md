# ☕ Patika.dev 


<h1 align="center">
  Merge Sort Projesi
</h1>


[16,21,11,8,12,22] -> Merge Sort

Dizisinin Merge Sort’a göre sıralanması:

   [16,21,11,8,12,22]       ->     [16,21,11]       [8,12,22]               
   [16,21,11]               ->     [16,21]    [11]
   [16,21]    [11]          ->     [16]  [21]   [11]
   [16]  [21]    [11]       ->     [16,21]    [11]
   [16,21]    [11]          ->     [11,16,21]*

  [16,21,11,8,12,22]        ->    [16,21,11]       [8,12,22]
  [8,12,22]                 ->    [8]    [12,22]
  [8]    [12,22]            ->    [8]  [12]  [22]
  [8]    [12]  [22]         ->    [8]    [12,22]
  [8]    [12,22]            ->    [8,12,22]**

Yukarıdaki  * ve ** dizilerini de sıralama yaptığımızda en küçük olanlar sola konular tekrar dizi elde edilir.

Big O gösterimi = Her adımda  n elemanlı diziyi 2 ye bölme işlemi yaparız. Bu da 2^x = n verir. Buradan O(nlogn) gelecektir.


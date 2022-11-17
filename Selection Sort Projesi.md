# ☕ Patika.dev 


<h1 align="center">
  Selection Sort Projesi
</h1>


[22,27,16,2,18,6] -> Insertion Sort

**1.Adım: **

[22,27,16,2,18,6] olarak verilen dizide en küçük sayı bulunur. Bu dizide 6.
En küçük sayı en başa yazılır. En baştaki sayı ile aslında yer değiştirmiş olur.

Yani [2,27,16,22,18,6] elde ederiz.

** 2.Adım:**
Daha sonra [2,27,16,22,18,6] dizisinde artık en baştaki en küçük sayımız olduğunu bulduk. İkinci sıradan sonrasındakilere bakmamız gerekiyor. 27,16,22,18,6 arasından
En küçük 6 olacağından 27 ile yer değişir. 

Yani [2,6,16,22,18,27] elde ederiz.

**3.Adım:**
[2,6,16,22,18,27] dizisinde zaten sıralı olduğunu görürüz. Dolayısıyla yer değiştirme yapmamıza gerek yoktur.

**4.Adım:**
Yine aynı şekilde diğer adımlardaki gibi bu sefer 22,18,27 arasından en küçük olanı seçmemiz gerekir.

 Yani [2,6,16,18,22,27] dizisi olur.
Son olarak yukarıdaki adımlar tekrar ederiz ve 22,27 ile kıyaslama yaptığımızda zaten sıralı olduğunu görürüz. Dolayısıyla işlem yapmamıza gerek kalmaz.


[2,6,16,18,22,27] insertion sort prensibine göre sıralamış olduk.

Big O gösterimi = n+(n-1)+(n-2)+…+1 = n*(n+1)/2 formülünden;
(n² +n)/2 den n² deriz. Çünkü n²’nin büyüme oranı n’den çok daha büyük olduğu için n’i dikkate almamıza gerek kalmıyor.

Time Complexity 18 için;

Dizini son hali [2,6,16,18,22,27] olduğu için Average case yani aradığımız sayının ortada olmasıdır.



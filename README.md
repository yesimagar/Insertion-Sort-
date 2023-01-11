@@ -1,38 +1,38 @@
 # algoritma-odev

 İnsertion Sort
 İnsertion Sort <br>
   [22,27,16,2,18,6] Dizisini insertion sort algoritması ile çalıştırdığımızda; <br>
   Dizinin ikinci elemanı başlangıç elemanı olarak seçilecektir.
   Başlangıç elemanı [27] kendinden önceki eleman olan [22] ile kıyaslanır.
   27>22 : sıralama değişmedi 
   Dizinin üçüncü elemanı [16] kendinden önceki elemanlarla kıyaslanır:
   27>22>16 ve sıralama : [16, 22, 27]
   Dizinin dördüncü elemanı [2] kendinden önceki elemanlarla kıyaslanır:
   27>22>16>2 ve sıralama: [2, 16, 22, 27]
   Dizinin beşinci elemanı [18] kendinden önceki elemanlarla kıyaslanır:
   27>22>18>16>2 ve sıralama: [2,16,18,22,27]
   Dizinin altıncı elemanı [6] kendinden önceki elemanlarla kıyaslanır:
   27>22>18>16>6>2 ve sıralama : [2,6,16,18,22,27]
   Dizinin son hali: [2,6,16,18,22,27]

 Big-O Gösterimi: 
   Big-O=(n^2)

 Time Complexity
    Dizi sıralandıktan sonra 18 sayısı Average case kapsamına girer.


   Dizinin ikinci elemanı başlangıç elemanı olarak seçilecektir. <br>
   Başlangıç elemanı [27] kendinden önceki eleman olan [22] ile kıyaslanır.<br>
   27>22 : sıralama değişmedi <br>
   Dizinin üçüncü elemanı [16] kendinden önceki elemanlarla kıyaslanır:<br>
   27>22>16 ve sıralama : [16, 22, 27]<br>
   Dizinin dördüncü elemanı [2] kendinden önceki elemanlarla kıyaslanır:<br>
   27>22>16>2 ve sıralama: [2, 16, 22, 27]<br>
   Dizinin beşinci elemanı [18] kendinden önceki elemanlarla kıyaslanır:<br>
   27>22>18>16>2 ve sıralama: [2,16,18,22,27]<br>
   Dizinin altıncı elemanı [6] kendinden önceki elemanlarla kıyaslanır:<br>
   27>22>18>16>6>2 ve sıralama : [2,6,16,18,22,27]<br>
   Dizinin son hali: [2,6,16,18,22,27]<br>
 <br>
 Big-O Gösterimi: <br>
   Big-O=(n^2)<br>
 <br>
 Time Complexity<br>
    Dizi sıralandıktan sonra 18 sayısı Average case kapsamına girer.<br>
    <br>
    <br>
 Selection Sort
   Dizi içindeki en küçük elemanı bulup baştaki ile yer değiştirerek çalışan bir yapısı vardır.

   [7,3,5,8,2,9,4,15,6]--> En küçük sayı bulunur: 2
   [2,3,5,8,7,9,4,15,6]--> 2 ve 7 yer değiştirir. 3 olduğu yerde kalır
   [2,3,4,8,7,9,5,15,6]--> 4 ve 5 yer değiştirir.
   [2,3,4,5,7,9,8,15,6]--> 5 ve 8 yer değiştirir.
   [2,3,4,5,6,9,8,15,7]--> 6 ile 7 yer değiştirir
   [2,3,4,5,6,7,8,15,9]--> 7 ile 9 yer değiştirir
   [2,3,4,5,6,7,8,9,15]--> 9 ve 15 yer değiştirir

   Dizinin ilk hali: [7,3,5,8,2,9,4,15,6]
   Dizinin son hali: [2,3,4,5,6,7,8,9,15] 
   Dizi içindeki en küçük elemanı bulup baştaki ile yer değiştirerek çalışan bir yapısı vardır.<br>
   <br>
   [7,3,5,8,2,9,4,15,6]--> En küçük sayı bulunur: 2<br>
   [2,3,5,8,7,9,4,15,6]--> 2 ve 7 yer değiştirir. 3 olduğu yerde kalır<br>
   [2,3,4,8,7,9,5,15,6]--> 4 ve 5 yer değiştirir.<br>
   [2,3,4,5,7,9,8,15,6]--> 5 ve 8 yer değiştirir.<br>
   [2,3,4,5,6,9,8,15,7]--> 6 ile 7 yer değiştirir<br>
   [2,3,4,5,6,7,8,15,9]--> 7 ile 9 yer değiştirir<br>
   [2,3,4,5,6,7,8,9,15]--> 9 ve 15 yer değiştirir<br>
   <br>
   Dizinin ilk hali: [7,3,5,8,2,9,4,15,6]<br>
   Dizinin son hali: [2,3,4,5,6,7,8,9,15] <br>

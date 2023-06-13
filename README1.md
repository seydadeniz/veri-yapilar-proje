# Proje 1
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
[2,27,16,22,18,6] En küçük sayıyı bulup başa aldık baştaki ile yerini değiştirdik.
[2|6,16,22,18,27] en baştaki en küçük olduğu için ona artık bakmıyoruz bu durumda n-1 oluyor
[2,6|16,22,18,27]burada en küçükleri zaten 16 olduğu için bir işleme gerek kalmadı.
2,6,16|18,22,27] sayılar artık sıralandı aslında bundan sonra sadece kontrol edilecek. 



Big-O gösterimini yazınız. n+(n-1)+n-2)+ ....  = (n.n+1)/2 
Hesaplamalar sonucunda elde edilen (n2+n)/2 değerinin asimptotik üst sınırı O(n2) değerini verir.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1.Average case: Aradığımız sayının ortada olması    1 yani aradığımız sayı ortada olması
2.Worst case: Aradığımız sayının sonda olması
3.Best case: Aradığımız sayının dizinin en başında olması.
.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
[2,3,5,8,7,9,4,15,6] 1. adım
[2|3,5,8,7,9,4,15,6]2.adım
[2,3|4,8,7,9,5,15,6]3. adım
[2,3,4|5,7,9,8,15,6]4.adım
[2,3,4,5|6,9,8,15,7]5.adım

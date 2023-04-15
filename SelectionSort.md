# Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız. <br>

Big-O gösterimini yazınız.<br>

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız<br>

1.Average case: Aradığımız sayının ortada olması<br>
2.Worst case: Aradığımız sayının sonda olması<br>
3.Best case: Aradığımız sayının dizinin en başında olması.<br>
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.<br>

-------------------------------------------------------------------------
Cevaplar<br>
1.Sorunun Cevabı:<br>
[22,27,16,2,18,6] bu diziden en küçük sayı seçilir ve en baştaki sayı ile yer değiştirilir. Ardından diğer sayılar içinde yer değiştirmeli sıralama işlemi yapılır.<br>
[22,27,16,2,18,6] (n)<br>
[2,27,16,22,18,6] (n-1) 2 ile 22 yer değiştirdi.<br>
[2,6,16,22,18,27] (n-2) 6 ile 27 yer değiştirdi.<br>
[2,6,16,18,22,27] (n-3) 22 ile 18 yer değiştirdi.<br>
[2,6,16,18,22,27]  1 son hali bu olur.<br>
2.Sorunun Cevabı: n+(n-1)+(n-2)+(n-3)+...+1 = n.(n+1)/2 = n üssü 2 +n/2. Baskın ifade n² dir. Big-O =(n²)<br>
3.Sorunun Cevabı: Sıralama işleminin sonunda 18 sayısı ortada olduğu için cevap Average case'dir.<br>
4.Sorunun Cevabı:<br>
1.Adım: [7,3,5,8,2,9,4,15,6]<br>
2.Adım: [2,3,5,8,7,9,4,15,6] 2 ile 7 yer değiştirdi.<br>
3.Adım: [2,3,4,8,7,9,5,15,6] 4 ile 5 yer değiştirdi.<br>
4.Adım: [2,3,4,5,7,9,8,15,6] 5 ile 8 yer değiştirdi.<br>
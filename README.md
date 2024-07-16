[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  1- En küçük dizi elemanı aranır. Bunun için n arama yapılır.
  2- n-1 arama
  3- n-2 arama
  4- n-3 arama
  5- n-4 arama
  6- n-5 arama
  7- 1 arama

  Bu 1'den n'e kadar olan sayıların toplamıdır. Formül [n*(n-1)]/2 ---> O(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
  18 sayısı sıralandıktan sonra 4. indekstedir. Bu yüzden "Average case".
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre sıralayın.

1- 7,3,5,8,2,9,4,15,6
  3<7
2- 3,7,5,8,2,9,4,15,6
  5<7
  5>3
3- 3,5,7,8,2,9,4,15,6
  8>7
4- 3,5,7,8,2,9,4,15,6
  2<8
  2<7
  2<5
  2<3
5- 2,3,5,7,8,9,4,15,6
  9>8
6- 2,3,5,7,8,9,4,15,6
  4<9
  4<7
  4<5
  4>3
7- 2,3,4,5,7,8,9,15,6
  15>9
8- 2,3,4,5,7,8,9,15,6
  6<15
  6<9
  6<8
  6<7
  6>5
9- 2,3,4,5,6,7,8,9,15

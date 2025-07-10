##### Veri Yapılar Ve Algortimalar Proje 2



***Soru:***

***\[16,21,11,8,12,22] -> Merge Sort***



***Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.***

***Big-O gösterimini yazınız.***





1- Merge sort, elemanları 1 tane kalıncaya kadar parçalar ve sonra sıralı bir şekilde birleştirir



1.parçalama -> 16,21,11   | 8,12,22

2.parçalama -> 16  21,11  | 8  12,22

3.parçalama -> 16  21  11 | 8  12  22



sonra sıralı bir şekilde birleştirir



21+11 --> 11,21

16 + 11,21 ---> 11,16,21



12+22 --> 12,22

8 + 12,22 --> 8,12,22



ve en son:



\[11, 16, 21] + \[8, 12, 22] --> \[8, 11, 12, 16, 21, 22]





2-Merge sortun Big-O gösterimi her durumda O(n log n) şeklinde olur.




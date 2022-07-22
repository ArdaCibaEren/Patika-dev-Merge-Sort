# Patika.dev Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

# [16,21,11,8,12,22] Dizisinin Merge Sort Aşamaları

* Diziyi [16,21,11] ve [8,12,22] olarak 2 parçaya ayırıyoruz.

* Sonra tekrar parçalayarak devam ediyoruz.

* [16],[21,11] ve [8],[12,22]

* [16], [21], [11] ve [8], [12], [22]

* [16], [11,21] ve [8], [12,22]

* [11,16,21] ve [8,12,22]

* Son aşamada en küçükten en büyüğe göre sıralanıyor. [8,11,12,16,21,22]

# Big O gösterimi : O(nlogn)
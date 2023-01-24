# Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalırını yazınız.

	Her adımda parçaya ayırarak tek parça kalana kadar bölüyoruz.
	[16,21,11,8,12,22]
	[16,21,11]   [8,12,22]
	[16] [21,11]   [8] [12,22]
	[16] [21] [11]   [8] [12] [22]

	Sıralama yapıp birleştiriyoruz.
	[16] [11,21]   [8] [12,22]
	[11,16,21]   [8,12,22]
	[8,11,12,16,21,22]

Big-O gösterimini yazınız.

	Big-O = O(nlogn)

[https://www.patika.dev/tr](https://www.patika.dev/tr)

Proje 2
[16,21,11,8,12,22] -> Merge Sort

1-Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2-Big-O gösterimini yazınız.

Sıralanmasını istediğimiz sayı listemiz [16,21,11,8,12,22].


- İlk önce listemizi 2'ye bölelim.
    16,21,11  8,12,22
        - Böldüğümüz listeyi tekrardan ikiye bölelim.
            *** Elde edilen parçalar 2 veya daha küçük eleman sayısına ulaştığı için durulur.
        - Her parçayı kendi içinde sırala
            16, 21 - 11 - 8,12 - 22
        - Her bölünmüş parçayı sıralı bir şekilde birleştir.
            11, 16, 21 - 8, 12, 22
        - Tek bir bütün parça haline gelmesi için tekrar birleştirilir.
            8, 11, 12, 16, 21, 22
        - Tek parça olduğundan dolayı işlem durur, sayı dizimiz aşağıdaki gibidir.
            sayi_dizisi = [8, 11, 12, 16, 21, 22]

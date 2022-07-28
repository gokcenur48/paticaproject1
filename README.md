[22,27,16,2,18,6] -> Insertion Sort

1.adım: [2,27,16,22,18,6]
2.adım:[2,6,16,22,18,27]
3.adım:[2,6,16,22,18,27]>>Değişiklik yok.
4.adım:[2,6,16,18,22,27]
5.adım:[2,6,16,18,22,27]>>Değişiklik yok.

Soru:
İlk adımda n sayıda işlem yapılır.Daha sonra n-1,n-2,...,1 olana kadar devam eder.Bunlarında toplamı (n*(n+1))/2 ile bulunur.Sonuç olarak Big-O gösterimi O(n^2) olur.

Soru:Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
18 sayısı dizinin ortasında yer almasına rağmen sıralama yapılırken en sonuncu işlemden sonra yerini alır.Bu yüzden worst case'dir.

Soru:[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1.Adım: [2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]>>Değişiklik yok.
2.Adım:[2,3,4,8,7,9,5,15,6]
3.Adım:[2,3,4,5,7,9,8,15,6]
4.Adım:[2,3,4,5,6,9,8,15,7]
https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje

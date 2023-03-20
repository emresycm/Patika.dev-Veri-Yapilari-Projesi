# [Patika.dev](https://app.patika.dev) Veri Yapilari Projesi
### Sorting ve Searching Algoritmalari
-----------------------------------------------------------------
## Insertion Sort (Eklemeli sıralama)

 Eklemeli Sıralama, bilgisayar bilimlerinde kullanılan ve sıralı diziyi her adımda öğe öğe oluşturan bir sıralama algoritmasıdır. Büyük dizilerle çalışıldığında hızlı sıralama, birleştirmeli sıralama ve yığın sıralaması gibi daha gelişmiş sıralama algoritmalarından daha verimsiz çalışır.[Wikipedia](https://tr.wikipedia.org/wiki/Eklemeli_sıralama)

- Zaman karmaşıklığı: O(n²)
- Alan karmaşıklığı: O(1)
- En iyi: Genellikle değil
- Veri yapısı: Dizi

 |  Adım    |     Dizi Durumu    |
 -----------|---------------------
 | 1.adım   |  [22,27,16,2,18,6] |
 | 2.adım   |  [22,27,16,2,18,6] |
 | 3.adım   |  [16,22,27,2,18,6] |
 | 4.adım   |  [2,16,22,27,18,6] |
 | 5.adım   |  [2,16,18,22,27,6] |
 | 6.adım   |  [2,6,16,18,22,27] |

-----------------------------------------------------------------
## Selection Sort (Seçmeli sıralama)

Seçmeli Sıralama, bilgisayar bilimlerinde kullanılan bir sıralama algoritmasıdır. Karmaşıklığı O(n²) olduğu için büyük listeler üzerinde kullanıldığında verim sağlamaz ve genel olarak benzeri olan eklemeli sıralamadan daha başarısızdır. Seçmeli sıralama yalın olduğu ve bazı durumlarda daha karmaşık olan algoritmalardan daha iyi sonuç verdiği için tercih edilebilir.[Wikipedia](https://tr.wikipedia.org/wiki/Seçmeli_sıralama)

- Zaman karmaşıklığı: O(n²)
- Alan karmaşıklığı: toplamda О(n), ek alan O(1)
- En iyi: Genellikle değil
- Veri yapısı: Dizi

 |  Adım    |     Dizi Durumu       |
 -----------|-----------------------
 | 1.adım   |  [7,3,5,8,2,9,4,15,6] |
 | 2.adım   |  [2,3,5,8,7,9,4,15,6] |
 | 3.adım   |  [2,3,4,8,7,9,5,15,6] |
 | 4.adım   |  [2,3,4,5,7,9,8,15,6] |
 
-----------------------------------------------------------------
## Merge Sort (Birleştirmeli sıralama)


# [Patika.dev](https://app.patika.dev) Veri Yapilari Projesi
### Sorting ve Searching Algoritmalari
----------------------------------------------------------------
## Insertion Sort

 |  Adım    |     Dizi Durumu    |
 -----------|---------------------
 | 1.aşama  |  [22,27,16,2,18,6] |
 | 2.aşama  |  [22,27,16,2,18,6] |
 | 3.aşama  |  [16,22,27,2,18,6] |
 | 4.aşama  |  [2,16,22,27,18,6] |
 | 5.aşama  |  [2,16,18,22,27,6] |
 | 6.aşama  |  [2,6,16,18,22,27] |

-----------------------------------------------------------------
## Insertion Sort - Big-O Notation ve Time Complexity

Eklemeli Sıralama, bilgisayar bilimlerinde kullanılan ve sıralı diziyi her adımda öğe öğe oluşturan bir sıralama algoritmasıdır. Büyük dizilerle çalışıldığında hızlı sıralama, birleştirmeli sıralama ve yığın sıralaması gibi daha gelişmiş sıralama algoritmalarından daha verimsiz çalışır.

- Zaman karmaşıklığı: O(n²)
- Alan karmaşıklığı: O(1)
- En iyi: Genellikle değil
- Veri yapısı: Dizi
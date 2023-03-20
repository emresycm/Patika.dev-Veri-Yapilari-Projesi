# [Patika.dev](https://www.patika.dev/tr) Veri Yapilari Projesi
### Sorting ve Searching Algoritmalari
-----------------------------------------------------------------
## Insertion Sort (Eklemeli sıralama)

 Eklemeli Sıralama, bilgisayar bilimlerinde kullanılan ve sıralı diziyi her adımda öğe öğe oluşturan bir sıralama algoritmasıdır. Büyük dizilerle çalışıldığında hızlı sıralama, birleştirmeli sıralama ve yığın sıralaması gibi daha gelişmiş sıralama algoritmalarından daha verimsiz çalışır.[Wikipedia](https://tr.wikipedia.org/wiki/Eklemeli_sıralama)

- Zaman karmaşıklığı: O(n²)
- Alan karmaşıklığı: O(1)
- En iyi: Genellikle değil
- Veri yapısı: Dizi

### Örnek Dizi : [22,27,16,2,18,6]

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

### Örnek Dizi : [7,3,5,8,2,9,4,15,6]

 |  Adım    |     Dizi Durumu       |
 -----------|-----------------------
 | 1.adım   |  [7,3,5,8,2,9,4,15,6] |
 | 2.adım   |  [2,3,5,8,7,9,4,15,6] |
 | 3.adım   |  [2,3,4,8,7,9,5,15,6] |
 | 4.adım   |  [2,3,4,5,7,9,8,15,6] |
 
-----------------------------------------------------------------
## Merge Sort (Birleştirmeli sıralama)

Birleşmeli Sıralama (Merge Sort), bilgisayar bilimlerinde O(n log(n)) derecesinde karmaşıklığa sahip bir sıralama algoritmasıdır. Girdi olarak aldığı diziyi en küçük hale gelene kadar ikili gruplara böler ve karşılaştırma yöntemi kullanarak diziyi sıralar.[Wikipedia](https://tr.wikipedia.org/wiki/Birleştirmeli_sıralama)

- Zaman karmaşıklığı: O(n log(n))
- Alan karmaşıklığı: En kötü durumda О(n)
- En iyi: Genellikle
- Veri yapısı: Dizi

### Örnek Dizi : [16,21,11,8,12,22]

|  Adım    |     Dizi Durumu               |
 ----------|-------------------------------
| 1.adım   |      [16,21,11,8,12,22]       |
| 2.adım   |     [16,21,11]-[8,12,22]      |
| 3.adım   |   [16]-[21,11]-[8,12]-[22]    |
| 4.adım   | [16]-[21]-[11]-[8]-[12]-[22]  |
| 5.adım   |   [16]-[11,21]-[8,12]-[22]    |
| 6.adım   |     [11,16,21]-[8,12,22]      |
| 7.adım   |      [8,11,12,16,21,22]       |

 -----------------------------------------------------------------
 ## Binary Searh Tree (İkili Arama Ağacı)

 İkili arama ağacı, verileri organize etmek için kullanılan bir çeşit ikili ağaçtır. İkili ağaçtan temel farkı, verilerin sıralanmış bir şekilde tutulmasıdır, bu sayede ikili arama algoritmasının kullanılmasına imkân verir.
 İkili arama ağaçlarında; her düğümün sağ çocuğu kendisinden büyük, sol çocuğu ise kendisinden küçüktür. Bu ağaçlarda çalışan arama algoritması önce kökten başlar, eğer aranan eleman kökten büyükse sağ çocuğa, kökten küçükse sol çocuğa ilerler. Böylece, eleman bulunana yapraklara kadar yinelemeli bir şekilde ilerleme sağlanır.[Wikipedia](https://tr.wikipedia.org/wiki/İkili_arama_ağacı)

### Örnek Dizi : [7,5,1,8,3,6,0,9,4,2]


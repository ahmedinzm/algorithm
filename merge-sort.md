Verilen diziyi Merge Sort algoritması ile sıralamak için şu aşamalar gerçekleştirilir:
1. Diziyi ikiye bölme: [16,21,11] ve [8,12,22]
2. Sol ve sağ tarafın her biri için ayrı ayrı Merge Sort işlemi uygulama:
   Sol taraf: [16,21,11] -> [11,16,21]
   Sağ taraf: [8,12,22] -> [8,12,22]
3. Sıralanmış sol ve sağ dizileri birleştirme: [11,16,21], [8,12,22] -> [8,11,12,16,21,22]

Bu şekilde verilen dizi sıralanmış olur.

Merge Sort'un Big-O gösterimi O(n log n)'dir.

Not: Merge Sort'ta bir dizinin boyutu 2^n olduğunda en iyi performans elde edilir, fakat verilen örnek için bu durum geçerli değildir.

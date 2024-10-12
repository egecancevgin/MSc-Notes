## Finansta Makine Öğrenimi Ders Notları

### Varyans, Volatilite, Risk ve Standart Sapma aralarındaki farklar nelerdir?
  - Sapma, |Veri noktaları - Ortalama|'dır, `Varyans` ise tüm bu sapmaların karelerinin ortalamasıdır yani avg(|Veri - Ortalama|^2)'dır.
  - `Standart Sapma` varyansın kareköküdür ve daha ufaktır daha anlaşılırdır.
  - Varyans uç değerlere daha fazla ağırlık verdiği için daha hassas bir ölçüdür.
  - `Volatilite`, bir varlığın getirilerinin ne kadar dalgalandığıdır ve genellikle standart sapma ile ölçülür.
  - `Risk`, yatırımın beklenen getiriden sapma olasılığıdır ve yukarıdaki boş terimler ve başka terimler ile ölçülen oynaklıktır.
   
### Skewness, Heavy Tailness ve Kurtosis terimleri aralarındaki farklar nelerdir?
  - `Skewness`, dağılımın asimetrik olup olmadığını ölçer, yani diyelim yüksek uç değerler fazla bu durumda sağa skewed deriz. Ör: 1.90'dan uzun çok kişi varsa.
  - `Kurtosis`, dağılımın uç değerlerinin normalden yoğun olup olmadığını ölçer. Genelde herkes 1.70'lerde ise kurtosis düşüktür.
  - `Heavy Tailness`, uç bölgelerde normalden daha fazla veri noktası olduğu anlamına gelir. Ör: Boyu 2.10 ve 1.40 olan normalden fazla kişi varsa.
  - `Quantile-Quantile Plot`, referans çizgisinden uzaklıklar varsa heavy-tailness ve skewness belirtir.

## Korelasyon, Pearson Korelasyonu, Otokorelasyon ve Kovaryans aralarındaki farklar nelerdir?
  - `Korelasyon`, iki değişkenin birlikte nasıl değiştiğini ölçer ve -1 ile 1 arasındadır. Ör: Kişinin boyu ile kol uzunluğu korelasyonu 0.8 olabilir.
  - `Kovaryans`, 
  - `Pearson Korelasyonu`, doğrusal bir korelasyondur ve sadece doğrusal bakar.   


Kapital Market Doğrusu, piyasa portföyü ile risksiz getiri arasındaki farkın piyasa standart sapmasına bölünmesidir.

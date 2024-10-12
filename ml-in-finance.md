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

### Korelasyon, Pearson Korelasyonu, Kovaryans ve Kovaryans Matrisi aralarındaki farklar nelerdir?
  - `Korelasyon`, iki değişkenin birlikte nasıl değiştiğini ölçer ve -1 ile 1 arasındadır. Ör: Kişinin boyu ile kol uzunluğu korelasyonu 0.8 olabilir.
  - `Kovaryans`, iki değişkenin aynı yönde mi zıt yönde mi hareket ettiğini ölçer. Değişkenlerin büyüklüğünden etkilenir bu yüzden kıyaslama yapmak doğru değildir.
  - `Pearson Korelasyonu`, doğrusal bir korelasyondur ve sadece doğrusal bakar, kovaryans(a,b) / (stdspma(a)*stdspma(b)) şeklinde hesaplanır.
  - `Kovaryans Matrisi`, birden fazla varlığın birlikte ne yönde hareket ettiklerini gösterir, Ör: THY ve ASL kovaryansı pozitif, birini portföyden çıkart ki risk azalsın.


### Aşağıdaki grafikte Beklenen Getiri, Kapital Market Doğrusu, Sharpe Oranı nedir?
  - ![](https://raw.githubusercontent.com/egecancevgin/MSc-Notes/refs/heads/main/resim.png)
  - `Beklenen Getiri`, bir hisseden beklenen getiridir. Ör: THY'nin, %10 getiri olasılığı %40, %5 getiri olasılığı %30, %2 kayıp olasılığı %30 diyelim.
  - Beklenen Getiri = (0.4 * 0.1) + (0.3 * 0.05) - (0.3 * 0.02) = 4.9%, bu THY'nin beklenen getirisidir.
  - Eğer birden fazla hisse varsa ör: THY %5 beklenen getiri, %40 ağırlık, ASL %6 beklenen getiri, %30 ağırlık, Koç %4 beklenen getiri, %30 ağırlık diyelim.
  - Beklenen Getiri = (0.05 * 0.4) + (0.06 * 0.3) + (0.04 * 0.3) = %5, bu portföyün beklenen getirisidir.
  - `Kapital Market Doğrusu`, piyasa portföyü ile risksiz getiri arasındaki farkın piyasa standart sapmasına bölünmesidir.
  - Bu doğru, X ekseni standart sapma ve Y ekseni beklenen getiri olan bir grafikte bulunur.
  - Kısacası risksiz varlık ve optimal riskli portföy kombinasyonları arasında en iyi risk-getiri dengesini gösterir.
  - `Efficient Frontier`, bir eğridir ve kapital market doğrusuna teğet geçer ve teğet noktası en iyi risk-getiri dengesini sağlayan portföyü gösterir.
  - `Sharpe Oranı` (Beklenen Getiri - Risksiz Getiri)/Standart Sapma olarak hesaplanır.
  - Efficient Frontier ile CML'nin kesiştiği nokta, en yüksek Sharpe Oranı'na sahip portföyü gösterir.


### Markowitz'in Mean Variance Portfolio'su nedir?
  - 

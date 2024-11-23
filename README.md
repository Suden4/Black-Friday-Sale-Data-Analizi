# Black-Friday-Sale-Data-Analizi

Proje Özeti
Bu proje, Black Friday satış etkinliği sırasında tüketici satın alma davranışlarını analiz etmek için kullanılan Black Friday Sale veri setini incelemektedir. Veri seti, müşteri demografileri, ürün detayları ve işlem verileri gibi bilgileri içermektedir. Bu veriler, müşteri tercihleri, satın alma alışkanlıkları ve pazar trendlerini anlamak için değerli bilgiler sunmaktadır. Veri ön işleme, keşifsel veri analizi (EDA) ve görselleştirme yöntemleriyle bu analiz, işletmelerin Black Friday gibi büyük satış etkinliklerinde satış stratejilerini optimize etmelerine yardımcı olacak eyleme dönüştürülebilir içgörüler sunmayı hedeflemektedir.

Veri Seti
Bu analizde kullanılan veri seti, Kaggle’dan alınan Black Friday Sale veri setidir. Aşağıdaki sütunlar bulunmaktadır:

User ID: Her müşteriye özgü bir kimlik numarası.
Product ID: Her ürüne özgü bir kimlik numarası.
Gender: Müşterinin cinsiyeti (Erkek/Kadın).
Age: Müşterinin yaş grubu.
Occupation: Müşterinin mesleği.
City Category: Müşterinin yaşadığı şehirin tipi (A, B, C).
Stay In Current City Years: Müşterinin şu anki şehirde yaşama süresi.
Product Category: Satın alınan ürünün kategorisi.
Purchase: Müşterinin Black Friday sırasında harcadığı miktar.

Amaçlar
Bu analizdeki ana hedefler:
Tüketici davranışlarını anlamak: Müşteri demografilerine dayalı satın alma eğilimlerini incelemek.
En popüler ürünleri belirlemek: Hangi ürünlerin en çok satıldığını tespit etmek.
Bölgesel analiz yapmak: Farklı şehir kategorilerinde satın alma eğilimlerini araştırmak.
Korelasyonları incelemek: Müşteri özellikleri (yaş, cinsiyet, meslek vb.) ile harcama alışkanlıkları arasındaki ilişkileri keşfetmek.

Kullanılan Araçlar ve Teknolojiler
Bu projede aşağıdaki araçlar ve kütüphaneler kullanılmıştır:
Python: Veri analizi ve görselleştirme için kullanılan ana programlama dili.
Pandas: Veri manipülasyonu ve temizliği için kullanıldı.
Matplotlib: Veri görselleştirme için kullanıldı.
Seaborn: Gelişmiş veri görselleştirme için kullanıldı.
Jupyter Notebook: Analizlerin interaktif olarak geliştirildiği ortam.

Analiz Adımları

Veri Toplama ve İçe Aktarma:
Veri, Pandas kullanılarak bir CSV dosyasından içe aktarıldı.
Veri Temizleme:
Eksik veriler ve aykırı değerler yönetildi.
Kategorik değişkenler, analiz için uygun hale getirildi.
Keşifsel Veri Analizi (EDA):
Veri setinin temel özelliklerini anlamak için açıklayıcı istatistikler üretildi.
Yaş, harcama miktarı gibi sayısal değişkenlerin dağılımları görselleştirildi.
Grafikler kullanılarak desenler ve eğilimler keşfedildi.
Müşteri Segmentasyonu:
Müşteri demografileri (cinsiyet, yaş, meslek vb.) analiz edilerek farklı müşteri segmentleri belirlendi.
Harcama alışkanlıkları bu segmentler arasında karşılaştırıldı.
Ürün Kategorisi Analizi:
Farklı ürün kategorilerinin popülerliği analiz edildi.
En çok satan ürün kategorileri görselleştirildi.
Bölgesel Analiz:
Farklı şehir kategorileri arasında satın alma davranışları karşılaştırıldı.
Bölgesel farklılıklar analiz edilerek, hangi bölgelerin daha fazla harcama yaptığı belirlendi.
Korelasyon Analizi:
Müşteri özellikleri ile harcama miktarı arasındaki ilişkiler araştırıldı.
İstatistiksel olarak anlamlı korelasyonlar tespit edildi.

Önemli İçgörüler
Müşteri Segmentasyonu:

Kadın müşteriler, erkek müşterilere kıyasla daha fazla harcama yapmaktadır, özellikle belirli yaş gruplarında.
26-35 yaş grubu, Black Friday sırasında en aktif alıcı grubudur.
Ürün Kategorisi Eğilimleri:

Elektronik ve moda gibi belirli ürün kategorileri, diğer kategorilere göre daha yüksek satış rakamları elde etmiştir.
Bölgesel Tercihler:

"A" kategorisindeki şehirlerdeki müşteriler, "B" ve "C" kategorilerindeki şehirlere kıyasla daha fazla harcama yapmaktadır. Bu, daha zengin bölgelerde yaşayan müşterilerin daha fazla harcama eğiliminde olduğunu göstermektedir.
Harcama Davranışı:
Genç müşteriler (18-25 yaş) ortalama olarak daha düşük harcamalar yaparken, daha yaşlı müşteriler (36-45 yaş) daha yüksek harcamalar yapmaktadır.

Gelecek İyileştirmeleri
Tahminsel Modelleme: Makine öğrenmesi modelleri kullanarak, müşteri demografilerine göre gelecekteki satın almaları tahmin etmek.
Zaman Serisi Analizi: Satın alma eğilimlerini zaman içinde analiz ederek, gelecek Black Friday satışlarını tahmin etmek.
Öneri Sistemi: Geçmiş satın alımlarına dayalı olarak müşterilere ürün önerileri sunan bir sistem geliştirmek.

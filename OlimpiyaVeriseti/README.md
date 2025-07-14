# 🏅 Olimpiyat Verisi Analiz Projesi
Bu çalışma, temizlenmiş ve modellenmiş bir olimpiyat veri seti üzerinden Power BI ve veri analizi becerilerini geliştirme amacıyla hazırlanmıştır
## Veri Temizleme

Bu projede Kaggle üzerinden alınan `athlete_events.csv` ve `noc_regions.csv` adlı veri setleri kullanılmıştır. Veri analizine geçmeden önce kapsamlı bir veri temizliği gerçekleştirilmiştir:

- `"NA"` şeklindeki eksik veriler uygun şekilde `NULL` ile değiştirilmiştir.
- `"France-1"`, `"Germany-2"` gibi hatalı ülke adları `"France"`, `"Germany"` şeklinde standartlaştırılmıştır.
- `NOC` kodlarındaki hatalı veya eksik değerler `noc_regions` dosyasındaki doğru bilgilerle güncellenmiştir.
- Gerçek dışı görülen `Weight` (örneğin: `55,1175`) gibi değerler veri kümesindeki ortalama ile değiştirilmiştir.
- `noc_regions` ile `athlete_events` dosyası arasındaki uyumsuzluklar giderilmiştir.
- Veri tiplerindeki tutarsızlıklar (örneğin metin olarak kaydedilmiş sayılar) uygun veri tiplerine dönüştürülmüştür.

> ⚠️ **Not:** Orijinal veri seti yüksek satır sayısına sahip olduğundan (yaklaşık 270.000+ satır), bilgisayar donanımı yetersizliği nedeniyle analiz süreci 500 satırlık bir örnek veri üzerinden gerçekleştirilmiştir. Daha güçlü bir sistem kullanıldığında tüm veri ile daha kapsamlı ve doğru analizler yapılabilir.

## Veri Modelleme - Star Schema
<img width="1159" height="534" alt="Image" src="https://github.com/user-attachments/assets/74b78e68-6844-44a1-ab88-7117fddbcbf7" />
Veri temizliği tamamlandıktan sonra, Power BI’da kolay analiz yapmayı sağlamak amacıyla **Star Schema (Yıldız Şeması)** modeli kurulmuştur.

## Dashboard Görseli
<img width="1107" height="624" alt="Image" src="https://github.com/user-attachments/assets/ff34df16-786c-4f3f-85f8-0436f5aa4b28" />







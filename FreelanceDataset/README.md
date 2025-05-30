# 🚀 Freelance Proje Yönetimi & Analizi – Power BI Dashboard

Bu proje, freelance çalışan bir bireyin proje süreçlerini, müşteri ilişkilerini ve finansal durumunu analiz etmek üzere tasarlanmış 3 sayfalık bir Power BI dashboard'udur.  
Star şema modeliyle DIM ve FACT tabloları ayrıştırılmış, veri modellemesi profesyonel BI standartlarına uygun olarak hazırlanmıştır.

---

## 🧠 Dashboard Sayfaları

### 1️⃣ Proje Performans Analizi
- ✅ Yapılan toplam proje adedi  
- ⏱️ Zamanında teslim edilen projeler  
- 🕒 Toplam çalışılan saat  
- ⚠️ Geç teslim edilen proje sayısı  
- ⭐ Ortalama müşteri puanı  
- 🧭 Ortalama gecikme süresi  
- 💻 Platformlara göre proje sayısı  
- 📉 Gecikme sebepleri analizi  
- 🔧 En sık kullanılan teknolojiler  
- 📅 En çok talep gelen zaman dilimi  
- 🔁 Revizyon sayısı vs teslim süresi ilişkisi  
- 🔍 Dinamik analiz için: Yıl, Platform, Proje Kategorisi, Proje Durumu slicer'ları

---

### 2️⃣ Müşteri Analizi
- 🤝 Ortalama müşteri puanı  
- 📁 Müşteri başına proje sayısı  
- 💰 Müşteri bazlı toplam kazanç  
- 🧾 Teslim tarihi geçmiş firma sayısı & isimleri  
- 🗂️ Firma başına ortalama puan ve proje adedi (Tablolu format)  
- 💬 Geri bildirim analizi (Negatif / Nötr / Pozitif)  
- 📞 İletişim sıklığına göre memnuniyet analizi  
- 🔄 En çok revizyon isteyen müşteriler  
- 🏭 Sektöre göre müşteri yoğunluğu  
- 🎛️ Dinamik analiz için: Müşteri ve Sektör slicer’ları

---

### 3️⃣ Finansal Performans
- 💸 Toplam kazanç  
- ✂️ Kesinti miktarı  
- 📉 Kaç projede kesinti yapılmış  
- 📊 Kesinti oranı & sebepleri (tablo)  
- ⚖️ Anlaşılan ücret vs Gerçekleşen ücret karşılaştırması  
- 📌 Müşteri bazlı kazanç analizi  
- 📆 Aylık bazda gelir ve kesinti oranı  
- 🎛️ Dinamik analiz için: Yıl ve Ay slicer’ları

---

## 🧱 Veri Modeli

- **Model Türü:** Star Schema  
- **Kullanılan Tablolar:**
  - `DIM_Musteriler`
  - `DIM_Projeler`
  - `DIM_Teknolojiler`
  - `FACT_ProjePerformans`
  - `FACT_FinansalDurum`
  - `FACT_GeriBildirim`

Tüm ölçümler basit ve orta seviye DAX fonksiyonlarıyla oluşturulmuştur.

---

## 📸 Dashboard Görselleri

### Proje Performans Sayfası  
![Image](https://github.com/user-attachments/assets/f97c1f67-7b9e-4f48-915b-41e4fa4c6230)

### Müşteri Analizi Sayfası  
![Image](https://github.com/user-attachments/assets/538de367-01e0-494c-99ae-b699d9f967ac)

### Finansal Performans Sayfası  
![Image](https://github.com/user-attachments/assets/7aa94cbb-ded6-491d-8e06-d9351082b811)

---

## 🎯 Projenin Katkısı

Bu proje ile freelance çalışanlar;
- Proje yönetim verilerini sistematik şekilde takip edebilir,
- Müşteri memnuniyeti ve ilişkilerini analiz edebilir,
- Finansal performansını aylık ve müşteri bazında değerlendirebilir.


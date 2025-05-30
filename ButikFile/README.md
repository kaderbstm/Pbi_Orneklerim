# 🛍️ Mini Butik Satış & İade Dashboardu

Bu proje, küçük ölçekli bir butik mağazanın satış ve iade verilerinin analizine odaklanmaktadır. Dashboard, Power BI kullanılarak iki sayfa halinde hazırlanmıştır: **Satış Analizi** ve **İade Analizi**.

## 🎯 Proje Hedefi
- Satış performansını izlemek
- Ürün, kategori ve beden bazlı analizler yapmak
- Aylık trendleri görmek
- Stok risklerini takip etmek
- İade oranlarını ve nedenlerini analiz etmek
- 
## 📄 Dashboard Sayfaları

### 1️⃣ Satış Analizi

Bu sayfa, butiğin satış dinamiklerine odaklanır:

- 🧮 **Toplam Ürün Adedi**
- 🛒 **Toplam Satış Adedi**
- 💰 **Toplam Satış Tutarı (₺)**
- 🧾 **Toplam İade + Satış Tutarı**
- 📉 **Net Satış Tutarı**
- 🗂️ **Kategori Bazlı Satış Tutarı ve Adedi**
- 🧵 **Beden Bazlı Satış Analizi**
- 📆 **Aylık Satış Trendleri**
- 🚨 **Stok Seviyesi Düşük Ürünler (Tehlikeli)**

### 2️⃣ İade Analizi

Bu sayfa, müşteri iadeleri ve sebeplerine odaklanır:

- 🔁 **Toplam İade Adedi**
- 📊 **İade Oranı (%)**
- 💸 **Toplam İade Tutarı**
- ✅ **Net Satış Sonrası Durum**
- 📦 **İade Adetleri ve Sebep Dağılımı**
- 📅 **Ay Bazlı İade Trendleri**
- 📋 **Ürün Bazlı İade Tablosu (Ürün İsmi + Sebep + Adet)**

---

## 📈 Kullanılan Veri Setleri

- **Satış Verileri**  
  Ürün Adı, Kategori, Beden, Satış Tarihi, Miktar, Tutar

- **İade Verileri**  
  Ürün Adı, İade Tarihi, Sebep, Miktar, Tutar

- **Ürün Stok Bilgileri**  
  Stok Adedi, Kritik Seviye

## 🧩 Kullanılan Veri Yapısı
- **Fact Table(s):** Fact key ile belirtildi
- **Dimension Table(s):** Dim key ile belirtildi
- Star schema mantığına uygun şekilde yapılandırıldı.
---

## 💡 Kullanılan Teknolojiler

- Power BI Desktop
- Temel DAX İfadeleri
- Excel (veri kaynağı)

---

## 🌈 Dashboard Görünümü

> 📌 Görseller aşağıda eklenecek  
(Dashboard'un 2 sayfasından SS al → `satis-dashboard.png` ve `iade-dashboard.png` olarak klasöre at → aşağıdaki satırları aktif et)

```md
### 🛍️ Satış Analizi

![Satış Dashboard](./satis-dashboard.png)

### 🔁 İade Analizi

![İade Dashboard](./iade-dashboard.png)

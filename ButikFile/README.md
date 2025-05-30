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
## 🌈 Dashboard Görünümü

### 🛍️ Satış Analizi
![Image](https://github.com/user-attachments/assets/a48dfa65-1e5f-4d2f-9356-254d28bf445f)

### 🔁 İade Analizi

![Image](https://github.com/user-attachments/assets/5eb78cf2-d784-43e1-8f9b-20b695d67643)

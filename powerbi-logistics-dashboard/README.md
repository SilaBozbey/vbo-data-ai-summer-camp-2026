# Lojistik & Kargo Performans Dashboard (Power BI)

Bu projede Olist e-ticaret veri seti kullanılarak şirket yönetiminin kargo maliyetlerini ve bölgesel etkilerini analiz eden bir Power BI raporu geliştirilmiştir.

##Rapor İçeriği ve Özellikler
- **Veri Modeli:** Yıldız şema (Star Schema) yapısına uygun boyut ve olgu tabloları (`FactSales`, `DimCustomer`, `DimProduct`, `DimDate`).
- **Temel Metrikler:** Toplam Kargo Tutarı, Sipariş Başı Ortalama Yük (DAX ölçüleri ile).
- **Görselleştirmeler:** Zaman trendi (Kargo ve Satış kıyaslaması), ürün bazlı kargo dağılımı ve eyalet bazlı matris tablosu.
- **Koşullu Biçimlendirme:** Kargo/Satış oranı %20'nin üzerinde olan eyaletlerin dinamik olarak kırmızı renkle vurgulanması.

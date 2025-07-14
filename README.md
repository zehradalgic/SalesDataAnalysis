📊 Power BI Raporu - Satış Analizi
Proje Adı: 2025 Satış Dashboardu
Hazırlayan: Zehra Dalgıç
Tarih: Temmuz 2025

📌 Amaç
Bu Power BI raporu, 500 kayıtlık satış verisi üzerinden genel performansı analiz etmek, satış eğilimlerini görmek ve işletmeye stratejik öngörüler sağlamayı amaçlamaktadır.

📁 Veri Seti
Kaynak Dosya: sales_data_cleaned.xlsx

Kayıt Sayısı: 500

Sütunlar:

Order No (Sipariş No)

Order Date (Tarih)

Customer No & Name (Müşteri Bilgileri)

City (Şehir)

Category (Ürün Kategorisi)

Product (Ürün Adı)

Quantity (Adet)

Unit Price (Birim Fiyat)

Total Sales (Toplam Tutar)

📈 Kullanılan Görseller ve Analizler
Görsel	Açıklama
Card	Toplam Satış, Ortalama Satış, Müşteri Sayısı
Column Chart	Kategori bazlı toplam satış karşılaştırması
Bar Chart	En çok satış yapan 10 şehir
Line Chart	Sipariş tarihine göre satış eğilimi
Gauge	Toplam satışın hedefe ulaşma yüzdesi (Hedef: ₺2.000.000)

🧮 Kullanılan DAX Formülleri (Bazı Örnekler)
DAX
Kopyala
Düzenle
ToplamSatis = SUM('SalesData'[Total Sales])

OrtalamaSatis = AVERAGE('SalesData'[Total Sales])

MusteriSayisi = DISTINCTCOUNT('SalesData'[Customer No])

HedefSatis = 2000000

🛠 Kullanılan Araçlar
Power BI Desktop

Excel (veri hazırlığı için)

Power Query (veri temizleme ve dönüştürme)

DAX (hesaplamalar)


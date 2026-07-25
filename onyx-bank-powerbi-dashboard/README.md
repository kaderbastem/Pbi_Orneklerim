# 💳 Zephyr Bank Customer & Fraud Analysis Dashboard

> Bu proje, **Onyx Data - DataDNA Challenge** kapsamında Power BI kullanılarak geliştirilmiştir.

## 📌 Proje Hakkında
Bu çalışmada dijital bankacılık işlemleri analiz edilerek müşteri davranışları, işlem hacmi, komisyon gelirleri ve fraud (şüpheli işlem) verileri etkileşimli dashboardlar aracılığıyla görselleştirilmiştir.
Dashboard, karar vericilerin bankanın genel performansını takip etmesini, riskli işlemleri analiz etmesini ve müşteri segmentlerini daha iyi anlamasını amaçlamaktadır.

# 🎯 Proje Amacı

Bu dashboard aşağıdaki iş sorularına cevap vermeyi amaçlamaktadır:

- Bankanın genel performansı nasıl?
- Komisyon gelirleri hangi müşteri segmentinden geliyor?
- Fraud oranı nedir?
- Hangi bölgelerde risk daha yüksek?
- Hangi yaş grubu daha fazla işlem yapıyor?
- En yüksek işlem hacmine sahip müşteriler kimler?
- Başarısız işlemlerin temel nedenleri nelerdir?
- En riskli cihaz ve işlem kanalı hangisi?

---

# 🗂️ Veri Modeli

Projede **Star Schema (Yıldız Şema)** veri modeli kullanılmıştır.

<img width="1010" height="681" alt="Image" src="https://github.com/user-attachments/assets/e0f89925-83a6-404f-9bd8-11a8bb726bc1" />
## Fact Tablosu

- Fact Transactions

## Dimension Tabloları

- Dim Customer
- Dim Transaction Type
- Dim Merchant Category
- Dim Date
- Dim Geography
- Dim Device

Star Schema sayesinde;

- Daha performanslı raporlama
- Daha hızlı DAX hesaplamaları
- Kolay filtreleme
- Daha okunabilir veri modeli

sağlanmıştır.

---

# 🧹 Veri Ön İşleme

Dashboard oluşturulmadan önce Power Query kullanılarak aşağıdaki veri hazırlama adımları uygulanmıştır.

- Veri tipleri düzenlendi.
- Tarih alanları uygun formata dönüştürüldü.
- Sayısal alanlar kontrol edildi.
- Gereksiz sütunlar kaldırıldı.
- Kolon isimleri düzenlendi.
- Kategorik veriler standartlaştırıldı.
- Tablolar arası ilişkiler oluşturuldu.
- Analiz için uygun veri modeli hazırlandı.

---

# 📈 DAX Çalışmaları

Projede birçok KPI ve hesaplama DAX kullanılarak oluşturulmuştur.

Bazı ölçüler;

- Toplam İşlem Hacmi
- Toplam Komisyon
- Fraud Tutarı
- Fraud Oranı
- Aktif Müşteri Sayısı
- Ortalama İşlem Tutarı
- Müşteri Başına Gelir
- Potansiyel Gelir Kaybı
- KYC Doğrulama Oranı
- Başarısız İşlem Oranı

---

# 📊 Dashboard Sayfaları

## 1️⃣ Executive Overview

Bu sayfa bankanın genel performansını özetlemektedir.

### KPI'lar

- Toplam İşlem Hacmi
- Fraud Oranı
- Aktif Müşteri
- Başarısız İşlem %
- Toplam Komisyon

### Cevaplanan İş Soruları

- Toplam işlem hacmi ne kadar?
- Fraud oranı nedir?
- Kaç aktif müşteri bulunmaktadır?
- Toplam komisyon geliri ne kadar?
- Komisyon gelirleri aylara göre nasıl değişmektedir?
- İşlem hacmi hangi kanallarda yoğunlaşmaktadır?
- Hangi sektörlerde daha fazla işlem gerçekleşmektedir?
- Başarısız işlemlerin en büyük nedeni nedir?

---

## 2️⃣ Risk Page

Bu sayfa fraud analizleri ve risk değerlendirmesi için hazırlanmıştır.

### KPI'lar

- Fraud Tutarı
- Fraud Oranı
- Potansiyel Gelir Kaybı
- Yurtdışı Riskli İşlem Tutarı
- Yurtiçi Riskli İşlem Tutarı

### Cevaplanan İş Soruları

- En riskli cihaz hangisidir?
- Fraud işlemleri en çok hangi sektörde görülmektedir?
- Riskli işlemler hangi bölgelerde yoğunlaşmaktadır?
- Potansiyel gelir kaybı ne kadardır?
- Yurtiçi ve yurtdışı riskli işlem dağılımı nasıldır?
- Toplam fraud işlemlerinin oranı nedir?

---

## 3️⃣ Customer Page

Bu sayfa müşteri davranışlarını analiz etmek amacıyla hazırlanmıştır.

### KPI'lar

- Aktif Müşteri
- Müşteri Başına Gelir
- Ortalama İşlem Tutarı
- KYC Doğrulama Oranı

### Cevaplanan İş Soruları

- En yüksek işlem hacmine sahip müşteriler kimlerdir?
- En fazla komisyon hangi müşteri segmentinden elde edilmektedir?
- En yüksek işlem hacmine sahip yaş grubu hangisidir?
- KYC doğrulama oranı nedir?
- Hangi müşteri segmentinde şüpheli işlem oranı daha yüksektir?
- İşlemlerin ne kadarı yurtiçi, ne kadarı yurtdışıdır?
- En yüksek gelir sağlayan müşteriler kimlerdir?

---

# 🛠️ Kullanılan Teknolojiler

- Power BI Desktop
- Power Query
- DAX
- Star Schema
- Data Modeling

---

# 📌 Dashboard Özellikleri

- 3 Sayfalı Dashboard
- Etkileşimli Slicer Yapısı
- Dinamik KPI Kartları
- Star Schema Veri Modeli
- DAX Measure Kullanımı
- Power Query ile Veri Temizleme
- İş Odaklı Dashboard Tasarımı

---

# 📷 Dashboard Görselleri

## Executive Overview

<img width="1218" height="686" alt="Image" src="https://github.com/user-attachments/assets/3fc3b512-41ec-4c4b-a398-cff2e35544c1" />

## Risk Page

<img width="1220" height="682" alt="Image" src="https://github.com/user-attachments/assets/7932de05-7898-49d4-baa1-a0dda0baa2bd" />

## Customer Page

<img width="1219" height="683" alt="Image" src="https://github.com/user-attachments/assets/fba2d3e2-3b82-419a-9a51-bb4cefef8b70" />

---

# 💡 Elde Edilen İçgörüler

- Business segmenti en yüksek komisyon gelirini üretmektedir.
- 35-44 yaş grubu en yüksek işlem hacmine sahiptir.
- İşlemlerin büyük bölümü yurtiçinde gerçekleşmektedir.
- Fraud kaynaklı başarısız işlemler diğer nedenlere göre daha yüksektir.
- Belirli cihazlar ve bölgelerde risk yoğunlaşmaktadır.
- Komisyon gelirleri aylara göre değişkenlik göstermektedir.

---

## 👨‍💻 Geliştirici

**Kader Bastem**

Power BI • Veri Analizi • Business Intelligence

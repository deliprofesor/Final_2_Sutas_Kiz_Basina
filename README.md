# Sütaş Satış Analizi Raporu - Power BI Projesi

<img width="1100" height="616" alt="image" src="https://github.com/user-attachments/assets/91649c3a-639f-48c3-9dd7-967672f663f3" />


## Proje Hakkında
Bu proje, Sütaş markasının satış verileri üzerinde kapsamlı bir analiz yapmak amacıyla hazırlanmıştır. Power BI kullanılarak oluşturulan raporda, farklı perspektiflerden (Özet, Müşteri, Kategori) satış performansı ve müşteri davranışları incelenmiştir.  

Projenin amacı, Sütaş ürünlerinin satış trendlerini anlamak, müşteri segmentasyonlarını analiz etmek ve karar alma süreçlerini destekleyecek görsel raporlar oluşturmaktır.

---

## Veri Setleri
Projede aşağıdaki veri tabloları kullanılmıştır:

- **Kullanıcılar (Users):** Müşteri bilgileri, demografik veriler
- **Adres (Address):** Kullanıcıların adres bilgileri ve şehirleri
- **Ürünler (Items):** Sütaş ürünleri ve kategorileri
- **Siparişler (Orders):** Siparişlerin genel bilgileri ve tarihleri
- **Sipariş Detayları (OrderDetail):** Siparişlerdeki ürün adet ve fiyat bilgileri
- **Bölgeler:** Türkiye'deki bölgeler ve şehirler bilgisi (harita görselleştirmeleri için)

---

## Yapılan Veri Hazırlıkları
- Tabloların isimlendirilmesi ve veri türlerinin düzeltilmesi
- Tarih ve saat ayrıştırmaları yapılması (sipariş tarihinden saat çıkarılması)
- Koşullu sütunlar eklenmesi (Hafta içi/Hafta sonu, yaş grupları, cinsiyet)
- Kullanıcı isimlerinin Ad ve Soyad olarak ayrılması
- Gizlenmesi gereken hassas sütunların gizlenmesi
- Tablolar arası ilişkilendirmelerin kurulması

---

## Rapor Sayfaları
1. **Giriş Sayfası:** Proje bilgileri ve sayfa yönlendirmeleri  
2. **Özet Sayfa:**  
   - Haftasonu ve haftaiçi satış grafiği  
   - Bölgelere göre toplam satış adeti grafiği  
   - Saatlik satış tutarının grafiği  
   - Satış adetleri, toplam ciro, müşteri sayısı gibi önemli KPI kartları  
3. **Müşteri Perspektifi:**  
   - Tekil, kadın ve erkek müşteri sayıları  
   - Bölgelere göre müşteri sayısı  
   - İstanbul’daki en çok alışveriş yapan ilk 10 müşteri tablosu  
   - Yaş grubuna göre satış grafiği  
4. **Kategori Perspektifi:**  
   - İstanbul’da yaşayan genç müşterilerin toplam cirosu kategori bazında (ağaç haritası)

---

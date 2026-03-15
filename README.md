# 📊 İstatistiksel Hesaplama Portfolyosu

Bu repo, farklı veri türleri için geliştirilmiş istatistiksel analiz araçlarını içerir.

---

## 1️⃣ Sınıflanmamış Seri Hesaplayıcı
**Dosya:** `index.html` (Ana dizin)

Bu araç, ham veri listeleri üzerinde işlem yapar. Herhangi bir gruplandırma olmayan basit seriler için uygundur.

* **Veri Girişi:** `10, 15, 20, 25...` şeklinde düz liste.
* **Özellikler:** Standart sapma, varyans ve merkezi eğilim ölçülerini doğrudan ham veri üzerinden hesaplar.

Canlı Uygulamayı Aç: https://hmeyrakrklnc.github.io/Istatistik-Hesaplayici/

---

## 2️⃣ Sınıflanmış (Gruplandırılmış) Seri Hesaplayıcı 
**Klasör:** `/siniflanmis-seri`

Bu araç, belirli aralıklara ve frekanslara sahip tablolaştırılmış veriler için tasarlanmıştır.

* **Veri Girişi:** `AltLimit ÜstLimit Frekans` (Örn: `10 20 5`)
* **Hesaplama Mantığı:** Sınıf orta noktaları ($m_i$) ve frekans ağırlıklı formüller kullanılır.
* **Öne Çıkan Özellik:** Çoklu mod (multimodal) desteği ve doğrusal interpolasyon ile hassas medyan hesabı yapar.

Canlı Uygulamayı Aç: https://hmeyrakrklnc.github.io/Istatistik-Hesaplayici/siniflanmis-seri/

---

## 🚀 Nasıl Kullanılır?

1. Kullanmak istediğiniz aracın sayfasına gidin.
2. Verilerinizi belirtilen formatta kutucuğa yapıştırın.
3. **Hesapla** butonuna basarak sonuçları 4 basamak hassasiyetle görüntüleyin.

## 🛠 Teknik Detaylar
* **Dil:** Saf JavaScript (Vanilla JS)
* **Arayüz:** Responsive HTML5 & CSS3
* **Lisans:** Eğitim amaçlı açık kaynak.

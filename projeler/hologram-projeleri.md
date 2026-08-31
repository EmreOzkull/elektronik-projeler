# Hologram Projeleri

**Yıl:** 2021

İki ayrı hologram çalışması: biri **POV** (persistence of vision) prensibiyle dönen bir
donanım, diğeri kamera görüntüsünü hologram prizmasına hazırlayan bir yazılım hattı.

---

## 1. Hologram Clock

Devre, yüksek hızda dönen bir motora sabitlenmiştir. Motor döndükçe sıralı olarak
yerleştirilen **LED'lerin ışık şiddeti değiştirilerek**, dönme ekseninde belirlenen yazının
havada asılıymış gibi görünmesi sağlanır.

**Etiketler:** `POV LED` · `Motor Senkronizasyonu` · `Gömülü Yazılım`

---

## 2. Eşzamanlı Hologram

**Python** dilinde, **OpenCV** kütüphanesi temel alınarak hazırlanmıştır.

Çalışma adımları:

1. Kameradan gelen görüntü çeşitli fonksiyonlardan geçirilir
2. **Arka plan kaldırılır**
3. Videodaki nesne hologram için uygun konuma alınır
4. Hesaplamalara göre nesnenin görüntüsü yeniden üretilerek ekrana yerleştirilir
5. Görüntü **hologram prizmasına** uygun hâle getirilir

İşlem sonucunda prizmaya aktarılan görüntü hologram etkisini oluşturur.

**Etiketler:** `Python` · `OpenCV` · `Görüntü İşleme` · `Hologram Prizması`

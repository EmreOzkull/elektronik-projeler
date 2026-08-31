# Görüntü İşleme Destekli Otonom Savunma Sistemi

**Yıl:** 2023 · **Bağlam:** KTO Karatay Üniversitesi bitirme projesi

## Amaç

Görüntü işleme ile önceden tanıtılmış hedefleri sınıflandırarak yalnızca **düşman** olarak
etiketlenen hedefe yönelen, sabit konumlu bir gözetleme kulesi.

## Çalışma prensibi

1. Kameradan gelen görüntü, Python tarafındaki görüntü işleme algoritmalarıyla işlenir.
2. Sistem **düşman asker / dost asker / sivil** ayrımını yapar.
3. Sınıflandırma sonucu **UART** haberleşme protokolü ile mikrodenetleyiciye aktarılır.
4. Mikrodenetleyici, gelen veriye göre iki step motoru sürerek namlu ucunu X ve Y
   ekseninde hedefe çevirir.

Kule sabittir; hareket kabiliyeti yalnızca namlu ucundadır.

## Donanım

- **PIC18F46K22** mikrodenetleyici
- X ve Y ekseni için 2 adet step motor
- Kamera + görüntü işleme çalıştıran bilgisayar

## Projedeki rolüm

- Elektronik devre tasarımı
- Görüntü işlemeden gelen verilerin UART ile mikrodenetleyiciye aktarılması
- Gelen veriye göre motor hareketlerinin sürülmesi

## Etiketler

`PIC18F46K22` · `Python` · `Görüntü İşleme` · `UART` · `Step Motor` · `Savunma`

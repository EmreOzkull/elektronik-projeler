# 6 Eksen Hareket Ezberleyen Robot Kol

**Yıl:** 2023 · **Bağlam:** KTO Karatay Üniversitesi bitirme projesi

## Amaç

Operatörün joystick ile yaptırdığı hareketleri kaydedip, istenildiği anda tek bir buton
darbesiyle birebir tekrarlayabilen 6 serbestlik dereceli bir robot kol.

## Donanım

| Bileşen | Adet | Not |
|:--|:--:|:--|
| PIC18F46K22 mikrodenetleyici | 1 | Sistemin tamamını sürer |
| Step motor | 5 | Eksen hareketleri |
| Servo motor | 1 | Toplam 6 eksen |
| Joystick | 3 | Eksenler bağımsız sürülebilir |
| Buton | 5 | Hareket kaydet / tekrarla |

## Çalışma prensibi

Robot 3 joystick üzerinden bağımsız olarak hareket ettirilir. Kola entegre 5 buton, yapılan
hareket dizisini **ezberler**; istenilen bir zamanda ilgili butona basıldığında kaydedilen
hareket sırayla tekrar edilir.

Denetleyici **CCS C** ile programlanmıştır.

## Projedeki rolüm

- Devre kartı tasarımı ve testleri
- Gömülü sistem yazılımı ve uygulaması

## Etiketler

`PIC18F46K22` · `CCS C` · `Step Motor` · `Servo` · `PCB Tasarımı` · `Gömülü Yazılım`

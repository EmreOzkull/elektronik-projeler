# DotMatrix Elektronik Kum Saati

**Yıl:** 2022

## Amaç

Klasik kum saatinin dijital karşılığı: dönen bir mekanizmayla kendini ters çevirip
sayımı yeniden başlatan, LED matris üzerinde analog görünümlü bir zamanlayıcı.

## Donanım

- **PIC18F46K22** mikrodenetleyici
- 2 adet **8×8 nokta matris** (dot matrix) gösterge
- Ters çevirme mekanizması için servo motor

## Çalışma prensibi

Sistem iki modda çalışır: **60 saniye** ve **60 dakika**.

Otonom modda süre tamamlandığında servo motor saati **180 derece** döndürerek ters çevirir
ve sayım yeniden başlar. Dijital LED'lere kum saatinden esinlenen bir **analog görünüm
efekti** verilmiştir — taneler akıyormuş izlenimi matris üzerinde oluşturulur.

## Etiketler

`PIC18F46K22` · `Dot Matrix` · `Servo` · `Gömülü Yazılım`

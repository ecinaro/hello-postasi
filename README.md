# Hello Postası

"hello" yazınca dünyanın dört bir yanından cevap gelen küçük bir web uygulaması.

- Her `hello` için 49 dilin içinden 6 tanesi rastgele cevap verir.
- Her kartta selamın kendi yazısı, okunuşu, dilin Türkçe adı ve dil kodu var.
- `merhaba`, `selam`, `hola`, `konnichiwa` gibi başka dillerdeki selamları da tanır.
- Hoparlör düğmesi selamı tarayıcının sesiyle okur.
- Kaç dil keşfettiğini sayar.

## Çalıştırma

Kurulum yok. `index.html` dosyasını tarayıcıda açman yeterli.

## Yapı

Tek dosya: HTML, CSS ve JavaScript `index.html` içinde. Sunucu ya da kütüphane yok, sadece yazı tipleri Google Fonts'tan yüklenir. Yeni dil eklemek için dosyadaki `LANGS` listesine bir satır eklemek yeter.
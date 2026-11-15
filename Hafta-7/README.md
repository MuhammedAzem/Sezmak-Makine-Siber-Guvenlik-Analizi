# Hafta 7 – AI Safety Challenge

## Proje Bilgileri
**Makine:** Sezmak Rotary Dolum, Kesme ve Kapatma Makinesi

**Konu:** Yapay Zekâ Destekli Kalite Kontrol ve Makine Emniyeti

## Çalışmanın Amacı
Bu çalışmada Sezmak Rotary Dolum, Kesme ve Kapatma Makinesi için varsayımsal bir yapay zekâ destekli görsel kalite kontrol sistemi değerlendirilmiştir. Yapay zekâ kararlarının hatalı olması durumunda güvenli davranışların nasıl sağlanacağı incelenmiştir.

## Yapılan Çalışmalar
- Yapay zekâ modelinin kusurlu ürünü hatalı biçimde kabul etmesi senaryosu incelenmiştir.
- Kamera verisinin bozulması veya manipüle edilmesi durumunda alınacak önlemler belirlenmiştir.
- Modelin güven skorunun düşmesi durumunda uygulanacak karar mekanizması tasarlanmıştır.
- Fail-safe, human override, monitoring, confidence threshold ve fallback yaklaşımları değerlendirilmiştir.
- Yapay zekâ destekli kalite kontrol ile bağımsız makine emniyet fonksiyonları arasındaki fark açıklanmıştır.

## Önerilen Güvenlik Yaklaşımı
Yapay zekâ kararları tek başına makine emniyetini garanti etmez. Şüpheli ürünler ayrılmalı, gerekli durumlarda operatör onayı alınmalı ve emniyet fonksiyonları yapay zekâ sisteminden bağımsız çalışmalıdır.

Örnek güven eşiği %90 olarak belirlenmiştir. Bu değer gerçek sistem testleriyle doğrulanmadan kullanılmamalıdır.

## Hafta 7 Dosyaları
- Paketleme-7.pdf

## Sonuç
Yapay zekâ destekli kalite kontrol sistemlerinde hatalı sınıflandırma, manipüle edilmiş veriler ve düşük güven skorları için önceden tanımlanmış güvenli davranışlar bulunmalıdır.

Bu çalışma eğitim amaçlı bir tasarım senaryosudur; Sezmak makinesinde yapay zekâ sisteminin mevcut olduğu anlamına gelmez.

**Çıktı:** AI Fail-Safe Decision – Evidence Pack EP 03 + EP 15

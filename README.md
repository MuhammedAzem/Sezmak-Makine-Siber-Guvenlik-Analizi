# Sezmak Makine – Endüstriyel Siber Güvenlik ve Makine Emniyeti Analizi

## Proje Hakkında

Bu proje kapsamında **Sezmak Rotary Dolum, Kesme ve Kapatma Makinesi**, endüstriyel siber güvenlik ve makine emniyeti açısından değerlendirilmiştir.

Çalışmanın temel amacı; endüstriyel otomasyon sistemlerinde ortaya çıkabilecek siber güvenlik tehditlerini belirlemek, bu tehditlerin üretim sürekliliğine ve çalışan güvenliğine olası etkilerini incelemek ve riskleri azaltmaya yönelik güvenlik önlemleri geliştirmektir.

Proje, **7 haftalık laboratuvar çalışması ve bir SWOT analizinden** oluşmaktadır.

## İncelenen Makine

**Üretici:** Sezmak Makina

**Makine:** Rotary Dolum, Kesme ve Kapatma Makinesi

**Temel İşlev:** Ürünlerin kaplara doldurulması, ambalaj folyosunun kesilmesi ve kapların kapatılması işlemlerinin gerçekleştirilmesi.

## Haftalık Laboratuvar Çalışmaları

| Hafta | Konu | Laboratuvar Föyü |
|---|---|---|
| 1 | Safety Architecture – Emniyet Mimarisi | [Hafta 1](Hafta-1/Paketleme-1-YENI.pdf) |
| 2 | IEC 62443 – Zone & Conduit Analizi | [Hafta 2](Hafta-2/Paketleme-2.pdf) |
| 3 | Threat & Risk – Risk Matrisi | [Hafta 3](Hafta-3/Paketleme-3-DUZELTILMIS.pdf) |
| 4 | Secure Remote Access – Güvenli Uzaktan Erişim | [Hafta 4](Hafta-4/Paketleme-4.pdf) |
| 5 | SBOM / CVE / Patch – Güvenlik Açığı ve Yama Yönetimi | [Hafta 5](Hafta-5/Paketleme-5.pdf) |
| 6 | CRA Incident Simulation – Siber Olay Müdahalesi | [Hafta 6](Hafta-6/Paketleme-6.pdf) |
| 7 | AI Safety Challenge – Yapay Zekâ ve Makine Emniyeti | [Hafta 7](Hafta-7/Paketleme-7.pdf) |

Her haftanın klasöründe ilgili laboratuvar föyü ve çalışmanın amacını, kapsamını ve sonuçlarını açıklayan bir `README.md` dosyası bulunmaktadır.

## SWOT Analizi

Yedi haftalık çalışmaların ardından makinenin endüstriyel siber güvenlik açısından SWOT analizi hazırlanmıştır.

Analizde aşağıdaki dört başlık ele alınmıştır:

- **Strengths (Güçlü Yönler):** Üretim sürecinin bütünleşik yapısı ve güvenlik kontrolleri için değerlendirilebilecek özellikler.
- **Weaknesses (Zayıf Yönler):** Olası güvenlik açıkları, erişim kontrolü ve bakım süreçlerindeki riskler.
- **Opportunities (Fırsatlar):** IEC 62443, ağ segmentasyonu, güvenli uzaktan erişim ve güvenlik iyileştirmeleri.
- **Threats (Tehditler):** Yetkisiz erişim, kötü amaçlı yazılımlar, kontrol sistemlerinin manipülasyonu ve üretim kesintileri.

**[SWOT Analizi PDF Dosyası](SWOT-Analizi/Sezmak-Makine-SWOT-Analizi.pdf)**

## Kullanılan Yaklaşımlar ve Kavramlar

- Endüstriyel Kontrol Sistemleri (ICS/OT)
- PLC ve HMI güvenliği
- Fonksiyonel emniyet ve fail-safe yaklaşımı
- IEC 62443 güvenlik bölgeleri
- Tehdit modelleme ve risk değerlendirmesi
- VPN, MFA ve güvenli uzaktan erişim
- SBOM, CVE, CVSS ve yama yönetimi
- Siber olay müdahalesi ve CRA
- Yapay zekâ destekli kalite kontrol güvenliği
- SWOT analizi

## Projenin Sonucu

Bu çalışmada endüstriyel makinelerin siber güvenliği ile fiziksel emniyetinin birlikte değerlendirilmesi gerektiği ortaya konulmuştur.

Özellikle yetkisiz erişim, yazılım güvenlik açıkları, kontrol sistemlerindeki olası değişiklikler ve yetersiz olay müdahalesi süreçlerinin üretim güvenliği üzerinde risk oluşturabileceği değerlendirilmiştir.

Bu risklerin azaltılması için erişim kontrolü, ağ segmentasyonu, düzenli risk analizi, kontrollü güncelleme süreçleri ve emniyet fonksiyonlarının bağımsızlığı gibi önlemler önerilmiştir.

## Çalışmanın Kapsamı

Bu proje **eğitim amaçlı bir siber güvenlik ve makine emniyeti analizidir**.

İncelenen siber saldırı senaryoları, kontrol sistemi bileşenleri ve önerilen güvenlik mimarileri varsayımsal değerlendirmeler içerebilir. Bunlar, Sezmak makinesinde doğrulanmış güvenlik açıkları veya mevcut donanım özellikleri olarak yorumlanmamalıdır.

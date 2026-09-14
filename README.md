# DEYE / Analys

**Hibrit inverter izleme, tanı ve teknik servis çalışma alanı.**  
**A workspace for hybrid inverter monitoring, diagnostics and technical service.**

[Türkçe](#türkçe) · [English](#english)

## Türkçe

DEYE / Analys; canlı enerji verilerini, cihaz parametrelerini, servis testlerini ve oturum kayıtlarını aynı arayüzde toplar. Tezgâh ve saha çalışmalarında cihaz davranışını incelemek, ölçümleri kaydetmek ve servis raporu oluşturmak için geliştirilir.

| Alan | Özellikler |
| --- | --- |
| İZLEME | PV, yük, batarya ve şebeke güç kartları; Batarya doluluk oranı ve çalışma durumu; Doğrulanmış ve beklenen akış yönlerinin ayrımı |
| ANALİZ | 1, 5, 15 ve 30 dakika veya tüm oturum; Özel sinyal seçimi, duraklatma ve otomatik ölçek; Kaynak geçişlerinde güç eğilimlerinin karşılaştırılması |
| ÖLÇÜMLER | L1, L2 ve L3 gerilimleri; Faz başına yük gücü; Batarya, DC ve AC sıcaklıkları |
| TANI | Aktif hata ve uyarı sayıları; Kalıcı olay kayıtları; Arıza anındaki ölçümlerle teknik değerlendirme |
| AYARLAR | Şarj/deşarj akımı ve batarya kapasitesi; Düşük, kapanma ve yeniden başlama SOC eşikleri; Batarya, çalışma, şebeke ve jeneratör ayar grupları |
| ZAMAN PLANI | Altı ayrı zaman periyodu; Periyot bazında güç ve SOC değerleri; Kapalı, şebeke, jeneratör veya birlikte şarj kaynağı |
| SERVİS ERİŞİMİ | Süreli servis erişimi; Değişikliklerin toplu incelemesi ve ikinci onay; Yazma sonrası geri okuma ve doğrulama akışı |
| SERVİS TESTLERİ | Doğrulanmış fan testi komutu; Jeneratör rölesi ve ekran testleri için doğrulama durumu; Lityum arayüzü, LCD tuşları ve röle izleme tanı kartları |
| FONKSİYON TESTLERİ | PV üretim, PV→yük ve PV→batarya senaryoları; Şebeke→batarya, batarya→yük ve şebeke→yük senaryoları; PV→şebeke satış ve sıfır ihracat kontrolleri |
| KAYIT VE RAPOR | Manuel ölçüm, birim ve teknisyen notu; Oturum süresi, örnek sayısı, hata ve test özeti; Müşteri Excel’i, servis test raporu ve kapsamlı servis telemetrisi |

### Tanıtım sayfası

`index.html`, Türkçe / English dil düğmeli, mobil uyumlu tanıtım sayfasıdır. Dil tercihi tarayıcıda saklanır. Ekran görüntüleri yüklendiğinde tıklanarak büyütülebilir; görsellerin içindeki orijinal arayüz metinleri çevrilmez.

Bu depo yalnızca tanıtım sayfasını ve tanıtım materyallerini içerir. İnverter uygulamasının kaynak kodu, haberleşme implementasyonu, servis PIN'i ve çalıştırılabilir uygulaması dahil değildir.

**Mevcut durum:** Sayfa ve iki dilde içerik hazırlanmıştır. On ekran görüntüsünün GitHub'a aktarımı ve kullanıcının göndereceği üç ek ekranın yerleştirilmesi beklenmektedir. Bu commit ile canlı site yayına alınmamıştır.

Görsel dosya eşleştirmeleri: [Ekran görüntüsü listesi](assets/screenshots/README.md).

### Destek kapsamı

İçerik, paylaşılan TommaTech TRIO HYBRID LV 20.0F ekranlarına dayanır. Parametre yazma ve servis komutları cihaz modeli, firmware, profil ve doğrulama durumuna bağlıdır. Örnek servis ekranında fan testi doğrulanmıştır; diğer kartlar aynı doğrulama durumunda değildir. Fonksiyon testleri ekrandaki ön koşullar ve ölçümlerle değerlendirilir.

## English

DEYE / Analys combines live energy data, device parameters, service tests and session records in one interface. It supports bench and field workflows for inspecting device behavior, recording measurements and preparing service reports.

| Area | Features |
| --- | --- |
| MONITORING | PV, load, battery and grid power cards; Battery state of charge and operating status; Distinct confirmed and pending flow directions |
| ANALYSIS | 1, 5, 15 and 30 minutes or the full session; Custom signal selection, pause and automatic scaling; Power trend comparison during source transitions |
| MEASUREMENTS | L1, L2 and L3 voltages; Per-phase load power; Battery, DC and AC temperatures |
| DIAGNOSTICS | Active fault and warning counts; Persistent event records; Technical assessment with fault-time measurements |
| SETTINGS | Charge/discharge current and battery capacity; Low, shutdown and restart SOC thresholds; Battery, operating, grid and generator setting groups |
| SCHEDULING | Six individual time periods; Power and SOC values per period; Off, grid, generator or combined charging source |
| SERVICE ACCESS | Time-limited service access; Change review and second confirmation; Post-write readback and verification workflow |
| SERVICE TESTS | Verified fan test command; Verification status for generator relay and display tests; Diagnostic cards for lithium interface, LCD keys and relay monitoring |
| FUNCTION TESTS | PV generation, PV-to-load and PV-to-battery scenarios; Grid-to-battery, battery-to-load and grid-to-load scenarios; PV export and zero-export checks |
| RECORDS AND REPORTS | Manual measurements, units and technician notes; Session duration, sample count, faults and test summary; Customer Excel, service test report and comprehensive service telemetry |

### Product showcase

`index.html` is a responsive showcase with Turkish / English buttons and a saved language preference. Uploaded screenshots can be enlarged; original interface text inside screenshots is not translated.

This repository contains presentation materials only. It does not include the inverter application's source code, communication implementation, service PIN or application executable.

**Current status:** The page and bilingual content are committed. Uploading the ten screenshots and placing three additional screens from the user remain outstanding. This commit does not deploy a live website.

See the [screenshot manifest](assets/screenshots/README.md).

### Support scope

Content is based on the supplied TommaTech TRIO HYBRID LV 20.0F screenshots. Parameter writing and service commands depend on device model, firmware, profile and verification status. The sample service screen shows a verified fan test; other cards do not have the same verification status. Function tests are evaluated against on-screen preconditions and measurements.

---

Proje geliştirme / Project development: **Deniz Türker Tuncer**

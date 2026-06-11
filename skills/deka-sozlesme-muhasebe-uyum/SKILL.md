---
name: deka-sozlesme-muhasebe-uyum
description: >
  Sözleşmenin finansal unsurlarını muhasebe ile kontrol et. 
  Fiyatlandırma, ödeme şartları, KDV, vergi uyumluluk.
argument-hint: "[Sözleşme fiyat maddeleri / muhasebe politikası]"
---

# DEKA SÖZLEŞME-MUHASEBEYÖNETİMİ UYUMLULUK

## Fiyatlandırma Türleri

| Tip | Örnek | Muhasebe İşlemi |
|---|---|---|
| **Sabit Fiyat** | 100.000 TRY toplamı | Teslimat'da revenue tanı |
| **Zaman Maliyeti** | 5.000 TRY/ay × 6 ay | Aylık revenue (SaaS) |
| **Aşama Ödemeli** | Ön 50%, Teslimat 50% | Aşama tamamlandığında |

## Ödeme Şartları

- **Net 30:** 30 gün ödeme süresi
- **Net 60:** 60 gün ödeme süresi
- **2/10 Net 30:** İlk 10 gün %2 iskonto, ya da net 30

## Vergi Uyumluluk

- KDV Dahili/Harici kontrolü
- Kurumlar Vergisi
- Withholding Tax (varsa)

---

## Entegrasyon

- deka-sozlesme-inceleme → Fiyat maddeleri
- Muhasebe sistemi → Revenue tanı

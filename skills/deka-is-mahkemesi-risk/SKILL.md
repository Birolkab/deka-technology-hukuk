---
name: deka-is-mahkemesi-risk
description: >
  Çalışan davası riski değerlendirmesi. Tazminat hesaplama (otomatik), 
  arabuluculuk prosedürü, dava maliyeti tahmini.
argument-hint: "[Çalışan bilgisi / fesih sebepleri]"
---

# DEKA İŞ MAHKEMESİ RİSK

## Tazminat Hesaplama

```
Tazminat = Brüt Ücret × Gün Sayısı ÷ 360

Örnek:
- Brüt Ücret: 15.000 TRY
- Çalışma Süresi: 2 yıl (730 gün)
- Tazminat = 15.000 × 730 ÷ 360 = 30.417 TRY

NOT: Tazminat dava süresi de hesaplanır (dava 1-2 yıl)
→ İşveren 30K + Avukat (10K) + Faiz = 45-50K TRY harcama
```

## Risk Faktörleri

| Durum | Risk | Tazminat |
|---|---|---|
| **Yazılı Sözleşme** | Düşük (5%) | Tartışmaya açık |
| **Yazılı Olmayan** | Yüksek (80%) | Kesin ödeme |
| **Sebepsiz Fesih** | Çok Yüksek (95%) | Tam tutarı + faiz |
| **Kötü Muamele** | Kritik (100%) | 2-3 katı tazminat |

## Arabuluculuk

- **Zorunlu:** Fesih bildirimi sonrası 30 gün arabuluculuk
- **Başarısız:** Dava açılabilir
- **Başarılı:** Anlaşma = dava yok

---

## Entegrasyon

- deka-is-sozlesme-yazici → Sözleşme kontrolü
- deka-sgk-bildirimi → Bildirimi kontrol

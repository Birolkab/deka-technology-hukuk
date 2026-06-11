---
name: deka-sozlesme-inceleme
description: >
  Deka Technology sözleşmelerini inceleme. MSA, SOW, NDA, SLA analizi. 
  GREEN (imzala) / YELLOW (danışman gözüne) / RED (avukat incelemesi) sınıflandırma.
argument-hint: "[Sözleşme PDF/DOCX dosyası]"
---

# DEKA SÖZLEŞME İncelemesi

## Kontrol Matrisi

| Unsur | GREEN | YELLOW | RED |
|---|---|---|---|
| **IP Sahipliği** | Açık (müşteri sahibi) | Muğlak | Deka sahibi (risk!) |
| **Fiyatlandırma** | Sabit + Teslimat | Değişken + Test | Belirsiz |
| **Ceza Maddeleri** | Makul (max 1-2 ay) | Orta | Açık uçlu ceza |
| **Teslimat Tarihi** | Gerçekçi + Tampon | Dar | Geçmiş tarih |
| **SLA Garantisi** | 99% uptime | 95% | 99.9% (gerçekçi değil) |
| **Münasebet Süresi** | 30 gün (test) | 14 gün | 7 gün (yetersiz) |
| **Gizlilik Madde** | Karşılıklı + Süreli | Tek taraflı | Belirsiz |

## Çıktı Format

```json
{
  "sözlesme": "Anadolu Efes Software - 2024",
  "taraf": "Deka Technology vs. Anadolu Efes",
  "sonuc": "YELLOW",
  "riskler": [
    "IP sahipliği muğlak",
    "SLA 99.9% gerçekçi değil"
  ],
  "tavsiye": "Danışman incelemesi gerekli"
}
```

## Entegrasyon

- deka-sozlesme-risk-analizi → Risk puanlaması
- deka-sozlesme-template → Şablon karşılaştırma

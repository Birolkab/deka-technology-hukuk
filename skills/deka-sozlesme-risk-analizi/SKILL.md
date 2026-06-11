---
name: deka-sozlesme-risk-analizi
description: >
  Sözleşme risklerini parasal, yasal ve işletme açısından analiz et. 
  Risk puanı (1-10), tavsiye (ödeme mi, dilekçe mi, yeniden müzakere mi).
argument-hint: "[Sözleşme inceleme sonuçları / risk faktörleri]"
---

# DEKA SÖZLEŞME RİSK ANALİZİ

## Risk Türleri

### Parasal Risk
- Ceza maddeleri (maksimum kayıp)
- Ödeme gecikme faizi
- İade koşulları

### Yasal Risk
- IP sahipliği anlaşmazlığı
- Gizlilik ihlali
- İş mahkemesi davası potansiyeli

### İşletme Riski
- Scope creep (kapsamın sınırsız genişlemesi)
- Müşteri ödeme riski
- Teslimat tarihi gerçekçiliği

## Hesaplama

```
Risk Puanı = (Parasal_Risk × 0.4) + (Yasal_Risk × 0.4) + (İşletme_Riski × 0.2)

Çıktı:
1-3: LOW (imzala)
4-6: MEDIUM (danışman gözüne)
7-10: HIGH (avukat incelemesi)
```

---

## Entegrasyon

- deka-sozlesme-inceleme → Risk input
- deka-sozlesme-karsilastirma → Tarihsel risk karşılaştırma

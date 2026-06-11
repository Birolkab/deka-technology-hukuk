---
name: deka-sozlesme-topluluk-analiz
description: >
  Tüm aktif sözleşmeleri tarayıp toplam risk raporu. Hangi müşteri en riskli? 
  Toplu güncelleme önerileri. Dashboard: Müşteri × Risk Matrix.
argument-hint: "[Tüm sözleşme portföyü]"
---

# DEKA SÖZLEŞME TOPLULUK ANALİZİ

## Portfolio Dashboard

```
Müşteri              | Risk | Durum  | Tavsiye
─────────────────────┼──────┼────────┼─────────
Anadolu Efes         | 7/10 | ACTIVE | Yeniden müzakere
Honda Marine         | 4/10 | ACTIVE | Devam
Hayat Holding        | 8/10 | ACTIVE | Acil yenileme
Kastamonu            | 3/10 | ACTIVE | İyi
Anadolu Motor        | 5/10 | ACTIVE | 6 ay sonra review
─────────────────────┴──────┴────────┴─────────
ORTALAMA RISK:       5.4/10
KRITIK SÖZLEŞMELER:  2 (Hayat, Anadolu Efes)
```

## Toplu Eylemler

- Müşterilere standart şablon öner
- Güncelleme tarihi ortaklaştır
- Risk seviyeleri grafiği

---

## Entegrasyon

- deka-sozlesme-inceleme × N → Tüm sözleşmeler
- deka-sozlesme-risk-analizi × N → Risk puanları

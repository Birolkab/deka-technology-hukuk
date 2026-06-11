---
name: deka-sozlesme-karsilastirma
description: >
  Geçmiş sözleşmeleri yeni sözleşme ile karşılaştır. Tutarsızlıkları flag et. 
  Önceki "iyi" şartları tekrar öneri (önceki müşteriler bunu kabul etmiş).
argument-hint: "[Yeni sözleşme / karşılaştırılacak eski sözleşmeler]"
---

# DEKA SÖZLEŞME KARŞILAŞTIRMASI

## Workflow

1. Yeni sözleşmeyi oku
2. Geçmiş sözleşmeleri tara
3. Madde-madde karşılaştır
4. Tutarsızlıkları flag et
5. "Daha iyi" şartları öner

## Çıktı Örneği

```
Anadolu Efes Sözleşme (Yeni)
vs.
Honda Marine Sözleşme (2023 - Başarılı)

❌ TUTARSIZLIK:
- Honda: IP Sahipliği "Müşteri"
- Anadolu: "Shared" (muğlak!)
→ ÖNER: Honda şartını kabul et

✅ AVANTAJ:
- Anadolu: Ödeme "Net 30" (Honda: Net 60)
→ TEYIT: Bunu saklı tut
```

---

## Entegrasyon

- deka-sozlesme-inceleme → Input
- deka-sozlesme-risk-analizi → Risk karşılaştırma

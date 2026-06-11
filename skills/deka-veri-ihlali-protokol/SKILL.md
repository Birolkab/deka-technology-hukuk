---
name: deka-veri-ihlali-protokol
description: >
  Veri sızması / İhlal Protokolü. Kimdkötü sızsa ne olur? Kime bildir? 
  Kaç saat içinde? Dokümantasyon (KVKK m.69).
argument-hint: "[İhlal türü / Etkilenen veri sayısı]"
---

# DEKA VERİ İHLALİ PROTOKOLÜ

## ADIM 1: SIZZINTI TESPITI (0-2 saat)

Bir çalışan rapor eder:
- "Müşteri dosyası yanlış folder'a koydum"
- "Bilgisayar çalındı"
- "Hackleme yapıldı"

**Yapılacak:**
- [ ] Teknik ekip derhal yetkisiz erişimi kes
- [ ] Etkilenen verileri belirle (kaç kişi?)
- [ ] Sızdı'rısı (Confidentiality?) kontrol et
- [ ] İncelemeler başlat

---

## ADIM 2: KİMİ BİLDİR (24 saat içinde)

### KVKK'ya Bildir
- URL: https://www.kvkk.gov.tr
- İlet: Sızıntı detayları + Alınan önlemler
- **CEZA:** 24 saat geçerse ceza 250K-4.8M TRY!

### Müşteri'ye Bildir
- E-posta + Telefon (Aynı gün)
- "Anadolu Efes müşteri verilerinizde sızıntı tespit ettik"
- Alınan önlemler
- Sizdırılı veriler (ad, email, vb)

### Zayıf Veri Sahibine Bildir
- Etkilenen müşteri (Anadolu Efes'in müşterisi)
- "E-postanız, cep telefonunuz sızıntıya maruz kaldı"
- Kimlik hırsızlığı uyarısı

---

## ADIM 3: DOKÜMANTASYON (KVKK Denetimi için)

```
İHLAL RAPORU

Tarih: 2024-06-11
Saat: 14:30
Sızıntı Nedeni: Yanlış folder paylaşımı
Etkilenen Veri: 5.000 müşteri e-postası
Etkilenen Kişi: 5.000
Sızdırma Süresi: 2 saat
Alınan Önlemler:
  - Klasör erişimi kapatıldı
  - Tüm klasörler şifrelenди
  - Personel eğitimi yapıldı
KVKK Bildirim: 11:45'te yapıldı (24 saat öncesi)
Müşteri Bildirim: 11:48'de yapıldı
```

---

## ADIM 4: TAZMİNAT & AYIRMA

- Etkilenen kişiler: Ücretsiz kimlik hırsızlığı sigortası (12 ay)
- Müşteri: Tazminat teklifi (iş kaybı, imaj hasarı)

---

## Entegrasyon

- deka-veri-guvenligi-checklist → Sızıntı yapma (prevention)
- KVKK.gov.tr → Resmi bildirim

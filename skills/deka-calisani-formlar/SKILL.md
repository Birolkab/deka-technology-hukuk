---
name: deka-calisani-formlar
description: >
  Çalışan formları generator. İş başvurusu, Veri Formu (KVKK), Gizlilik, 
  NDA, Çıkış Formu. Tüm formlar KVKK uyumlu.
argument-hint: "[Form türü: Başvuru / Veri / Gizlilik / NDA / Çıkış]"
---

# DEKA ÇALIŞAN FORMLAR

## 1. İŞ BAŞVURUSU FORMU

```
Ad Soyad: _________________
E-posta: _________________
Telefon: _________________
Pozisyon: _________________
Başlangıç Tarihi: _________________
```

## 2. ÇALIŞAN VERİ FORMU (KVKK)

```
Ad Soyad: (Zorunlu)
Kimlik No: (Zorunlu, SGK için)
Doğum Tarihi: (Zorunlu)
Adres: (Zorunlu, maaş postasl için)
Banka Hesabı: (Zorunlu, maaş transferi)

KVKK ONAY:
☐ Veri işlemeyi kabul ediyorum
☐ Pazarlama e-postası göndermesine izin veriyorum
```

## 3. GİZLİLİK SÖZLEŞMESI

```
Bu sözleşmeyi imzalayarak, Deka Technology'de çalışırken:
- Müşteri bilgilerini gizli tutacağımı
- Kodları paylaşmayacağımı
- 3 yıl sonrası da gizli kalacağını
kabul ediyorum.
```

## 4. NDA (Çalışan)

```
Aynı gizlilik sözleşmesi ama daha resmi.
Karşılıklı yükümlülükler.
```

## 5. ÇIKIŞ FORMU

```
Son Çalışma Günü: ___________
Aldığı Malzemeleri Geri Verdi: ☐ Evet
Bilgisayar: ☐ Evet
Telepon: ☐ Evet
Anahtar: ☐ Evet
Dosyalar: ☐ Evet

Ödenen Tutarlar:
- Son Ücret: X TRY
- Tazminat: X TRY
- Diğer: X TRY
TOPLAM: X TRY ☐ Ödendi
```

---

## Entegrasyon

- deka-is-hukuku-checklist → Prosedür
- deka-kvkk-politika → Veri işleme

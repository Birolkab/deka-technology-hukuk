---
name: deka-gizlilik-onay-formu
description: >
  Gizlilik ve KVKK onay formu. Çalışan onayı, Müşteri onayı, Web sitesi checkbox. 
  Kanıt saklama (audit trail).
argument-hint: "[Onay türü: Çalışan / Müşteri / Ziyaretçi]"
---

# DEKA GİZLİLİK ONAY FORMU

## 1. ÇALIŞAN ONAY FORMU

```
Adı-Soyadı: ________________
Tarihí: ________________

☑ Deka Technology'in KVKK Gizlilik Politikası'nı okudum
☑ Kişisel verilerimin işlenmesine izin veriyorum
☑ Pazarlama iletişimi almak istiyorum (opsiyonel)
☑ Müşteri projelerinde gizlilik kurallarını kabul ediyorum

İmza: ________________

Not: Bu form dosyada saklanır (KVKK audit için)
```

## 2. MÜŞTERİ ONAY FORMU

```
Firma: ________________ (Anadolu Efes örneği)
Tarihí: ________________
Proje: "Satış Sistemi"

☑ Deka Technology'in KVKK Gizlilik Politikası'nı okudum
☑ Müşteri verilerimin Deka tarafından işlenmesine izin veriyorum
☑ Veri İşleme Sözleşmesi'ni kabul ediyorum
☑ Veri sızması durumunda 24 saat içinde bildirim alacağımı anladım

İşveren Adı: ________________
İmza: ________________
```

## 3. WEB SITESI CHECKBOX

```
☑ "Gizlilik Politikasını Kabul Ediyorum"
(İlk ziyaretçi otomatik onay ister)
```

---

## Entegrasyon

- deka-kvkk-politika → Bağlantı
- Dosya arşivi (Audit trail)

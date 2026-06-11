---
name: deka-veri-isleme-sozlesme
description: >
  Müşteri ile KVKK Veri İşleme Sözleşmesi. Deka = Veri İşlemeci (KVKK m.3), 
  Müşteri = Veri Sorumlusu. Hangi veriler, nasıl işleniyor.
argument-hint: "[Müşteri adı / işlenecek veri türleri]"
---

# DEKA KVKK VERI İŞLEME SÖZLEŞMESI

## Yasal Rol

**Müşteri (Anadolu Efes gibi):**
- Veri Sorumlusu (KVKK m.3/ç)
- Verileri toplar, amaçları belirler

**Deka Technology:**
- Veri İşlemeci (KVKK m.3/d)
- Müşteri'nin talimatı üzerine veriler işler

## Veriler Nelerdir?

```
Müşteri Projesi: "Satış Sistemi"
İşlenecek Veriler:
- Satıcı adları, maaşları
- Müşteri adları, cep telefonları
- İşlem tutarları, tarihleri
```

## İşleme Şekli

- **Şifreleme:** Veritabanı AES-256 şifreleme
- **Erişim Kontrolü:** Sadece Deka mühendisleri erişebilir
- **Yedekleme:** Günlük AWS yedekleme
- **Silme:** Proje sonrası 30 gün içinde kalıcı silme

## İhlal Durumunda

Deka, veri sızması durumunda:
- Müşteri'yi 24 saat içinde bildir
- KVKK'ya bildir
- Etkilenen verilerin listesini sun

---

## Entegrasyon

- deka-kvkk-politika → Gizlilik politikası
- deka-veri-guvenligi-checklist → Teknik kontroller

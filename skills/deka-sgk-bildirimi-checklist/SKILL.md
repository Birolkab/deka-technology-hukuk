---
name: deka-sgk-bildirimi-checklist
description: >
  SGK (Sosyal Güvenlik Kurumu) bildirimi prosedürü. İşe alım, fesih, kimlik 
  değişiklikleri. E-SGK online bildirimi.
argument-hint: "[Bildirim türü: İşe Alım / Fesih / Değişiklik]"
---

# DEKA SGK BİLDİRİMİ CHECKLIST

## İŞE ALIM BİLDİRİMİ

- [ ] E-SGK Portalı'nda "Sigortalı Kayıtları" bölümüne gir
- [ ] "Yeni Sigortalı" seçeneğini tıkla
- [ ] Kimlik No, Ad-Soyad, Doğum Tarihi, TC No gir
- [ ] İşe Alım Tarihi: YYYY-MM-DD (Sözleşme tarihi)
- [ ] Primi Ödeyecek: Deka Technology (İşveren)
- [ ] Bildirimi Onayla ve Gönder
- [ ] Onay almak 2-3 iş günü

## FESİH BİLDİRİMİ

- [ ] Fesih Haber Tarihine KADAR bildirme! (30 gün haber kuralı)
- [ ] E-SGK > Sigortalı Kayıtları > Fesih
- [ ] Fesih Tarihi: YYYY-MM-DD (Gerçek çıkış günü)
- [ ] Sebep: (İsteğe bağlı)
- [ ] Gönder

**SIKÇA YAPILAN HATA:** Fesih bildirimini unutmak → SGK devam öder → İşveren para iade etmek zorunda kalır

---

## Entegrasyon

- deka-is-sozlesme-yazici → Sözleşme tarihi
- deka-is-mahkemesi-risk → Tazminat hesapla

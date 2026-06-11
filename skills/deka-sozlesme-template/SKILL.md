---
name: deka-sozlesme-template
description: >
  Deka için standart sözleşme şablonları. MSA (Master Service Agreement), 
  SOW (Scope of Work), NDA, SLA. Tüm şablonlar TBK uyumlu ve test edilmiş.
argument-hint: "[Şablon türü: MSA / SOW / NDA / SLA]"
---

# DEKA SÖZLEŞME ŞABLONLARı

## 1. MSA (Master Service Agreement)

**İçerik:**
- Taraflar, İş Tanımı
- Ödeme Şartları (net 30/60)
- IP Sahipliği (müşteri sahibi)
- Gizlilik (karşılıklı, 3 yıl)
- Sorumluluğun Sınırlanması (max 1 proje tutarı)
- Fesih Şartları (30 gün haber)

## 2. SOW (Scope of Work)

**İçerik:**
- Proje Adı & Numarası
- Kapsamı (maddeli liste)
- Dışlanmış İşler (scope creep önleme)
- Teslimat Tarihleri
- Maliyeti (sabit + breakdown)
- Ödeme Planı (ön + % teslimat)
- Test Dönemi (30 gün)

## 3. NDA (Gizlilik)

**İçerik:**
- Gizli Bilgi Tanımı
- Gizlilik Süresi (3 yıl)
- İstisnalar (genel bilgi, kanun)
- Müekkil'in Yükümlülüğü

## 4. SLA (Service Level Agreement)

**İçerik:**
- Uptime Garantisi (99% gerçekçi)
- Response Time (kritik: 4 saat, normal: 24 saat)
- Ceza Maddeleri (makul, max 1 ay ücret)

---

## Entegrasyon

- deka-sozlesme-inceleme → Şablon karşılaştırma
- deka-sozlesme-karsilastirma → Geçmiş versiyonlar

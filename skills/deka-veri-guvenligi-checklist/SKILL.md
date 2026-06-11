---
name: deka-veri-guvenligi-checklist
description: >
  Teknik veri güvenliği checklist. HTTPS, veritabanı şifreleme, backup, 
  personel erişim kontrolü, malware scanning.
argument-hint: "[Sistem / Uygulama]"
---

# DEKA VERİ GÜVENLİĞİ CHECKLIST

## Ağ Güvenliği

- [ ] **HTTPS Aktif** (SSL/TLS sertifikası)
- [ ] **Firewall** (Gelen/giden trafiği kontrol)
- [ ] **DDoS Koruması** (Cloudflare, AWS Shield gibi)
- [ ] **İntrusion Detection** (Saldırı tespit sistemi)

## Veri Güvenliği

- [ ] **Veritabanı Şifreleme** (AES-256)
- [ ] **Password Hashing** (bcrypt, Argon2)
- [ ] **API Tokens** (Rastgele, kısa ömürlü)
- [ ] **SQL Injection Koruması** (Prepared statements)

## Yedekleme

- [ ] **Günlük Yedekleme** (Otomatik)
- [ ] **Off-Site Backup** (Ayrı coğrafi bölge)
- [ ] **Restore Testi** (Ayda 1x yapılan test)
- [ ] **Yedekleme Şifrelemesi**

## Personel Erişim

- [ ] **Role-Based Access Control (RBAC)**
  - Admin: Full access
  - Engineer: Geliştirme + test verilerine
  - Support: Sadece müşteri sorunlarına

- [ ] **2FA (İki Faktörlü Kimlik Doğrulama)** (Admin hesapları)
- [ ] **Access Logging** (Kim ne zaman ne okudu?)
- [ ] **Quarterly Access Review** (Çıkan çalışanı hemen kapat)

## Tehdit Taraması

- [ ] **Malware Scanning** (Aylık)
- [ ] **Penetration Testing** (Yıllık)
- [ ] **Vulnerability Scan** (Hazırlık yapılı)

---

## Entegrasyon

- deka-veri-isleme-sozlesme → İşleme tanımı
- deka-veri-ihlali-protokol → İhlal durumunda

# 🔧 Firebase Authentication Sorunu - Hızlı Çözüm

## ❌ Sorun
```
admin-restricted-operation
```
= Anonymous login enable değil!

---

## ✅ ÇÖZÜM (2 dakika)

### 1️⃣ Firebase Console'a Git
```
https://console.firebase.google.com
```

### 2️⃣ "mistakes-548c3" → Build → **Authentication**

### 3️⃣ **"Sign-up method"** Sekmesi
1. **"Anonymous"** bul
2. Sağda mavi **açılır menu (⋮)** tıkla
3. **"Enable"** seç (AÇIK/On olmalı!)

### 4️⃣ Kaydet
- **"Save"** tıkla
- Yeşil onay işareti görülmeli ✅

---

## 🔄 Database Rules Güncellemesi

1. **Build → Realtime Database**
2. **"Rules"** sekmesi
3. **Tüm kodu sil**, BUNU YAPISTIR:

```json
{
  "rules": {
    "users": {
      "$uid": {
        ".read": "auth !== null",
        ".write": "auth !== null"
      }
    }
  }
}
```

4. **"Başlat"** tıkla

---

## 🚀 Test Et

```
https://mistakes-548c3.web.app
```

- Yeniden yükle (F5)
- Soru ekle
- Çalışıyor mı? ✅

---

**2 dakika al, kontrol et! 🔧**

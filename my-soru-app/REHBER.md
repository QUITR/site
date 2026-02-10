# 🎓 Soru Çözüm Uygulaması - Firebase Hosting

## ✅ Başarıyla Yayında!

Uygulamanız Firebase Hosting'de başarıyla dağıtıldı ve şu adreste erişilebilir:

🔗 **https://mistakes-548c3.web.app**

---

## 📱 Uygulama Özellikleri

✅ **Soru Ekleme** - Fotoğraf + Cevap (A,B,C,D,E)  
✅ **Soru Çözme** - Interaktif kalemle çizim  
✅ **Çözüm Geçmişi** - Tüm çözümleri sakla ve görüntüle  
✅ **Sınav Modu** - Rasgele soru seçip sınav yap  
✅ **Veri Dışa/İçe Aktarma** - JSON olarak soruları kaydet/yükle  
✅ **Tamamen Çevrimdışı** - İnternet olmadan çalış  

---

## 🛠️ Proje Yapısı

```
my-soru-app/
├── index.html          # Ana uygulamalar
├── firebase.json       # Firebase konfigürasyonu
└── .firebaserc         # Firebase proje ayarları
```

---

## 📝 Kullanım Talimatları

### 1️⃣ Uygulamaya Erişim
Tarayıcında aç: https://mistakes-548c3.web.app

### 2️⃣ Soru Ekleme
- "Yeni Soru Ekle" butonuna tıkla
- Soru fotoğrafını yükle (veya Ctrl+V ile yapıştır)
- Ders ve Konu alanlarını doldur
- Doğru cevabı (A, B, C, D, E) seç
- "Ekle" butonuna tıkla

### 3️⃣ Soru Çözme
- Listeden soruyu seç
- "Çöz" butonuna tıkla
- Kalemin rengini seç
- Soru üzerine çiz
- Şıkları tıkla ve "Çözümü Kaydet"

### 4️⃣ Sınav Yapma
- Ders, Konu ve Seviye filtresi kullan
- İçinden kaç soru çekmek istersen seç
- "Sadece Soruları Çöz" tıkla
- Tüm sorular için seçim yap ve sonuçları gör

### 5️⃣ Verileri Kayıt Etme
- "Soruları Dışa Aktar" → JSON dosyası indir
- Başka bir cihazda "Soruları İçe Aktar" → JSON yükle

---

## 🔄 Güncellemeler / Değişiklikler

Uygulamada değişiklik yapmak istersen:

1. **index.html dosyasını düzenle**
   - VS Code'da mi-soru-app/index.html aç
   - Değişiklikleri yap
   - Dosyayı kaydet

2. **Firebase'e yeniden yayınla**
   ```bash
   cd C:\Users\yunus\Desktop\my-soru-app
   firebase deploy --only hosting
   ```

3. **Değişiklikler anında yayında olur!**

---

## 📊 Veri Depolama

- **Tüm veriler** browser'ın localStorage'da saklanır
- Her tarayıcı/cihaz kendi verisini tutar
- Tarayıcı geçmişini silersen **veriler silinir** ⚠️
- **JSON dışa aktar** ile yedek al

---

## 🏠 Yerel Test (İsteğe Bağlı)

Değişiklikleri sitemde test etmek istersen:

```bash
cd C:\Users\yunus\Desktop\my-soru-app
firebase serve
```

Tarayıcıda aç: http://localhost:5000

---

## 📚 Firebase Konsolu

Proje istatistikleri ve ayarları:  
🔗 https://console.firebase.google.com/project/mistakes-548c3/overview

---

## ⚡ Performans Bilgileri

- **Site Hızı:** Çok hızlı ⚡
- **Depolama:** Sınırsız (JSON dosyalara dayalı)
- **Veri Transfer:** 5GB/ay (ücretsiz plan)
- **Uptime:** %99.95+

---

## 🆘 Sorun Giderme

### Site açılmıyor?
- Tarayıcı cache'ini temizle (Ctrl+Shift+Del)
- Sayfayı yenile (Ctrl+R veya F5)

### Veriler kaydedilmiyor?
- Browser'ın localStorage depolması dolmuş olabilir
- Eski soruları dışa aktar ve sil
- Tarayıcı veri ayarlarından alan açıl

### Fotoğraf yüklenmiyor?
- Resim formatı PNG/JPG olmalı
- Dosya boyutu 5MB'dan küçük olmalı
- Tarayıcıyı yenile ve tekrar dene

---

## ✨ İleride Eklenebilecek Özellikler

- ☐ Firebase Realtime Database ile bulut senkronizasyonu
- ☐ Kullanıcı hesapları ve kimlik doğrulama
- ☐ Paylaşım ve işbirliği özellikleri
- ☐ Analitik dashboard
- ☐ Mobil uygulama versiyonu

---

## 📞 Iletişim

Sorular veya öneriler için aşağıdaki adrese eriş:  
📧 E-posta: yunusemrehppp@gmail.com

---

**Hayırlı kullanmalar! 🎉**

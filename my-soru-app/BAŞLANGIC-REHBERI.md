# Soru Çözüm Uygulaması - Firebase Deployment

## 🎉 En Başından Başlayanlara Hızlı Başlangıç

Uygumanız **firebase** üzerinde başarıyla yayında! İşte yapman gerekenler:

### 1. Uygulamaya Erişim
Web tarayıcını aç ve şu adrese git:
```
https://mistakes-548c3.web.app
```

### 2. Soru Eklemek İçin
- **"Yeni Soru Ekle"** tıkla
- Resim dosyasını seç veya yapıştır (Ctrl+V)
- Ders adı yaz (örn: "Matematik")
- Konu yaz (örn: "Türevler")
- Doğru cevap seç (A, B, C, D, E)
- **"Ekle"** tıkla ✅

### 3. Soru Çözmek İçin
- Ana sayfadan soruyu seç
- **"Çöz"** tıkla
- Kalemle soru üzerine çiz
- Şıkını seç (A, B, C, D, E)
- **"Çözümü Kaydet"** tıkla ✅

### 4. Sınav Yapmak İçin
- Filtre seçeneklerini doldur
- İçinden kaç soru çekeceğini belirt
- **"Sadece Soruları Çöz"** tıkla
- Sonuçları gör ✅

### 5. Verilerinizi Yedeklemek
- **"Soruları Dışa Aktar"** → dosyanı kaydet
- Başka cihazda: **"Soruları İçe Aktar"** → dosyayı yükle

---

## 🔧 Teknik Bilgileri (Geliştiriciler İçin)

### Proje Yapısı
```
my-soru-app/
├── index.html       (Tüm uygulama burada)
├── firebase.json    (Hosting konfigurasyonu)
└── .firebaserc      (Proje ID'si)
```

### Kodda Değişiklik Yapma

1. İhtiyacın dosyayı VS Code'da aç:
   ```
   C:\Users\yunus\Desktop\my-soru-app\index.html
   ```

2. Değişiklikleri yap ve kaydet

3. Firebase'e yeniden yükle:
   ```bash
   cd C:\Users\yunus\Desktop\my-soru-app
   firebase deploy --only hosting
   ```

### Yerel Test
Değişiklikleri canlıya koymadan önce lokalde test etmek için:
```bash
cd C:\Users\yunus\Desktop\my-soru-app
firebase serve
```
Sonra tarayıcıda açıl: http://localhost:5000

---

## 📊 Veriler Nereye Saklanır?

- ✅ **LocalStorage** - Tarayıcının verisine kaydedilir
- ✅ **Resimler** - Base64 olarak saklanır
- ⚠️ **Silinirse** - Tarayıcı cache silinirse kaybolur
- 💾 **Yedek** - JSON dışa aktar ile kaydet

---

## 🌍 URL Sabit Kalıyor

Uygumanın URL'i daima şu olacak:
```
https://mistakes-548c3.web.app
```

Siteye Git ve bookmarkine ekle! 📌

---

## 🚀 Daha Sonra Eklenebilecekler

- Cloud sayılı veritabanı (Firebase Realtime Database)
- Kullanıcı hesapları
- Soruları paylaşma
- Analitik (kaç soru çözdün, başarı yüzdesi, vb)

---

## 📱 Mobil Cihazlarda Kullan

Tarayıcıda https://mistakes-548c3.web.app aç ve **"Homescreen'e Ekle"** seç. Masaüstü uygulaması gibi çalışır!

---

**Mutlu kullanmalar! 🎓✨**

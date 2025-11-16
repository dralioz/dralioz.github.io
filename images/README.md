# Profil Fotoğrafı Yükleme Rehberi 📸

## Fotoğrafını Nasıl Eklersin:

### 🎯 **Adım 1:** Fotoğraf Hazırla
- **Format:** JPG, PNG veya WebP
- **Boyut:** Minimum 300x300px (Kare formatı önerilir)
- **Kalite:** Yüksek çözünürlük
- **Dosya Adı:** `profile.jpg` olarak kaydet

### 📁 **Adım 2:** Fotoğrafı Bu Klasöre Koy
1. Fotoğrafını bu `images/` klasörüne kopyala
2. Dosya adının `profile.jpg` olduğundan emin ol
3. Eğer farklı format kullanıyorsan (PNG vs), `index.html`'deki yolu güncelle

### 🔧 **Adım 3:** Git ile Yükle
```bash
git add images/profile.jpg
git commit -m "Add profile photo"
git push
```

### ⚡ **Hızlı Çözüm - Farklı Format İçin:**
Eğer fotoğrafın PNG formatındaysa, `index.html`'de şu satırı bul:
```html
<img src="./images/profile.jpg" ...>
```

Ve şu şekilde değiştir:
```html
<img src="./images/profile.png" ...>
```

### 🎨 **İpuçları:**
- Yuvarlak kesim otomatik yapılacak
- Fotoğraf merkezi konumlandırılacak
- Hover efekti için büyüteç ikonu eklenecek
- Tıklandığında modal'da büyük boyutta açılacak

### 🛠️ **Test Et:**
1. Fotoğrafı yükledikten sonra sayfayı yenile
2. Eğer fotoğraf gözükmüyorsa, dosya adını ve yolunu kontrol et
3. Placeholder (DA) gözüküyorsa, fotoğraf yolu yanlış demektir
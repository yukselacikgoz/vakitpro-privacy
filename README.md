# vakitpro-privacy
VakitPro — Gizlilik Politikası / Privacy Policy

> **Son güncelleme / Last updated:** Haziran 2026 / June 2026

---

## 🇹🇷 Türkçe

### Genel Bakış

VakitPro, namaz vakitlerini takip eden, kıble yönünü gösteren ve ezan sesiyle hatırlatan ücretsiz bir Windows masaüstü uygulamasıdır.

**VakitPro hiçbir kişisel veri toplamaz, saklamaz veya üçüncü taraflarla paylaşmaz.**
Uygulamada kullanıcı hesabı, kayıt formu, reklam veya analitik sistemi bulunmaz.

---

### Kullanılan Veriler

#### 📍 Konum Bilgisi (Şehir, Ülke, Enlem, Boylam)

Namaz vakitlerinin hesaplanması için yaklaşık konum bilgisi kullanılır. Bu bilgi üç farklı şekilde elde edilebilir:

| Yöntem | Açıklama | Dış Servis |
|--------|----------|-----------|
| **Otomatik algılama** | IP adresiniz üzerinden yaklaşık konum tespit edilir | [ipapi.co](https://ipapi.co) |
| **Manuel şehir arama** | Girdiğiniz şehir adı koordinata dönüştürülür | [Nominatim / OpenStreetMap](https://nominatim.openstreetmap.org) |
| **Sabit konum** | Manuel girilen koordinatlar yalnızca cihazda saklanır | Yok |

Konum verileri yalnızca namaz vakti hesabı ve kıble yönü belirleme amacıyla kullanılır.

#### 🕌 Namaz Vakti Verileri

Koordinatlarınız (enlem/boylam) ve seçili hesaplama yöntemi, [Aladhan.com](https://aladhan.com) API'sine iletilerek namaz vakitleri hesaplanır. Bu API ücretsiz ve herkese açıktır. Hesaplanan vakitler gereksiz API çağrısını önlemek amacıyla cihazınızda **24 saat** boyunca yerel olarak önbelleğe alınır.

#### ⭐ Favori Konumlar

Kaydettiğiniz favori şehirler cihazınızdaki yerel bir JSON dosyasında saklanır. Bu veriler hiçbir sunucuya gönderilmez.

#### ⚙️ Uygulama Ayarları

Tema, dil, bildirim, ezan sesi ve görünüm tercihleriniz cihazınızdaki yerel bir JSON dosyasında saklanır. Bu veriler cihazınız dışına çıkmaz.

---

### Üçüncü Taraf Hizmetler

| Hizmet | Kullanım Amacı | Gizlilik Politikası |
|--------|---------------|---------------------|
| [ipapi.co](https://ipapi.co) | IP tabanlı otomatik konum algılama | [ipapi.co/privacy](https://ipapi.co/privacy/) |
| [Aladhan.com](https://aladhan.com) | Namaz vakti hesaplama | [aladhan.com/privacy-policy](https://aladhan.com/privacy-policy) |
| [Nominatim / OSM](https://nominatim.openstreetmap.org) | Manuel şehir arama | [osmfoundation.org](https://osmfoundation.org/wiki/Privacy_Policy) |

Bu hizmetlerin gizlilik uygulamaları kendi politikalarına tabidir. Uygulamamız bu veriler üzerinde kontrol sahibi değildir.

---

### Yerel Depolama

Uygulama yalnızca şu dosyaları cihazınıza yazar:

```
%LOCALAPPDATA%\VakitPro\favoriler.json   → Favori konumlar
%LOCALAPPDATA%\VakitPro\Cache\           → API önbellek dosyaları
%APPDATA%\VakitPro\appsettings.json      → Kullanıcı ayarları
```

Bu dosyalar yalnızca cihazınızda bulunur; bulut ortamına ya da herhangi bir sunucuya yüklenmez.

---

### Çocukların Gizliliği

Uygulama 13 yaş altı çocuklara yönelik kişisel veri toplamaz.

---

### Değişiklikler

Bu politika gerektiğinde güncellenebilir. Önemli değişiklikler uygulama güncelleme notlarında duyurulacaktır.

---

### İletişim

Gizlilik politikasıyla ilgili sorularınız için Microsoft Mağazası'ndaki uygulama sayfasından veya bu deponun [Issues](../../issues) bölümünden iletişime geçebilirsiniz.

---
---

## 🇬🇧 English

### Overview

VakitPro is a free Windows desktop application for tracking prayer times, showing the Qibla direction, and providing adhan sound reminders.

**VakitPro does not collect, store, or share any personal data with third parties.**
The application has no user accounts, registration forms, advertisements, or analytics.

---

### Data Used

#### 📍 Location Information (City, Country, Latitude, Longitude)

Approximate location is used to calculate prayer times. It can be obtained in three ways:

| Method | Description | External Service |
|--------|-------------|-----------------|
| **Auto-detection** | Approximate location detected via your IP address | [ipapi.co](https://ipapi.co) |
| **Manual city search** | The city name you enter is converted to coordinates | [Nominatim / OpenStreetMap](https://nominatim.openstreetmap.org) |
| **Fixed location** | Manually entered coordinates stored only on device | None |

Location data is used solely for prayer time calculation and Qibla direction.

#### 🕌 Prayer Time Data

Your coordinates (latitude/longitude) and selected calculation method are sent to the [Aladhan.com](https://aladhan.com) API to compute prayer times. This is a free, public API. Computed times are cached locally on your device for **24 hours** to reduce unnecessary API calls.

#### ⭐ Favorite Locations

Favorite cities you save are stored in a local JSON file on your device. This data is never sent to any server.

#### ⚙️ Application Settings

Your theme, language, notification, adhan sound, and appearance preferences are stored in a local JSON file on your device. This data never leaves your device.

---

### Third-Party Services

| Service | Purpose | Privacy Policy |
|---------|---------|----------------|
| [ipapi.co](https://ipapi.co) | IP-based automatic location detection | [ipapi.co/privacy](https://ipapi.co/privacy/) |
| [Aladhan.com](https://aladhan.com) | Prayer time calculation | [aladhan.com/privacy-policy](https://aladhan.com/privacy-policy) |
| [Nominatim / OSM](https://nominatim.openstreetmap.org) | Manual city search | [osmfoundation.org](https://osmfoundation.org/wiki/Privacy_Policy) |

The privacy practices of these services are governed by their own policies. Our application has no control over that data.

---

### Local Storage

The application only writes the following files to your device:

```
%LOCALAPPDATA%\VakitPro\favoriler.json   → Favorite locations
%LOCALAPPDATA%\VakitPro\Cache\           → API cache files
%APPDATA%\VakitPro\appsettings.json      → User settings
```

These files exist only on your device; they are never uploaded to the cloud or any server.

---

### Children's Privacy

The application does not collect personal data from children under the age of 13.

---

### Changes

This policy may be updated as needed. Significant changes will be announced in the application's update release notes.

---

### Contact

For questions about this privacy policy, please use the Microsoft Store application page or the [Issues](../../issues) section of this repository.

---

*VakitPro © 2026 Yuksel Acikgoz. Tüm hakları saklıdır / All rights reserved.*

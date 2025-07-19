# 🌬️ Rüzgar ve Sıcaklık Analiz Haritası

Bu proje, Leaflet.js kullanılarak seçilen alan üzerinde sıcaklık ve rüzgar hızını görsel olarak analiz etmenizi sağlar. OpenWeatherMap API'si ile anlık meteorolojik veriler çekilir ve harita üzerine gösterilir.

---

## 🚀 Özellikler

- 🗺️ Harita üzerinde dikdörtgen çizerek alan seçimi
- 📍 Belirli aralıklarla örnekleme (km cinsinden)
- 🌡️ Sıcaklığı renkli kutularla görselleştirme
- 💨 Rüzgar hızını ve yönünü ok ile gösterme
- 📊 Sekmeli kullanıcı arayüzü (Alan Seçimi / Veri Toplama)
- 🧭 Açıklayıcı gösterge (legend) paneli

---

## 🧰 Kullanılan Teknolojiler

- [Leaflet.js](https://leafletjs.com/)
- [Leaflet.draw](https://github.com/Leaflet/Leaflet.draw)
- [OpenWeatherMap API](https://openweathermap.org/api)
- HTML, CSS, JavaScript (Vanilla)

---

## 📦 Kurulum Adımları

1. Tüm dosyaları bilgisayarına indir.
2. `index.html` dosyasını bir tarayıcıda aç.
3. Aşağıdaki adımı uygulamadan **veriler yüklenmez**:

### 🔑 API Anahtarı Girişi

- `index.html` içinde şu satırı bul:

```js
const API_KEY = '';
```

- Tırnak içine kendi [OpenWeatherMap](https://openweathermap.org/api) API anahtarını ekle:

```js
const API_KEY = 'BURAYA_ANAHTARINIZI_YAZIN';
```

---

## 📋 Kullanım

### 1. Alan Seçimi

- "🗺️ Alan Seçimi" sekmesinde harita üzerinde dikdörtgen çizerek analiz alanını seçin.

### 2. Veri Toplama

- "📊 Veri Toplama" sekmesine geçin.
- Örnekleme sıklığını (0.5 km - 5 km) seçin.
- "Verileri Topla" butonuna tıklayın.
- Seçilen alandaki noktalar için sıcaklık ve rüzgar verileri görselleştirilir.

---
<img width="978" height="859" alt="t1" src="https://github.com/user-attachments/assets/5775f5c1-8cda-44df-824d-98de10c4f52e" />
<img width="979" height="946" alt="t2" src="https://github.com/user-attachments/assets/6b410502-5a9a-4800-9754-d3a6ae1c3814" />


## ⚠️ Uyarılar

- OpenWeatherMap ücretsiz API planı günlük sınırlı sayıda istek alır.
- Örnekleme sıklığını düşük tutmak çok fazla istek gönderir, bu durum yavaşlamaya neden olabilir.

---

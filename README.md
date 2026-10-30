# ☕ MindCafe

> Web tarayıcınızda çalışan, gerçek zamanlı sentetik ses motoruna sahip, interaktif ve tamamen duyarlı bir dijital çalışma sığınağı ve odaklanma alanı.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Web Audio API](https://img.shields.io/badge/Web%20Audio%20API-FF4500?style=flat-square&logo=audio&logoColor=white)
![PWA Ready](https://img.shields.io/badge/PWA-Ready-purple?style=flat-square)

---

## ✨ Proje Hakkında

**Digital Cozy Sanctuary**, uzun çalışma saatlerinde veya mola vermek istediğinizde dikkatinizi dağıtmadan sizi sakinleştiren, kendi ses miksinizi oluşturabileceğiniz ve çeşitli atmosferler arasında geçiş yapabileceğiniz minimalist bir web uygulamasıdır. 

Harici ses dosyalarına (MP3/WAV) bağımlı kalmadan, **Web Audio API** kullanarak tarayıcı içinde tamamen matematiksel olarak üretilen (procedural) ses motoruyla çalışır.

---

## 🚀 Öne Çıkan Özellikler

* **🎛️ 6 Kanallı Prosedürel Ses Mikseri:** 
  * Sağanak Yağmur (Pink/Brown Noise + Lowpass Filter)
  * Şömine & Ateş Çıtırtısı (Crackle Generator)
  * Mekanik Klavye Ritmik Tıkırtısı
  * Lo-Fi Caz Akorları (Polifonik Osilatör Döngüsü)
  * Binaural Alpha Odak Dalgası (10Hz Farklı Stereo Osilatör)
  * Kış Rüzgarı / Tipi Sesi
* **🗺️ Çoklu Atmosfer / Mekan Seçici:**
  * 🏙️ **Şehir Kafesi:** Gökdelen silüeti ve modern loft havası.
  * 🪵 **Dağ Evi:** Ahşap kütük doku, çam ormanı manzarası ve tıkladıkça harlanan **interaktif taş şömine**.
  * ⛩️ **Zen Veranda:** Shoji paravanları, fenerler ve sakin doğa manzarası.
* **❄️ Dinamik Hava Durumu & Mevsim Motoru:**
  * HTML5 Canvas tabanlı gerçek zamanlı **Yağmur** ve **Kar (Kış Teması)** yağışı animasyonları.
* **⏱️ Odak Araçları & Entegrasyonlar:**
  * Dahili Pomodoro Sayacı (25:00 Odak / Molalar)
  * LocalStorage destekli Mini Yapılacaklar Listesi (To-Do)
  * Aklınızdakileri hızlıca not alabileceğiniz İnteraktif Scratchpad (Not Defteri)
* **📱 Responsive & Mobil Uyumlu (Touch-First):**
  * Masaüstünde yan paneller, mobil cihazlarda ise alt kısımdan açılan akıllı **Bottom-Sheet (Çekmece)** mimarisi.

---

## 🛠️ Kullanılan Teknolojiler

* **Vanilla JavaScript (ES6+):** Sınıf yapısı, modüler mimari ve DOM manipülasyonları.
* **Web Audio API:** Dış kaynak kullanmadan gerçek zamanlı ses sentezi (`AudioBuffer`, `GainNode`, `BiquadFilterNode`, `Oscillator`).
* **HTML5 Canvas:** Yüksek performanslı parçacık (particle) yağmur ve kar simülasyonu.
* **CSS3 (Custom Properties & Glassmorphism):** Akıcı tema geçişleri, değişkenler (`--variables`) ve modern buzlu cam arayüzü.
* **LocalStorage API:** Kullanıcının ses miks ayarlarını, görev listesini ve notlarını cihazda kalıcı olarak saklama.

---

## ⚙️ Kurulum ve Çalıştırma

Bu projeyi yerel bilgisayarınızda çalıştırmak için herhangi bir sunucu kurmanıza gerek yoktur:

1. Projeyi klonlayın veya indirin:
   ```bash
   git clone [https://github.com/kullaniciadi/digital-cozy-sanctuary.git](https://github.com/kullaniciadi/digital-cozy-sanctuary.git)

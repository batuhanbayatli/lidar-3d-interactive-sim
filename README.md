<div align="center">

# 🛰️ 3D INTERACTIVE LiDAR & POINT CLOUD LAB
### ⚡ *Next-Gen Optical Occlusion & Real-Time Time-of-Flight Telemetry* ⚡

<br/>

<a href="https://lidar-3d-interactive-sim.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/CANLI_SİMÜLASYONU_DENE-000000?style=for-the-badge&logo=vercel&logoColor=00f2fe&labelColor=0d1117" alt="Vercel Live Demo" height="40"/>
</a>
<a href="https://www.linkedin.com/in/batuhanbayatlı" target="_blank">
  <img src="https://img.shields.io/badge/LINKEDIN_PROFİLİ-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a4066" alt="LinkedIn" height="40"/>
</a>

<br/><br/>

<!-- STATS & TECH BADGES -->
![](https://img.shields.io/badge/Engine-Three.js_r128-black?style=flat-square&logo=three.js&logoColor=00ffcc)
![](https://img.shields.io/badge/Render-WebGL_2.0-red?style=flat-square&logo=webgl&logoColor=white)
![](https://img.shields.io/badge/Audio-Web_Audio_API-orange?style=flat-square&logo=soundcharts&logoColor=white)
![](https://img.shields.io/badge/Telemetry-Time--of--Flight_(ToF)-blue?style=flat-square&logo=speedtest&logoColor=white)
![](https://img.shields.io/badge/Architecture-Zero--Build_Vanilla-yellow?style=flat-square&logo=javascript&logoColor=black)
![](https://img.shields.io/badge/License-MIT-emerald?style=flat-square)

<br/>

> 🎯 **Otonom araçların dünyayı nasıl gördüğünü doğrudan tarayıcında keşfet!**  
> Lazer darbeleri, nanosaniyelik optik örtüleme, dinamik nokta bulutu ve akustik sonar geri bildirimi tek bir etkileşimli arenada.

---

</div>

<br/>

## 🌟 ÖNE ÇIKAN SÜPER GÜÇLER

<table>
  <tr>
    <td width="50%">
      <h3>🛡️ Kusursuz Optik Gölgeleme (Occlusion)</h3>
      <p>Lazer ışınları opak nesnelerin içinden asla geçemez! Işın ilk çarptığı yüzeyde (<code>intersects[0]</code>) durur ve arkasındaki nesneler için <b>gerçekçi bir LiDAR gölgesi (kör nokta)</b> oluşturur.</p>
    </td>
    <td width="50%">
      <h3>⏳ Dinamik Nokta Yaşam Döngüsü (Decay)</h3>
      <p>Havada asılı kalan yapay hayalet izlere son! Noktalar belirlenen sönümleme süresi (TTL) bitince kaybolur; bir nesneyi sürüklediğinde <b>eski konumdaki tüm noktalar anında temizlenir</b>.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🔊 Senkronize Akustik Sonar (Web Audio)</h3>
      <p>Sıfır harici dosya yükü! Saf kodla üretilen parametrik ses sentezleyicisi, lazer bir cisme çarptığı anda <b>mesafeye göre dinamik frekansta (tiz/pes) sonar sinyali</b> çalar.</p>
    </td>
    <td width="50%">
      <h3>🎛️ Etkileşimli Sahne & Transform Okları</h3>
      <p>Sahneye dilediğin an yeni arabalar, yayalar, ağaçlar veya beton duvarlar ekle. Objeleri <b>3D oklarla tutup istediğin yere serbestçe taşı</b> ve sensörün tepkisini canlı izle.</p>
    </td>
  </tr>
</table>

---

## 📐 TELEMETRİ & FİZİK MOTORU

Simülasyon, endüstri standardı **Time-of-Flight (ToF)** formülünü donanım seviyesinde koşturur:

$$\Delta t = \frac{2 \times d}{c}$$

* **Azimut Ölçümü:** $0.0^\circ$ ile $360.0^\circ$ arasında hassas açı takibi.
* **Nanosaniye Telemetrisi:** Hedef mesafesine göre ışığın gidiş-dönüş süresi gerçek zamanlı HUD ekranında hesaplanır.
* **4 Farklı Görselleştirme:** Isı Haritası (Heatmap), Yükseklik Modu, Yansıma Şiddeti ve Neon Spektrum.

---

## 🎥 KAMERA & ÇALIŞMA MODLARI

| Mod | İkon | Deneyim & İşlev |
| :--- | :---: | :--- |
| **Orbit 3D Perspektif** | 🪐 | Sahneyi 360° serbestçe döndür, yakınlaş ve dilediğin açıdan izle. |
| **Kuşbakışı Radar** | 📡 | Tam tepeden 2D radar menzil halkaları ve açı kılavuzları görünümü. |
| **Sensör POV** | 👁️ | Dönen LiDAR optik kafasının kendi gözünden sahneyi deneyimle. |
| **Yalnızca Nokta Bulutu** | 🌌 | Tüm 3D katı modelleri gizler; tıpkı bir otonom beyni gibi saf veri bırakır. |

---

## 🚀 HIZLI BAŞLANGIÇ

Proje herhangi bir derleme adımı (build step) veya paket yöneticisi gerektirmez:

1. Depoyu klonlayın:
   git clone https://github.com/batuhanbayatli/lidar-3d-interactive-sim.git

2. Klasöre gidin:
   cd lidar-3d-interactive-sim

3. `index.html` dosyasını doğrudan tarayıcınızda açın veya VS Code Live Server başlatın.

Doğrudan kurulumsuz denemek için:  
👉 **[lidar-3d-interactive-sim.vercel.app](https://lidar-3d-interactive-sim.vercel.app/)** 🎯

---

## 👨‍💻 PROJE MİMARI

<div align="center">
  <b>BATUHAN BAYATLI</b><br/>
  <a href="https://www.linkedin.com/in/batuhanbayatlı" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Bağlantı_Kur-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://lidar-3d-interactive-sim.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Demo-Vercel'de_Aç-black?style=for-the-badge&logo=vercel&logoColor=white"/>
  </a>
  <br/><br/>
  <sub>MIT Lisansı ile korunmaktadır. © 2026 Batuhan Bayatlı.</sub>
</div>

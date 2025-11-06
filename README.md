# 🎲 React Dice Game

İki oyunculu (Kullanıcı vs Bilgisayar) **zar atma** oyunu.
Proje **Vite + React** ile geliştirilmiştir; `dev`, `build`, `preview` ve **GitHub Pages**’e tek komutla yayınlama script’leri hazır gelir. Komutlar ve bağımlılıklar `package.json` içinde tanımlıdır. 

---

## 🚀 Hızlı Başlangıç

```bash
# Bağımlılıkları yükle
npm install

# Geliştirme sunucusu (Vite)
npm run dev

# Üretim derlemesi
npm run build

# Build önizleme
npm run preview
```

> Script’lerin tamamı: `dev`, `build`, `lint`, `preview`, `predeploy`, `deploy`.
> `predeploy` üretim derlemesi alır, `deploy` ise **gh-pages** ile `dist/` klasörünü GitHub Pages’e gönderir. 

---

## 🧩 Teknolojiler

* **React 19** ve **React DOM 19** (ESM, modern JSX) 
* **Vite 7** geliştirme sunucusu ve üretim derlemesi 
* **Tailwind CSS v4** (resmi Vite eklentisi ile) 
* **ESLint** + React Hooks/Refresh kuralları (Vite uyumlu config) 

---

## 📁 Proje Yapısı

* **Giriş noktası**: `index.html` → `<div id="root">` ve `src/main.jsx` yüklemesi.
  (Favicon `vite.svg`, sayfa başlığı `dice-game` olarak ayarlı.) 
* **Global stiller**: `index.css` — light/dark color-scheme desteği, tipografi ve buton odak stilleri. 

Örnek minimal yapı:

```
.
├─ index.html
├─ src/
│  ├─ main.jsx
│  ├─ App.jsx
│  └─ index.css
├─ package.json
├─ eslint.config.js
└─ README.md
```

---

## 🎮 Oynanış (önerilen akış)

1. “Zarları At” butonuna tıklanır.
2. Her iki oyuncu için 1–6 arasında rastgele değer üretilir.
3. Ekranda sonuç gösterilir: **Kullanıcı kazandı / Bilgisayar kazandı / Berabere**.
4. Skor tutulabilir (kazanma/kaybetme/berabere), tekrar oyna akışı sunulabilir.

> Örnek bir önizleme ve canlı demo bağlantısı eklemek istersen mevcut README kalıbındaki alanları kullanabilirsin. 

---



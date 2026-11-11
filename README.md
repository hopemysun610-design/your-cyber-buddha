# YOUR CYBER BUDDHA // SYS.04 ACID TECHNO
> **Mindfulness Reimagined Through Acid Techno Brutalism & Client-Side Web Audio**  
> 🌐 **Live Production:** [yourcyberbuddha.cherrywebstudio.com](https://yourcyberbuddha.cherrywebstudio.com/)

---

## ⚡ Overview

**Your Cyber Buddha** is an interactive, zero-latency digital meditation and ambient soundscape web application designed and built by **CherryWeb Studio**. Blending ancient Buddhist philosophies with high-fashion brutalism and a cyberpunk aesthetic, it delivers daily meditative wisdom, procedural audio synthesis, and custom 3D talisman wallpaper generation directly within the mobile browser.

---

## 🛠️ Architecture & Key Engineering Highlights

### 1. Procedural Web Audio Synthesis (Zero-Latency DSP)
- **100% Client-Side Audio Pipeline:** Instead of streaming heavy pre-recorded audio files (~40MB), audio is procedurally synthesized client-side via the browser's native `Web Audio API` (`AudioContext`, custom oscillators, and ADSR gain envelopes).
- **108Hz Meditative Drone:** Generates an infinite, seamless binaural ambient frequency with zero looping seams or buffer stutter.
- **Dynamic 808 Bell Strike:** Low-end sub-bass transient synthesis triggered synchronously upon user interaction, achieving sub-45ms end-to-end tactile feedback.
- **Micro-Payload:** Reduced total audio asset footprint from 40MB down to **12KB of mathematical synthesis code**.

### 2. High-Performance Canvas Rendering Engine
- **4K Talisman Forge:** Generates customized 4K (3840x2160) lock-screen wallpapers with personalized character engraving and ambient metadata.
- **9:16 Instagram Story Cards:** Renders social-ready vertical scripture cards for seamless sharing across Instagram Stories and X feeds.
- **Mobile Memory Optimization:** Decouples device pixel ratio (DPR) on high-density Retina displays to strictly prevent mobile Safari WebKit out-of-memory (OOM) allocation crashes, utilizing asynchronous `.toBlob()` streams and immediate GPU buffer garbage collection.

### 3. Multilingual i18n Daily Transmission
- **31 Classical Scriptures:** Dynamic daily revelation engine hashing against local UTC dates to serve wisdom from foundational Buddhist canons.
- **Triple-Language Parity:** Instant zero-reloading language switching across **English (EN)**, **Korean (KR)**, and **Japanese (JA)**.

### 4. Edge Deployment & Sustainable Patronage
- **Global Edge Delivery:** Optimized static bundle deployed on Vercel Edge Network with sub-800ms First Contentful Paint (FCP) worldwide.
- **Digital Merit Patronage:** Integrated PayPal micro-transactions (`$1.08 / $3.00 / $6.00 / $10.80`) and KakaoBank secure account clipboards for voluntary indie creator support.

---

## 🚀 Running Locally

Open `index.html` directly in any modern browser, or serve locally with any static HTTP server:

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js npx
npx serve .
```

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author & Credits

- **Lead Developer & Product Designer:** Jaeseong Choi (Founder, [CherryWeb Studio](https://cherrywebstudio.com))
- **Production URL:** [https://yourcyberbuddha.cherrywebstudio.com](https://yourcyberbuddha.cherrywebstudio.com)

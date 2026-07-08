<div align="center">
  <img src="public/favicon.svg" width="80" height="80" alt="maddyShot logo">
  <h1>📸 maddyShot</h1>
  <p>
    <strong>Turn your code into beautiful, shareable images</strong>
    <br>
    <em>with full RTL / Persian support</em>
  </p>
  <p>
    <a href="https://maddyrampant.github.io/maddyshot" target="_blank">
      <img src="https://img.shields.io/badge/Live-Demo-22c55e?style=flat-square" alt="Live Demo">
    </a>
    <a href="LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-22c55e?style=flat-square" alt="MIT License">
    </a>
    <a href="https://github.com/Maddyrampant/maddyshot/releases">
      <img src="https://img.shields.io/badge/Release-v1.0.0-22c55e?style=flat-square" alt="v1.0.0">
    </a>
    <a href="https://react.dev">
      <img src="https://img.shields.io/badge/React-19-61DAFB?style=flat-square" alt="React 19">
    </a>
    <a href="https://vite.dev">
      <img src="https://img.shields.io/badge/Vite-8-646CFF?style=flat-square" alt="Vite 8">
    </a>
  </p>
  <br>
</div>

---

<br>

<p dir="rtl" align="center">
<strong>maddyShot</strong> ابزاری تماماً سمت کاربر (Client-Side) برای تبدیل کد یا متن به تصاویر زیبا و قابل اشتراک‌گذاری است. <br>
برخلاف ابزارهایی مثل Carbon یا Ray.so، <strong>متن راست‌به‌چپ (RTL)، تایپوگرافی فارسی و کدهای دوطرفه (BiDi)</strong> را به‌درستی مدیریت می‌کند.
</p>

<br>

---

<div align="center">
  
### ✨ English
  
</div>

**maddyShot** is a client-side SPA that converts code or text into polished, shareable images.  
Unlike Carbon, Ray.so, or CodeImage, it handles **RTL text, Persian typography, and bidirectional code** correctly — so Persian-speaking developers can share beautiful code screenshots without wrestling with layout bugs.

<br>

---

<br>

<div align="center">
  
### ✨ فارسی

</div>

<p dir="rtl" align="center">
maddyShot یه ابزار سمت کاربر (بدون سرور) برای تبدیل کد یا متن به تصاویر زیبا و قابل انتشار توی شبکه‌های اجتماعیه. <br>
تفاوتش با Carbon و Ray.so توی <strong>پشتیبانی درست از فارسی، RTL و کاراکترهای دوطرفه (BiDi)</strong> توی کدهاست — چیزی که هیچ‌کدوم از ابزارهای موجود درست انجام نمی‌دن.
</p>

<br>

---

<br>

## 📋 Table of Contents

| English | فارسی |
|---------|-------|
| [Features](#-features) | [قابلیت‌ها](#-قابلیت‌ها) |
| [Quick Start](#-quick-start) | [شروع سریع](#-شروع-سریع) |
| [Tech Stack](#-tech-stack) | [تکنولوژی‌ها](#-تکنولوژی‌ها) |
| [Why maddyShot?](#-why-maddyshot) | [چرا maddyShot؟](#-چرا-maddyshot) |
| [Screenshots](#-screenshots) | [تصاویر](#-تصاویر) |
| [Roadmap](#-roadmap) | [مسیر آینده](#-مسیر-آینده) |
| [License](#-license) | [لایسنس](#-لایسنس) |

<br>

---

<br>

<div align="center">
  
## ✨ Features

</div>

<table>
  <thead>
    <tr>
      <th width="220">Feature / قابلیت</th>
      <th>English</th>
      <th>فارسی</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>🎨 Syntax Highlighting</strong></td>
      <td>16 themes powered by Shiki (VS Code engine), 22+ languages with auto-detection</td>
      <td dir="rtl">۱۶ تم رنگی با موتور Shiki (همون موتور VS Code)، ۲۲+ زبان با تشخیص خودکار</td>
    </tr>
    <tr>
      <td><strong>🔤 RTL / BiDi Support</strong></td>
      <td>Automatic direction detection, <code>unicode-bidi: plaintext</code>, Persian number normalization</td>
      <td dir="rtl">تشخیص خودکار جهت متن، <code>unicode-bidi: plaintext</code>، نرمال‌سازی اعداد فارسی/عربی</td>
    </tr>
    <tr>
      <td><strong>🌈 Background</strong></td>
      <td>8 presets, 10 solid colors, gradient builder, transparent mode, custom color picker</td>
      <td dir="rtl">۸ گرادیانت آماده، ۱۰ رنگ ثابت، سازنده گرادیانت اختصاصی، حالت شفاف و color picker</td>
    </tr>
    <tr>
      <td><strong>🔠 Typography</strong></td>
      <td>Vazirmatn, JetBrains Mono, Fira Code, IBM Plex Mono with adjustable font size (10–24px)</td>
      <td dir="rtl">فونت‌های Vazirmatn و JetBrains Mono و Fira Code و IBM Plex Mono با اندازه قابل تنظیم</td>
    </tr>
    <tr>
      <td><strong>📥 Export</strong></td>
      <td>PNG (2x retina) & JPEG with image size presets (Twitter, Instagram, OG)</td>
      <td dir="rtl">خروجی PNG با کیفیت ۲x و JPEG با پریست‌های اندازه توییتر، اینستاگرام و OG</td>
    </tr>
    <tr>
      <td><strong>🔢 Line Numbers</strong></td>
      <td>Toggle on/off with dynamic digit width</td>
      <td dir="rtl">نمایش/مخفی‌سازی شماره خطوط با عرض پویا</td>
    </tr>
    <tr>
      <td><strong>🪟 Window Controls</strong></td>
      <td>macOS-style traffic light dots (🔴🟡🟢)</td>
      <td dir="rtl">سه دکمه macOS (🔴🟡🟢) در بالای کارت</td>
    </tr>
    <tr>
      <td><strong>💧 Watermark</strong></td>
      <td>Optional maddyShot branding on exported images</td>
      <td dir="rtl">واترمارک اختیاری maddyShot روی تصویر خروجی</td>
    </tr>
    <tr>
      <td><strong>📊 Stats Bar</strong></td>
      <td>Real-time line, word, and character count below the editor</td>
      <td dir="rtl">آمار زنده خطوط، کلمات و کاراکترها زیر ویرایشگر</td>
    </tr>
    <tr>
      <td><strong>🔔 Toast Notifications</strong></td>
      <td>Visual feedback on download, copy, reset actions</td>
      <td dir="rtl">اعلان‌های دیداری برای دانلود، کپی و بازنشانی</td>
    </tr>
    <tr>
      <td><strong>📱 Responsive</strong></td>
      <td>Collapsible sidebar with hamburger menu, works on mobile</td>
      <td dir="rtl">سایدبار جمع‌شونده با منوی همبرگری، سازگار با موبایل</td>
    </tr>
    <tr>
      <td><strong>🔒 Zero Server</strong></td>
      <td>Fully client-side — no backend, no data leaves your browser</td>
      <td dir="rtl">کاملاً سمت کاربر — بدون سرور، بدون ردپای داده</td>
    </tr>
  </tbody>
</table>

<br>

---

<br>

<div align="center">
  
## 🚀 Quick Start

</div>

<table>
  <tr>
    <th width="50%">English</th>
    <th width="50%">فارسی</th>
  </tr>
  <tr>
    <td>

```bash
git clone https://github.com/Maddyrampant/maddyshot.git
cd maddyshot
npm install
npm run dev
```

</td>
    <td dir="rtl">

```bash
git clone https://github.com/Maddyrampant/maddyshot.git
cd maddyshot
npm install
npm run dev
```

</td>
  </tr>
  <tr>
    <td>Open `http://localhost:5173` in your browser.</td>
    <td dir="rtl">مرورگرت رو باز کن و برو به `http://localhost:5173`</td>
  </tr>
  <tr>
    <td>

**Build for production:**

```bash
npm run build
```

Deploy `dist/` to any static host.

</td>
    <td dir="rtl">

**ساخت نسخه نهایی:**

```bash
npm run build
```

فایل‌های توی `dist/` رو روی هر هاست استاتیکی آپلود کن.

</td>
  </tr>
</table>

<br>

---

<br>

<div align="center">
  
## 🛠 Tech Stack

</div>

<table>
  <thead>
    <tr>
      <th>Layer</th>
      <th>Choice</th>
      <th>Why</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Framework</strong></td>
      <td><a href="https://react.dev">React 19</a> + <a href="https://vite.dev">Vite 8</a></td>
      <td>Fast DX, broad ecosystem, type-safe with TypeScript</td>
    </tr>
    <tr>
      <td><strong>Styling</strong></td>
      <td><a href="https://tailwindcss.com">Tailwind CSS v4</a></td>
      <td>Utility-first, rapid development, consistent design tokens</td>
    </tr>
    <tr>
      <td><strong>Syntax Highlighting</strong></td>
      <td><a href="https://shiki.style">Shiki v4</a></td>
      <td>VS Code-grade engine, 16 themes, accurate tokenization</td>
    </tr>
    <tr>
      <td><strong>Image Rendering</strong></td>
      <td><a href="https://github.com/bubkoo/html-to-image">html-to-image</a></td>
      <td>DOM → PNG/JPEG conversion with full font support</td>
    </tr>
    <tr>
      <td><strong>Fonts</strong></td>
      <td>Vazirmatn · JetBrains Mono · Fira Code · IBM Plex Mono</td>
      <td>Persian + monospace, loaded via Google Fonts</td>
    </tr>
  </tbody>
</table>

<br>

---

<br>

<div align="center">
  
## 🧠 Why maddyShot?

</div>

<table>
  <tr>
    <th width="50%">English</th>
    <th width="50%">فارسی</th>
  </tr>
  <tr>
    <td>

Existing tools like Carbon, Ray.so, and CodeImage have a blind spot: **RTL and Persian text**. Here's what happens when you paste Persian code into them:

| Problem | Result |
|---------|--------|
| ❌ Wrong text direction | LTR instead of RTL — code looks broken |
| ❌ Persian comments reorder | BiDi algorithm shuffles characters |
| ❌ No Persian font support | Arabic fallback, ugly rendering |
| ❌ Bad digit rendering | Persian/Arabic numerals garbled |

**maddyShot fixes all of these** while matching or exceeding the visual quality of existing tools.

</td>
    <td dir="rtl">

ابزارهای موجود مثل Carbon و Ray.so یه مشکل اساسی دارن: **پشتیبانی از RTL و متن فارسی**. وقتی کد فارسی توشون می‌چسبونی این مشکلات پیش میاد:

| مشکل | نتیجه |
|------|-------|
| ❌ جهت اشتباه متن | چپ‌چین به‌جای راست‌چین — کد به‌هم ریخته نشون داده می‌شه |
| ❌ کامنت‌های فارسی به‌هم می‌ریزن | الگوریتم BiDi ترتیب حروف رو به‌هم می‌زنه |
| ❌ بدون فونت فارسی باکیفیت | از فونت پیش‌فرض عربی استفاده می‌شه، ظاهر بد |
| ❌ نمایش غلط اعداد | اعداد فارسی/عربی درست رندر نمی‌شن |

**maddyShot همه اینا رو درست می‌کنه** در حالی که کیفیت بصری‌ش از ابزارهای موجود کمتر نیست.

</td>
  </tr>
</table>

<br>

---

<br>

<div align="center">
  
## 🖼 Screenshots

</div>

<p align="center">
  <em>Screenshots coming soon — deploy and see it live!</em>
</p>

<p dir="rtl" align="center">
  <em>به زودی — پروژه رو اجرا کن و خودت ببین!</em>
</p>

<br>

---

<br>

<div align="center">
  
## 🗺 Roadmap

</div>

<table>
  <tr>
    <th width="50%">English</th>
    <th width="50%">فارسی</th>
  </tr>
  <tr>
    <td>

### Phase 2
- [ ] SVG export
- [ ] Custom gradient builder (2 colors + angle)
- [ ] LocalStorage settings persistence
- [ ] Share link (state encoded in URL)

### Phase 3
- [ ] Social media size presets (Twitter, Instagram)
- [ ] Custom theme creator
- [ ] Diff mode for code changes

### Phase 4
- [ ] Browser extension
- [ ] Watermark customization
- [ ] Team presets

</td>
    <td dir="rtl">

### فاز ۲
- [ ] خروجی SVG
- [ ] سازنده گرادیانت اختصاصی (۲ رنگ + زاویه)
- [ ] ذخیره تنظیمات در localStorage
- [ ] لینک اشتراک‌گذاری (state در URL)

### فاز ۳
- [ ] پریست ابعاد شبکه‌های اجتماعی
- [ ] سازنده تم اختصاصی
- [ ] حالت Diff برای نمایش تغییرات کد

### فاز ۴
- [ ] افزونه مرورگر
- [ ] شخصی‌سازی واترمارک
- [ ] پریست‌های تیمی

</td>
  </tr>
</table>

<br>

---

<br>

<div align="center">
  
## 📄 License

</div>

<table>
  <tr>
    <td width="50%">

[MIT](LICENSE) © 2026 Maddyrampant

</td>
    <td dir="rtl" width="50%">

لایسنس [MIT](LICENSE) — آزاد برای استفاده شخصی و تجاری

</td>
  </tr>
</table>

<br>

---

<br>

<div align="center">
  <p>
    Built with ❤️ for Persian-speaking developers
    <br>
    ساخته شده با ❤️ برای توسعه‌دهنده‌های فارسی‌زبان
  </p>
  <p>
    <a href="https://github.com/Maddyrampant/maddyshot">GitHub</a>
    ·
    <a href="https://github.com/Maddyrampant/maddyshot/issues">Report Bug</a>
    ·
    <a href="https://github.com/Maddyrampant/maddyshot/discussions">Discussions</a>
  </p>
</div>

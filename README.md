# 🚀 Portfolio Website - Bryan Yogie Saputra

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

> **Website portfolio pribadi modern dengan animasi interaktif, desain responsif, dan integrasi sosial media lengkap.**

---

## 📋 Daftar Isi

- [Overview](#-overview)
- [Fitur Utama](#-fitur-utama)
- [Demo & Screenshots](#-demo--screenshots)
- [Teknologi yang Digunakan](#-teknologi-yang-digunakan)
- [Struktur Proyek](#-struktur-proyek)
- [Instalasi](#-instalasi)
- [Penggunaan](#-penggunaan)
- [Kustomisasi](#-kustomisasi)
- [Animasi & Efek](#-animasi--efek)
- [Responsive Design](#-responsive-design)
- [Browser Support](#-browser-support)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [Kontak](#-kontak)
- [License](#-license)

---

## 🎯 Overview

Website portfolio ini dirancang untuk menampilkan profil profesional, project, hobi, dan cara menghubungi saya dengan tampilan yang modern, interaktif, dan user-friendly. Dibangun dengan teknologi web terkini dan dilengkapi dengan animasi smooth yang meningkatkan user experience.

### 🌟 Highlights

- ✨ **Desain Modern** dengan gradient background dan glassmorphism
- 🎭 **40+ Animasi Interaktif** menggunakan CSS keyframes
- 📱 **Fully Responsive** - sempurna di semua device
- 🗺️ **Google Maps Integration** untuk lokasi
- 💬 **WhatsApp Direct Integration** dengan floating button
- 🎨 **Particle Background Animation** untuk visual yang menarik
- ⚡ **Fast Loading** dengan optimasi CSS dan JavaScript
- 🔗 **Multi-Platform Links** (GitHub, Instagram, YouTube, dll)

---

## ✨ Fitur Utama

### 1. **Home Page** 🏠
- Hero section dengan gradient animated background
- Profile image dengan pulse animation
- Particle floating background untuk efek visual
- Call-to-action button dengan hover effects
- Smooth scroll animations

### 2. **About Page** 👤
- Profil lengkap dengan image hover effects
- Skills section dengan animated cards
- Timeline-style content presentation
- Icon animations dengan bounce effects
- Gradient backgrounds untuk visual appeal

### 3. **Portfolio Page** 💼
- **Projects Section:**
  - 3 project cards dengan gambar dan deskripsi
  - Badge indicators untuk kategori project
  - Hover effects dengan scale dan shadow
  - Direct links ke GitHub repositories
  
- **Hobbies Section:**
  - 4 hobby cards dengan visual menarik
  - Card flip animations on hover
  - Professional photography showcase

### 4. **Contact Page** 📞
- **Social Media Integration:**
  - WhatsApp (dengan auto-message template)
  - Instagram
  - GitHub
  - YouTube
  - Lynk.id
  
- **Interactive Google Maps:**
  - Embedded map Surakarta, Jawa Tengah
  - Smooth zoom dan pan functionality
  - Location header dengan gradient
  
- **WhatsApp Floating Button:**
  - Sticky button di corner bawah kanan
  - Pulse animation untuk attention
  - Direct link dengan pre-filled message

### 5. **Navigation** 🧭
- Sticky navbar dengan blur backdrop
- Active page indicator dengan animated underline
- Smooth scroll behavior
- Mobile-friendly hamburger menu
- Responsive collapse navigation

---

## 🖼️ Demo & Screenshots

### Desktop View
```
┌─────────────────────────────────────────┐
│  🎨 Hero Section dengan Gradient BG     │
│  └─ Animated particles floating        │
├─────────────────────────────────────────┤
│  👤 Profile Section                     │
│  └─ Image dengan pulse animation       │
├─────────────────────────────────────────┤
│  💼 Projects Grid (3 columns)           │
│  └─ Card hover effects + badges        │
└─────────────────────────────────────────┘
```

### Mobile View
```
┌──────────────┐
│  📱 Mobile   │
│  Responsive  │
│  └─ Stacked  │
│     Layout   │
└──────────────┘
```

---

## 🛠️ Teknologi yang Digunakan

### Frontend
| Technology | Version | Purpose |
|-----------|---------|---------|
| HTML5 | - | Struktur website |
| CSS3 | - | Styling & animations |
| JavaScript (Vanilla) | ES6+ | Interactivity |
| Bootstrap | 5.3.3 | Responsive framework |
| Font Awesome | 6.0.0 | Icons library |

### External Services
- **Google Maps API** - Embedded maps
- **WhatsApp Business API** - Direct messaging
- **CDN Services** - Bootstrap & Font Awesome

### Design Features
- CSS Grid & Flexbox
- CSS Animations & Keyframes
- CSS Variables untuk theming
- Gradient backgrounds
- Box shadows & transforms
- Backdrop filters (glassmorphism)

---

## 📁 Struktur Proyek

```
portfolio-website/
│
├── index.html              # 🏠 Halaman utama
├── about.html              # 👤 Halaman tentang saya
├── portfolio.html          # 💼 Halaman portfolio
├── contact.html            # 📞 Halaman kontak
│
├── img/                    # 📸 Folder gambar
│   ├── foto_profil.jpg     # Profile picture
│   ├── Project 1.jpg       # Screenshot project 1
│   ├── Project 2.jpg       # Screenshot project 2
│   ├── Project 3.jpg       # Screenshot project 3
│   ├── Hobi 1.jpg         # Hobby image 1
│   ├── Hobi 2.jpg         # Hobby image 2
│   ├── Hobi 3.jpg         # Hobby image 3
│   └── Hobi 4.jpg         # Hobby image 4
│
└── README.md              # 📖 Dokumentasi (file ini)
```

### File Details

#### **index.html** (6.5KB)
- Hero section dengan animated background
- Profile introduction
- CTA button ke portfolio
- Particle background generation script

#### **about.html** (5.8KB)
- Detailed biography
- Skills showcase dengan icons
- Animated timeline presentation

#### **portfolio.html** (7.2KB)
- Projects grid dengan 3 cards
- Hobbies showcase dengan 4 cards
- GitHub integration links

#### **contact.html** (6.9KB)
- Social media cards (5 platforms)
- Google Maps embed
- WhatsApp floating button
- Interactive animations

---

## 🚀 Instalasi

### Prerequisites
- Browser modern (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime, Atom)
- Optional: Live Server extension untuk development

### Quick Start

1. **Clone Repository**
```bash
git clone https://github.com/Yogiexc/portfolio-website.git
cd portfolio-website
```

2. **Struktur Folder**
```bash
# Buat folder img jika belum ada
mkdir img

# Tambahkan gambar-gambar yang dibutuhkan ke folder img/
# - foto_profil.jpg
# - Project 1.jpg, Project 2.jpg, Project 3.jpg
# - Hobi 1.jpg, Hobi 2.jpg, Hobi 3.jpg, Hobi 4.jpg
```

3. **Buka di Browser**
```bash
# Double click index.html
# atau gunakan Live Server di VS Code
# atau buka melalui terminal:
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

### Alternative: Menggunakan Live Server

```bash
# Install Live Server globally
npm install -g live-server

# Jalankan di folder project
live-server
```

---

## 💡 Penggunaan

### Navigation Flow
```
Home (index.html)
  ├─→ About (about.html)
  ├─→ Portfolio (portfolio.html)
  │     ├─→ Project 1 (portfolio.html)
  │     ├─→ Project 2 (GitHub)
  │     └─→ Project 3 (GitHub)
  └─→ Contact (contact.html)
        ├─→ WhatsApp
        ├─→ Instagram
        ├─→ GitHub
        ├─→ YouTube
        └─→ Lynk.id
```

### Interaksi User

1. **Landing di Home**
   - Lihat hero section dengan animasi
   - Baca introduction
   - Klik "Lihat Portofolio Saya"

2. **Explore Portfolio**
   - Hover pada cards untuk melihat effects
   - Klik project untuk melihat detail di GitHub
   - Scroll untuk melihat hobbies

3. **Hubungi via Contact**
   - Klik icon social media
   - Klik WhatsApp floating button
   - Lihat lokasi di Google Maps

---

## 🎨 Kustomisasi

### Mengganti Warna Theme

Edit di setiap file HTML, cari bagian `<style>` dan ubah:

```css
/* Gradient utama */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Ubah menjadi: */
background: linear-gradient(135deg, #FF6B6B 0%, #4ECDC4 100%);

/* Warna accent button */
background: linear-gradient(135deg, #ff9800, #ff5722);

/* Ubah menjadi: */
background: linear-gradient(135deg, #00D4FF, #0099CC);
```

### Mengganti Informasi Pribadi

#### 1. **Nama & Bio** (index.html, about.html)
```html
<!-- Cari dan ganti: -->
<h1>Portofolio Bryan Yogie Saputra</h1>
<p>Seorang mahasiswa Teknik Informatika...</p>
```

#### 2. **Nomor WhatsApp** (contact.html)
```html
<!-- Cari dan ganti nomor: -->
<a href="https://wa.me/6285876941979?text=...">

<!-- Ubah menjadi nomor Anda: -->
<a href="https://wa.me/628XXXXXXXXXX?text=...">
```

#### 3. **Social Media Links** (contact.html)
```html
<!-- Instagram -->
<a href="https://www.instagram.com/USERNAME/">

<!-- GitHub -->
<a href="https://github.com/USERNAME">

<!-- YouTube -->
<a href="https://www.youtube.com/@USERNAME">
```

#### 4. **Lokasi Maps** (contact.html)
```html
<!-- Ganti embed URL Google Maps -->
<iframe src="https://www.google.com/maps/embed?pb=..."></iframe>
```

Cara mendapatkan URL embed:
1. Buka Google Maps
2. Cari lokasi Anda
3. Klik "Share" → "Embed a map"
4. Copy iframe code
5. Paste di contact.html

### Menambah/Mengurangi Project

Edit `portfolio.html`:

```html
<!-- Template Card Project -->
<div class="col-md-4">
  <div class="card">
    <div style="position: relative;">
      <span class="project-badge">KATEGORI</span>
      <img src="img/PROJECT_NAME.jpg" class="card-img-top" alt="Project Name">
    </div>
    <div class="card-body">
      <h5 class="card-title">
        <i class="fas fa-ICON"></i> Nama Project
      </h5>
      <p class="card-text">Deskripsi project Anda...</p>
      <a href="URL_PROJECT" target="_blank" class="btn btn-primary w-100">
        <i class="fas fa-eye me-2"></i>Lihat Proyek
      </a>
    </div>
  </div>
</div>
```

### Customizing Animations

```css
/* Ubah durasi animasi */
animation: fadeIn 1s ease;
/* Menjadi lebih cepat: */
animation: fadeIn 0.5s ease;

/* Ubah delay animasi */
animation-delay: 0.3s;
/* Menjadi lebih lama: */
animation-delay: 0.8s;

/* Disable animasi (jika ingin lebih simple) */
animation: none;
```

---

## 🎭 Animasi & Efek

### Daftar Animasi yang Digunakan

| Animation | Target Element | Duration | Effect |
|-----------|---------------|----------|---------|
| `fadeIn` | Cards, Main content | 0.6-1s | Opacity 0→1 |
| `fadeInDown` | Headers | 1s | Slide from top |
| `fadeInUp` | Text blocks | 1s | Slide from bottom |
| `fadeInRight` | Content sections | 1s | Slide from left |
| `slideIn` | Main containers | 0.8s | Scale + slide |
| `zoomIn` | Images | 1s | Scale up |
| `pulse` | Badges, Buttons | 2s | Scale breathing |
| `bounce` | Icons | 2s | Jump effect |
| `expand` | Underlines | 1s | Width growth |
| `float` | Particles | 15s | Random movement |
| `bounceIn` | WhatsApp button | 1s | Entrance effect |

### Hover Effects

```css
/* Card Hover */
.card:hover {
  transform: translateY(-15px) scale(1.02);
  box-shadow: 0 20px 50px rgba(102, 126, 234, 0.4);
}

/* Button Hover */
.btn-primary:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 20px rgba(255, 152, 0, 0.6);
}

/* Image Hover */
.profile-img:hover {
  transform: scale(1.05) rotate(5deg);
}
```

### Particle System

JavaScript untuk generate particles:

```javascript
// Create 50 animated particles
for (let i = 0; i < 50; i++) {
  const particle = document.createElement('div');
  particle.className = 'particle';
  particle.style.width = Math.random() * 5 + 2 + 'px';
  particle.style.left = Math.random() * 100 + '%';
  particle.style.top = Math.random() * 100 + '%';
  particlesContainer.appendChild(particle);
}
```

---

## 📱 Responsive Design

### Breakpoints

```css
/* Mobile First Approach */

/* Extra Small devices (phones, 0-575px) */
@media (max-width: 575px) {
  h1 { font-size: 1.8rem; }
  .card { margin-bottom: 15px; }
}

/* Small devices (landscape phones, 576px-767px) */
@media (max-width: 767px) {
  main { padding: 30px 20px; }
  h2 { font-size: 2rem; }
}

/* Medium devices (tablets, 768px-991px) */
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-6 { width: 50%; }
}

/* Large devices (desktops, 992px and up) */
@media (min-width: 992px) {
  main { padding: 60px; }
}
```

### Mobile Optimizations

✅ Touch-friendly button sizes (min 44x44px)
✅ Readable font sizes (min 16px)
✅ Optimized images untuk mobile
✅ Collapsible navigation menu
✅ Vertical stack layout untuk mobile
✅ Reduced animation complexity di mobile

---

## 🌐 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Full Support |
| Firefox | 88+ | ✅ Full Support |
| Safari | 14+ | ✅ Full Support |
| Edge | 90+ | ✅ Full Support |
| Opera | 76+ | ✅ Full Support |
| Mobile Safari | iOS 14+ | ✅ Full Support |
| Chrome Mobile | Android 90+ | ✅ Full Support |

### Features Compatibility

- ✅ CSS Grid & Flexbox
- ✅ CSS Animations & Keyframes
- ✅ CSS Gradients
- ✅ Backdrop-filter (with fallback)
- ✅ CSS Transforms
- ✅ Viewport units (vh, vw)
- ✅ Media queries

---

## 🗺️ Roadmap

### Version 1.0 (Current) ✅
- [x] 4 halaman utama (Home, About, Portfolio, Contact)
- [x] Responsive design
- [x] 40+ animasi interaktif
- [x] WhatsApp integration
- [x] Google Maps integration
- [x] Social media links

### Version 1.1 (Planned) 🚧
- [ ] Dark mode toggle
- [ ] Multi-language support (ID/EN)
- [ ] Blog section
- [ ] Project filter by category
- [ ] Testimonials section
- [ ] Contact form dengan email integration

### Version 2.0 (Future) 💭
- [ ] Backend dengan Node.js
- [ ] Database untuk projects (MongoDB)
- [ ] Admin panel untuk edit content
- [ ] Analytics dashboard
- [ ] PWA support (offline mode)
- [ ] Performance optimization
- [ ] SEO optimization
- [ ] Custom domain deployment

---

## 🤝 Contributing

Kontribusi sangat diterima! Berikut cara berkontribusi:

### 1. Fork Repository
```bash
# Klik tombol "Fork" di GitHub
```

### 2. Clone Fork Anda
```bash
git clone https://github.com/YOUR-USERNAME/portfolio-website.git
cd portfolio-website
```

### 3. Create Branch
```bash
git checkout -b feature/AmazingFeature
```

### 4. Commit Changes
```bash
git add .
git commit -m "Add: Amazing new feature"
```

### 5. Push ke Branch
```bash
git push origin feature/AmazingFeature
```

### 6. Open Pull Request
- Buka GitHub repository
- Klik "Pull Request"
- Jelaskan perubahan Anda

### Contribution Guidelines

📌 **Code Style:**
- Gunakan indentasi 2 spaces
- Gunakan nama variable yang deskriptif
- Tambahkan komentar untuk code kompleks

📌 **Commit Messages:**
- `Add:` untuk fitur baru
- `Fix:` untuk bug fixes
- `Update:` untuk perubahan existing feature
- `Remove:` untuk menghapus code

📌 **Testing:**
- Test di minimum 3 browsers
- Test responsive di mobile & tablet
- Pastikan no console errors

---

## 📞 Kontak

**Bryan Yogie Saputra**

- 📧 Email: [yogiexsaputra@gmail.com](mailto:bryan@example.com)
- 💬 WhatsApp: [+62 858-7694-1979](https://wa.me/6285876941979)
- 📱 Instagram: [@yogiexct](https://www.instagram.com/yogiexct/)
- 💻 GitHub: [@Yogiexc](https://github.com/Yogiexc)
- 🎥 YouTube: [@bryanyogiexc](https://www.youtube.com/@bryanyogiexc)
- 🔗 Lynk.id: [yogiexc](https://lynk.id/yogiexc)

### Support

Jika menemukan bug atau ingin request fitur:

1. Buka [Issues](https://github.com/Yogiexc/portfolio-website/issues)
2. Klik "New Issue"
3. Pilih template (Bug Report / Feature Request)
4. Isi detail dan submit

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

```
MIT License

Copyright (c) 2025 Bryan Yogie Saputra

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 🙏 Acknowledgments

- [Bootstrap](https://getbootstrap.com/) - Responsive framework
- [Font Awesome](https://fontawesome.com/) - Icon library
- [Google Fonts](https://fonts.google.com/) - Typography
- [Google Maps](https://developers.google.com/maps) - Maps integration
- [Gradient Hunt](https://gradienthunt.com/) - Gradient inspirations
- [CSS-Tricks](https://css-tricks.com/) - CSS references

---

## 📊 Project Stats

![GitHub repo size](https://img.shields.io/github/repo-size/Yogiexc/portfolio-website?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/Yogiexc/portfolio-website?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/Yogiexc/portfolio-website?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/Yogiexc/portfolio-website?style=flat-square)
![GitHub license](https://img.shields.io/github/license/Yogiexc/portfolio-website?style=flat-square)

---

## ⭐ Show Your Support

Jika project ini membantu Anda, berikan ⭐ di repository!

**Made with ❤️ by Bryan Yogie Saputra**

---

<div align="center">
  <sub>Built with passion and lots of ☕</sub>
</div>
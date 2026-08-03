```markdown
# Big Wura Hair Care

> **Zenith Web #001** — Production-ready marketing website for a premium hair care brand.

## 📖 Overview

A premium one-page marketing website for **Big Wura Hair Care**, a Lagos-based beauty brand specializing in high-quality hair care products and accessories. The site serves as a digital storefront, showcasing products with a WhatsApp-first customer journey.

**Live Demo:** [bigwurahaircare.vercel.app](https://bigwurahaircare.vercel.app/)

## 🎯 Key Features

- 🚀 **Performance Optimized** — Lazy loading, WebP-ready, minimal repaints
- ♿ **WCAG AA Compliant** — Accessible forms, keyboard navigation, screen reader support
- 🔍 **SEO Ready** — Meta tags, Open Graph, Twitter Cards, JSON-LD structured data
- 📱 **Fully Responsive** — Mobile-first, works on all screen sizes
- 🎨 **Premium UI/UX** — Smooth animations, interactive elements, gold-accented branding
- 💬 **WhatsApp Integration** — Contact form generates WhatsApp messages automatically
- 🖼️ **Lightbox Gallery** — Click images to view full-size
- 📋 **Animated FAQ** — Smooth open/close transitions with `<details>` elements
- 🎯 **Active Navigation** — Highlights current section while scrolling

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, flexbox, grid, animations
- **JavaScript (Vanilla)** — No frameworks, minimal dependencies
- **Fonts** — Fraunces (serif) + Manrope (sans-serif)

## 📁 Project Structure

```

/
├── index.html              # Main HTML file
├── robots.txt              # Search engine crawling rules
├── sitemap.xml             # XML sitemap
├── favicon.ico             # Browser favicon
├── apple-touch-icon.png    # iOS home screen icon
├── site.webmanifest        # PWA manifest
├── logo.png                # Brand logo (for structured data)
└── assets/
└── images/
├── image1.png      # Hydrating Hair Shampoo
├── image2.png      # Leave-In Conditioner
├── image3.png      # Professional Comb Set
├── image4.png      # Dreadlock Styling Foam
├── image5.png      # Satin Hair Bonnets
└── image6.png      # Electric Hot Comb

```

## 🚀 Deployment

### Vercel (Recommended)

1. Push code to GitHub
2. Import repository to [Vercel](https://vercel.com)
3. Deploy — it's that simple!

### Manual Deployment

1. Upload all files to your web server
2. Ensure `index.html` is in the root directory
3. Create `assets/images/` folder for product images

## 🔧 Configuration

### Update Domain
Search and replace `bigwurahaircare.vercel.app` with your custom domain in:
- `index.html` — canonical URL, OG URLs, JSON-LD
- `robots.txt` — sitemap URL
- `sitemap.xml` — all URLs

### Update Phone Number
The WhatsApp number appears in:
- HTML links (keep as-is for SEO)
- JavaScript `CONFIG.PHONE_NUMBER` constant (for contact form)

**Note:** WhatsApp links in HTML are intentionally kept static for better crawlability. Only the contact form uses the JavaScript constant.


📊 Lighthouse Scores

Target scores for Google Lighthouse:

· Performance: 95+
· Accessibility: 100
· Best Practices: 100
· SEO: 100

👥 Credits

· Design & Development: Zenith Web #001
· Client: Big Wura Hair Care
· Fonts: Fraunces + Manrope

📄 License

All rights reserved © Big Wura Hair Care

---

Made with ❤️ for Big Wura Hair Care

```
# 🌿 Nature's Essence - Natural Wellness Landing Page

A beautiful, production-ready landing page built with Astro for a company specializing in importing natural food products, aromatic oils, and beauty & skincare treatments.

## ✨ Features

- **Modern Astro Framework**: Fast, optimized, and SEO-friendly.
- **Multi-language Support (i18n)**: Fully localized in English and Spanish with a dedicated `LanguageSwitcher`.
- **Persistent Dark Mode**: Supports light and dark themes with system preference detection and `localStorage` persistence.
- **Elegant Design**: Natural color palette with smooth animations and polished UI components.
- **Automated Year Footer**: Copyright year updates automatically via Astro frontmatter.
- **Fully Responsive**: Mobile-first design implemented with custom CSS and Tailwind CSS integration.
- **SEO Optimized**: Complete meta tags, Open Graph, and Twitter Cards for both languages.

## 🎨 Sections

1. **Hero Section**: Eye-catching introduction with language-specific CTAs.
2. **About Section**: Company mission and values with feature highlights.
3. **Products Section**: Showcase of 4 main product categories.
4. **Testimonials Section**: Customer reviews and social proof.
5. **Contact Section**: Contact form and business information.
6. **Footer**: Navigation, newsletter signup, social links, and automated copyright year.

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ installed on your system
- npm or yarn package manager

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd ryl-landing
```

1. Install dependencies:

```bash
npm install
```

1. Start the development server:

```bash
npm run dev
```

1. Open your browser and visit:

```
http://localhost:4321
```

## 📦 Build for Production

To create an optimized production build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

## 🗂️ Project Structure

```
/
├── public/
│   ├── favicon.svg
│   └── robots.txt
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── About.astro
│   │   ├── Products.astro
│   │   ├── Testimonials.astro
│   │   ├── Contact.astro
│   │   ├── Footer.astro
│   │   ├── ThemeToggle.astro       # NEW: Handles theme switching
│   │   └── LanguageSwitcher.astro  # NEW: Handles i18n routing
│   ├── i18n/
│   │   ├── locales/
│   │   │   ├── en.json            # English translations
│   │   │   └── es.json            # Spanish translations
│   │   └── utils.ts               # Translation helper logic
│   ├── layouts/
│   │   └── BaseLayout.astro       # Master layout with theme/i18n scripts
│   ├── styles/
│   │   └── global.css             # Design system & theme variables
│   └── pages/
│       ├── index.astro            # Root (English)
│       └── es/
│           └── index.astro        # Spanish localization
├── astro.config.mjs               # Configuration (Dev Toolbar disabled)
├── package.json
└── tsconfig.json
```

## 🎨 Design System

### Color Palette

- **Primary**: `#2d5f3f` (Forest Green) / `#8b9d77` (Dark Mode Sage)
- **Secondary**: `#d4a574` (Warm Beige)
- **Accent**: `#8b9d77` (Sage Green) / `#2d5f3f` (Dark Mode Forest)
- **Background**: `#faf9f6` (Ivory) / `#1a1a1a` (Dark Gray)
- **Text**: `#2c2c2c` (Charcoal) / `#f0f0f0` (Off-white)

### Typography

- **Headings**: Poppins (Sans-serif)
- **Body**: Lora (Serif)

## 🔧 Customization

### Update Multi-language Content

Instead of editing `.astro` files directly for text, update the JSON files in `src/i18n/locales/`:

- `en.json` for English content
- `es.json` for Spanish content

### Update Images

Replace the Unsplash URLs in the components with your own images:

- Hero background in `Hero.astro`
- Product images in `Products.astro`
- Testimonial avatars in `Testimonials.astro`

### Update SEO

SEO settings are handled per-page in `src/pages/index.astro` and `src/pages/es/index.astro`.

### Update Theme Variables

Modify the CSS variables in `src/styles/global.css` under the `:root` and `:root[data-theme="dark"]` selectors.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🌐 Deployment

This Astro project can be deployed to various platforms:

### Netlify

```bash
npm run build
# Deploy the dist/ folder
```

### Vercel

```bash
npm run build
# Deploy the dist/ folder
```

### GitHub Pages

Configure `astro.config.mjs` with your site URL and deploy the `dist/` folder.

## 📄 License

This project is open source and available for commercial use.

---

Built with ❤️ using [Astro](https://astro.build) - The web framework for content-driven websites.

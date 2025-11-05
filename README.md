# 🌿 Nature's Essence - Natural Wellness Landing Page

A beautiful, production-ready landing page built with Astro for a company specializing in importing natural food products, aromatic oils, and beauty & skincare treatments.

## ✨ Features

- **Modern Astro Framework**: Fast, optimized, and SEO-friendly
- **Fully Responsive**: Mobile-first design that works on all devices
- **Elegant Design**: Natural color palette with smooth animations
- **SEO Optimized**: Complete meta tags, Open Graph, and Twitter Cards
- **Performance Focused**: Optimized images and minimal JavaScript
- **Accessible**: Semantic HTML with proper ARIA labels
- **Pure CSS**: No external frameworks, just clean custom styles

## 🎨 Sections

1. **Hero Section**: Eye-catching introduction with call-to-action
2. **About Section**: Company mission and values with feature highlights
3. **Products Section**: Showcase of 4 main product categories
4. **Testimonials Section**: Customer reviews and social proof
5. **Contact Section**: Contact form and business information
6. **Footer**: Navigation, newsletter signup, and social links

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

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit:
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
│   │   └── Footer.astro
│   ├── styles/
│   │   └── global.css
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 🎨 Design System

### Color Palette

- **Primary**: `#2d5f3f` (Forest Green)
- **Secondary**: `#d4a574` (Warm Beige)
- **Accent**: `#8b9d77` (Sage Green)
- **Background**: `#faf9f6` (Ivory)
- **Text**: `#2c2c2c` (Charcoal)

### Typography

- **Headings**: Poppins (Sans-serif)
- **Body**: Lora (Serif)

## 🔧 Customization

### Update Company Information

Edit the content in each component file located in `src/components/`:
- Company name, tagline, and mission in `About.astro`
- Product descriptions in `Products.astro`
- Testimonials in `Testimonials.astro`
- Contact information in `Contact.astro` and `Footer.astro`

### Update Images

Replace the Unsplash URLs in the components with your own images. Look for:
- Hero background in `Hero.astro`
- Product images in `Products.astro`
- Testimonial avatars in `Testimonials.astro`

### Update SEO

Edit the meta tags in `src/pages/index.astro`:
- Site title
- Description
- Keywords
- Open Graph image

### Update Colors

Modify the CSS variables in `src/styles/global.css` under the `:root` selector.

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

## 🤝 Support

For questions or support, please contact:
- Email: hello@naturesessence.com
- Website: [Your Website]

---

Built with ❤️ using [Astro](https://astro.build) - The web framework for content-driven websites.


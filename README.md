# Faruk Balarabe — Personal Website

Dark, minimal, editorial portfolio for Faruk Balarabe (Medical student · UI/UX Designer · Product Builder · Health-Tech Founder).

## Structure

```
faruk-website/
├── index.html          # Home
├── about.html
├── work.html
├── services.html
├── products.html
├── nexgene.html
├── contact.html
├── projects/
│   ├── nexgene.html
│   └── swiftpay.html
├── css/styles.css
├── js/main.js
└── assets/             # Add images, favicon, etc.
```

## Design system

- **Background**: Near-black `#070707`
- **Text**: Off-white + secondary gray
- **Accent**: Restrained violet `#8b7cf6`
- **Typography**: Inter + JetBrains Mono
- **Feel**: Minimal, premium, slightly futuristic, editorial

## How to update content

1. **Projects** — Edit or add HTML files in `/projects/`. Link them from `work.html` and the home page.
2. **Products** — Update the cards in `products.html`. Later you can connect to Gumroad, Lemon Squeezy, or Stripe.
3. **About / bio** — Edit `about.html`.
4. **Contact form** — Currently a demo. Connect it to:
   - [Formspree](https://formspree.io)
   - [Getform](https://getform.io)
   - Or your own backend
5. **Email** — Replace the placeholder in `contact.html`.
6. **Portrait** — Replace the placeholder in `about.html` with a real photo (recommended size ~800×1000).

## Deployment (recommended)

### Option 1: Cloudflare Pages (excellent free tier + performance)
1. Push this folder to a GitHub repository.
2. Go to [Cloudflare Pages](https://pages.cloudflare.com) → Create project → Connect GitHub.
3. Build settings: **Framework preset = None**, Build command = empty, Output directory = `/` (or root of the repo).
4. Add your custom domain (e.g. `farukbalarabe.com`).

### Option 2: Vercel
1. Import the GitHub repo at [vercel.com](https://vercel.com).
2. No build command needed.
3. Add custom domain.

### Option 3: Netlify
Same idea — drag & drop the folder or connect GitHub.

## Custom domain suggestions

- farukbalarabe.com
- faruk.design
- farukbalarabe.dev
- farukbuilds.com

## Next steps you may want

- Add real project images / mockups
- Connect contact form to a form service
- Add a simple blog / journal later (can use a static generator or just more HTML pages)
- Set up Gumroad or Lemon Squeezy for digital products
- Add Open Graph images and a favicon
- Optional: subtle page transitions or more motion if desired

Built to be fast, easy to maintain, and ready to monetize.

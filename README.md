# Royal Spice Restaurant Website

Premium static restaurant website built with HTML5, CSS3, JavaScript, and Bootstrap 5. It is deploy-ready for GitHub Pages, Vercel, Netlify, or any static host.

## Pages

- `index.html`
- `about.html`
- `menu.html`
- `gallery.html`
- `reservation.html`
- `contact.html`
- `404.html`

## Features

- Responsive Bootstrap 5 layout
- Sticky navigation
- Scroll progress bar
- Loading screen
- Smooth scrolling
- Back-to-top button
- Floating WhatsApp and call buttons
- Dark mode toggle
- Menu category filtering
- Gallery masonry layout with lightbox
- Counter animation
- Reveal-on-scroll animation
- Typing effect
- Frontend validation for reservation, contact, and newsletter forms
- SEO meta tags, Open Graph tags, Twitter card, canonical URLs
- Schema.org Restaurant JSON-LD
- Favicon, `robots.txt`, and `sitemap.xml`

## Customization

Update the phone numbers in `assets/js/main.min.js`:

```js
const CONFIG = {
  phone: "+919876543210",
  wa: "919876543210",
  brand: "Royal Spice"
};
```

Update canonical and sitemap URLs from `https://royal-spice.vercel.app/` to your production domain.

## Deploy on Vercel

1. Push this folder to a GitHub repository.
2. Import the repository in Vercel.
3. Keep the framework preset as `Other`.
4. Leave build command empty.
5. Deploy.

No backend or build process is required.

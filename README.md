# METRO INK & STITCH — Website

Art-driven, print-shop aesthetic. Black + cream + signal red, Bungee/Archivo Black display type, halftone textures, grain overlay, marquee strip, hover-flip service cards. Now includes the full Metro Ink & Stitch logo system in nav and footer.

## Files

```
metro-ink/
├── index.html              Main page
├── styles.css              All styling
├── netlify.toml            Deploy + headers config
├── robots.txt              SEO
├── favicon-32.png          Browser tab icon
├── favicon-180.png         Apple touch icon
└── logo/
    ├── BRAND-GUIDE.md      Logo system documentation
    ├── favicon.svg
    ├── metro-ink-stitch-primary.svg          (used in print/merch)
    ├── metro-ink-stitch-primary-dark.svg     (used in footer)
    ├── metro-ink-stitch-horizontal.svg       (used in nav)
    ├── metro-ink-stitch-mark.svg             (avatars, patches)
    ├── metro-ink-stitch-mono-black.svg       (embroidery)
    ├── metro-ink-stitch-mono-cream.svg
    └── metro-ink-stitch-mono-red.svg
```

## Deploy to Netlify

1. Drop the entire folder onto https://app.netlify.com/drop
2. The contact form is already wired with `data-netlify="true"` — submissions show up automatically under **Forms** in your Netlify dashboard
3. Add a custom domain when ready (e.g. metroinkandstitch.com)

## What's included

- **Sticky nav** with logo mark
- **Hero** with massive display type, meta strip, and rotated marquee
- **6 services**: Screen Printing, DTG, Heat Transfers, Embroidery, Hats, Mugs (cards flip red on hover)
- **Work gallery** with 6 SVG poster mockups (replace with real photos when you have them)
- **4-step process** strip
- **Manifesto block** (the "we're a real shop" moment)
- **Quote form** that posts to Netlify Forms (no backend needed)
- **Footer** with oversized wordmark

## Easy customization

### Phone number / email
Add a real phone + email in the contact section. Search `Mon–Fri` in `index.html` to find that block.

### Replace gallery art with real photos
In `index.html`, find each `<div class="work-tile">`. Replace the inline `<svg>` block with:
```html
<img src="images/your-photo.jpg" alt="...">
```
And in `styles.css`, the `.tile-art` already has `aspect-ratio:1/1` so square photos work perfectly.

### Colors
Top of `styles.css`:
```css
--ink: #0d0d0d;     /* black */
--cream: #f3ecdb;   /* paper */
--red: #e63027;     /* signal red */
--mustard: #e8b923; /* highlight */
```

### Logo
Currently the wordmark is type. When you have a real logo SVG, replace the `.logo-mark` span and `.logo-text` span in `index.html`.

## Form submissions

Once deployed, go to your Netlify site dashboard → **Forms** tab. You can:
- See all quote submissions
- Set up email notifications (Forms → Settings → Form notifications)
- Connect to Zapier / Slack / etc.

## Performance / SEO notes

- Inline SVGs, no JS frameworks → loads instant
- Open Graph tags ready for social sharing
- Security headers configured in `netlify.toml`
- Reduced motion respected
- Mobile-responsive at 980px / 780px / 600px / 500px breakpoints

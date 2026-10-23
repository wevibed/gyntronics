# Gyntronics Technologies Website

Responsive React + Vite website concept for Gyntronics Technologies, based on the supplied Facebook advertisement.

## Included
- Responsive homepage, services, how-it-works, about and contact sections
- Service cards with relevant photography
- WhatsApp enquiry links and click-to-call
- Quote form that validates name and phone, then prepares a WhatsApp message (no backend/database is implied)
- SEO title/description, favicon and Cloudflare Pages configuration

## Business details used
- Advertised vehicle tracking offer: $65 once-off (confirm current offer and inclusions with the business)
- Main WhatsApp/call contact from the ad: 071 230 7680 (+263 71 230 7680)
- Additional number visible on the supplied ad: 078 778 1745 (not used as the primary contact)
- Location: Zimbabwe; exact business address not provided

## Run locally
Requires Node.js 20+.

```bash
npm install
npm run dev
```

## Build for Cloudflare Pages
```bash
npm install
npm run build
```
Set the Pages build command to `npm run build` and build output directory to `dist`.

Images are sourced from Unsplash URLs and therefore require an internet connection at runtime. Replace with licensed client-owned imagery before production if needed. This is a preview site; the advertised features, offer and installation terms should be confirmed by the business before launch.

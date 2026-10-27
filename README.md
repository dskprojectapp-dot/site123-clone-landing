# NovaForge Landing Page Clone

A responsive landing page clone inspired by a SITE123-style business website, built for a clean front-end experience and ready to be wrapped into an APK via Capacitor/WebView.

## Features
- Responsive hero section
- Services, work, pricing, and contact sections
- Mobile menu support
- Modern dark design
- Form demo with no backend required
- Ready for APK packaging after build

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
```

## API keys and environment config

This demo app does not require any API key for a basic landing page. If you later add real integrations, place keys in a `.env` or `.env.local` file and access them through Vite environment variables.

Example:

```bash
VITE_CONTACT_EMAIL=hello@yourdomain.com
VITE_WHATSAPP_NUMBER=+15551234567
VITE_GOOGLE_MAPS_API_KEY=your_map_key_here
VITE_STRIPE_PUBLISHABLE_KEY=your_stripe_key_here
VITE_RESEND_API_KEY=your_resend_key_here
```

Important:
- Never expose secret backend keys in frontend code.
- Keep private keys on the server or in a secure environment.
- For APK conversion, public front-end keys are safe, but server secrets should never be bundled into mobile code.

## Repo

https://github.com/dskprojectapp-dot/site123-clone-landing

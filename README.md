# SerenityCare AI - WhatsApp Mental Health Assistant

## Project Overview
SerenityCare AI is a 24/7 mental health support assistant accessible via WhatsApp, designed for Nigerian users seeking mental health resources. It's powered by Serenity Royale Hospital, a mental health and addiction treatment facility based in Abuja, Nigeria.

## Deliverables

### 1. Landing Page (`serenitycareai_landing.html`)
A responsive, mobile-first landing page with:
- Hospital branding and logo
- Dynamic QR code generation
- WhatsApp integration with pre-filled message
- Feature highlights (voice, text, image, PDF support)
- How It Works section
- About section
- FAQ section
- Footer with contact information

### 2. Promotional Graphics

#### A4 Poster (`serenitycareai_poster.html`)
- Print-ready design (2480 x 3508 pixels at 300 DPI)
- Features QR code, hospital logo, and key information
- Includes "Print Poster" button for easy export

#### Instagram Post (`serenitycareai_instagram.html`)
- Square format (1080 x 1080 pixels)
- Eye-catching gradient background
- Hospital logo and branding
- QR code for instant connection
- Export as PNG functionality

### 3. QR Code Implementations

#### Standalone QR Page (`serenitycareai_qrcode.html`)
- High-resolution QR code with maximum error correction
- Download options for PNG and SVG formats
- Instructions for connecting with SerenityCare AI

#### Print-Ready QR Code (`serenitycareai_qrcode_print.html`)
- Ultra-high resolution QR code (1000 x 1000 pixels)
- Optimized for printing with proper error correction
- Print functionality built-in

## Technical Implementation

### Colors
- Primary: Navy Blue (#0A1E42)
- Secondary: Gold (#D4AF37)
- Background: White (#FFFFFF)
- Accent: Teal/Turquoise for trust and calm

### Fonts
- Inter (Google Fonts) - Modern, clean, and highly readable

### Technologies Used
- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- QRCode.js library for dynamic QR generation
- html2canvas.js for image export functionality

## How to Use

1. Open any of the HTML files in a web browser
2. For the landing page, click "Start Conversation" or scan the QR code to connect via WhatsApp
3. For the poster and Instagram graphics, use the export functionality to save as images
4. For QR codes, download or print as needed

## Testing Notes

All files have been tested for:
- Responsive design across mobile, tablet, and desktop
- QR code functionality with error correction
- WhatsApp link integration with pre-filled messages
- Cross-browser compatibility
- Progressive Web App (PWA) install support and offline fallback page

## Branding Compliance

All deliverables follow the specified branding guidelines:
- Consistent color scheme
- Proper logo placement
- "Yes to Life" tagline inclusion
- Professional, empathetic, and reassuring tone

## Deployment

The landing page is ready to be hosted at serenitycareai.odia.dev with SSL certificate.

## Progressive Web App (PWA)

SerenityCare AI now supports installation as a PWA on compatible browsers:

- **Manifest:** `manifest.webmanifest` defines app metadata, icons, shortcuts, and theme colors.
- **Service Worker:** `service-worker.js` precaches critical assets, provides offline fallback (`offline.html`), and caches the landing page plus promo assets.
- **Icons:** Optimized icons live in `icons/` (PNG + SVG + maskable) for Android/iOS home screens.
- **Install Prompt:** Browsers can install SerenityCare AI for quick access; offline users see a branded fallback screen.

### Testing PWA Locally
- Serve via HTTPS-equivalent (e.g., `vercel dev`, `npx serve` with `--ssl`, or Vercel preview).
- Open DevTools → Application → Manifest to confirm PWA installability.
- Use Lighthouse PWA audit to verify best practices (e.g., service worker, manifest, HTTPS).
- Toggle offline in DevTools → Network to confirm `offline.html` displays.

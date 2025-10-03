# SEO Assets Instructions for SerenityCare AI

## Required Images for Social Media Sharing

### 1. Open Graph Image (og-image.jpg)
- **Dimensions:** 1200 x 630 pixels
- **Format:** JPG or PNG
- **Purpose:** Facebook, LinkedIn, and other social platforms
- **Design Requirements:**
  - Include SerenityCare AI logo
  - Include tagline "Yes to Life"
  - WhatsApp number: +234 702 674 3998
  - Hospital branding colors (Navy Blue #0A1E42, Gold #D4AF37)
  - Clear, readable text
  - Professional mental health imagery

### 2. Twitter Card Image (twitter-card.jpg)
- **Dimensions:** 1200 x 600 pixels (or 1200 x 675 for summary_large_image)
- **Format:** JPG or PNG
- **Purpose:** Twitter/X sharing
- **Design Requirements:**
  - Same as Open Graph but optimized for Twitter's aspect ratio
  - Keep important content centered (may be cropped on mobile)

### 3. Favicon (Optional Enhancement)
- Currently using inline SVG favicon
- Consider creating:
  - favicon.ico (16x16, 32x32, 48x48)
  - apple-touch-icon.png (180x180)
  - favicon-192.png (192x192 for Android)
  - favicon-512.png (512x512 for PWA)

## How to Generate These Images

### Option 1: Use the Instagram Post as Base
1. Open `serenitycareai_instagram.html` in browser
2. Export as PNG
3. Resize to required dimensions using image editor
4. Save as `og-image.jpg` and `twitter-card.jpg`

### Option 2: Create Custom Images
1. Use design tools like Canva, Figma, or Photoshop
2. Follow brand guidelines:
   - Navy Blue (#0A1E42) - Primary
   - Gold (#D4AF37) - Secondary
   - White (#FFFFFF) - Background
   - Font: Inter or similar sans-serif

### Option 3: Auto-Generate with HTML
Create HTML templates similar to the poster/Instagram post and export them at the required dimensions.

## Upload Instructions

Once created, these images should be:
1. Added to the root of your Vercel deployment
2. Named exactly as referenced in the meta tags:
   - `og-image.jpg`
   - `twitter-card.jpg`

## Testing Your SEO

### Tools to Test Implementation:
1. **Facebook Sharing Debugger:** https://developers.facebook.com/tools/debug/
2. **Twitter Card Validator:** https://cards-dev.twitter.com/validator
3. **LinkedIn Post Inspector:** https://www.linkedin.com/post-inspector/
4. **Google Rich Results Test:** https://search.google.com/test/rich-results
5. **Meta Tags Checker:** https://metatags.io/

### AI/LLM Indexing Verification:
- The site is configured to be indexed by ChatGPT, Claude, Google Bard/Gemini
- Robots.txt allows all major AI crawlers
- Meta tags provide context for AI understanding

## Important Notes:
- All images should be optimized for web (compressed without losing quality)
- Keep file sizes under 1MB for faster loading
- Ensure images work on both light and dark backgrounds
- Test on actual social platforms after deployment
